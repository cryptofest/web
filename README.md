# CryptoFest - seminář

## Stream
 - [Live stream](https://www.youtube.com/watch?v=XGOUNxWJ9mg)
 - [Slides-only stream](https://www.youtube.com/watch?v=M8byBBJU_xQ) - for those in room with vision issues
 - [Playlist with all recordings](https://www.youtube.com/watch?v=kXGzezSSWEY&list=PLofm6RaC_O5oKTiq4kf4djzDMrU1zFGZg)

## Tento seminář je letos zaměřen na ty, co mají zájem o bezpečnost.

## Proběhne v sobotu 26. 5. od 10:00 v posluchárně 107 na [FIT CVUT](https://www.fit.cvut.cz) společně s [openSUSE Conference](https://events.opensuse.org/conference/oSC18) - [FB event](https://www.facebook.com/events/245865962642839/) [#CryptoFest](https://twitter.com/search?f=tweets&vertical=default&q=%23CryptoFest&src=typd)

### Registrace 

Registrace se provadí kliknutím na hvezdičku na tomto projektu zde na GitHubu

### Program


* 10:00 - 10:50 - [Ondřej Caletka](https://twitter.com/oskar456) - **Plně šifrovaný disk na moderním systému**

 - [slides](https://xn--ondej-kcb.caletka.cz/dl/slidy/20180526-CryptoFest-Plne_sifrovany_disk_na_modernim_systemu.pdf)
 - [video](https://www.youtube.com/watch?v=kXGzezSSWEY)

 Šifrování pevného disku je dnes běžná záležitost, šifrovat ale úplně celý disk je vždycky trochu oříšek. V přednášce si předvedeme, jak nastavit takové šifrování, které bude zároveň uživatelsky přívětivé i rozumně bezpečné. Použijeme přitom tyto ingredience: Btrfs, LVM, LUKS, GRUB, UEFI secure boot.



* 11:00 - 11:45 - Marcus Meissner - **Security Retrospective of the last year** 

 - [video](https://www.youtube.com/watch?v=hBCB3XOS5HQ)

 Last year was a quite busy year on the security front, various big issues 
happened, so its good to tell what security has done there and is doing for 
openSUSE and SUSE in general here.
 
 The talk will give a brief overview of how the SUSE Security Team works 
and operates. We will look at the reactive work including statistics, 
and also look at proactive secure development lifecycle activities.

 I will also highlight some of the big security issues we faced over the 
last year.

 Stack Clash from mid of 2017.

 Overview of the problem, what we do for mitigations, and our long way 
for compiler mitigations.

 Meltdown and Spectre

 As we hoped never to have a StackClash like issue again, CPU sidechannel 
issues surfaced which needed kernel mitigations begin of January.

 I will give an overview over what these issues are, and how 
we mitigated them or are still mitigating them.

* 13:00 - 13:45 - Vítězslav Čížek - **Introduction to TLS 1.3**

 TLS 1.3 is the brand new version of the SSL/TLS protocol. 
The draft of the standard was recently approved by IETF and it will be published as RFC in a couple of months.

 TLS 1.3 is a big redesign of the protocol which brings substantial changes such as better security or handshake speed-up.

 The talk will present its new features as well as compare the new protocol to the previous versions. 
It will also focus on the status of openSUSE, for example how are the web browsers, common cryptography libraries, and applications doing with regard to the TLS 1.3 support.


 

* 14:00 - 14:45 - Panos Georgiadis - **Let's talk about containers and security**



* 15:00 - 15:45 - Hans de Raad  - **The new EU CyberSecurity Act**

 Fibre to the home opens numerous interesting possibilities for both bona-fide and not so bona-fide use cases. 
Having your espresso machine or refrigerator being part of a multi-million device botnet which is attacking critical infrastructure might not necessarily be your first association when zipping your early morning caffeine fix. 
Not only might this notion be somewhat disruptive for your early morning zen-moment, you might also be held legally accountable for these actions as it is actually your home network participating in an international attack wreaking havoc on, let’s say, the healthcare information system of a close NATO ally. 
Nowadays there is zero quality control being enforced over internet connected devices in general. But the EU (and US) have decided this somewhat naive approach should come to an end.

 A new directive (NIS, Directive on the Security of Network and Information Systems) comes into effect. Especially for branches active in the development of internet connected devices with a direct application in the “quality of life improvement” domain, this will be something to look out for: 
 Medical devices 
 Automotive 
 Domotica

 This new directive includes the ambition of implementing a certification scheme for IT systems and devices, this scheme will be based on the existing ISO 15408 standard:

 “ISO/IEC 15408-1:2009 establishes the general concepts and principles of IT security evaluation and specifies the general model of evaluation given by various parts of ISO/IEC 15408 which in its entirety is meant to be used as the basis for evaluation of security properties of IT products.”

 What does this standard encompass? What does open-source and free software have to do with this? Let’s have a closer look in this talk!

* 16:00 - 16:45 [Petr Krčmář](https://twitter.com/krcmar) - **Role certifikátu při zabezpečení šifrovaného spojení**

 Šifrování se stává stále běžnějším a dostupnějším, většina navštěvovaných webů dnes má HTTPS. Neodmyslitelnou součástí dobře navrženého šifrování je také autentizace. V případě TLS se o ni starají certifikáty. Co to přesně certifikát je, jaká je jeho role a co všechno v něm najdeme?

* 17:00 - 17:30 [Karel Kočí](https://twitter.com/karel_koci) - **Bezpečné doručení distribučních balíčků**
 
 Většina linuxových distribucí distribuuje software ve formě binárních balíčků. Ty
jsou připraveny na serverech distribuce a uživatelé si je stahují přes internet do
svých počítačů. Pokud se útočníkovi podaří do balíčků dostat malware tak může
jednoduše ovládnout velké množství zařízení.

 V této prezentaci se dozvíte jak může takový útok být veden a jak se distribuce
proti těmto útokům chrání. Bude řeč o hashích, podepisování souborů, https,
certification pinningu a DNSSECu. Dohromady tyto technologie zabezpečují updaty
vašich systémů a přímo tak přispívají k zabezpečení internetu.


* 17:30 - 17:45 - Jan Dušátko -  Ochrana proti HashCat

 Hashcat je pro správce databází hesel dost nepřjemný. Ale i
on má své slabiny.


* 17:45 - 17:55 - Lightning talks (add in repo :) 


## Workshop - 351

* 15:30 - 16:45 - Jan Baier + [Pavel Dostál](https://twitter.com/pdostal_cz) - **Jak na PGP**

 Jak funguje PGP? Přidtě si naučit a vyzkoušet si podepisování a šifrování s PGP

## 17:59 PGP key singning PARTY před místností 105. Co a jak najdete na  [https://github.com/cryptofest/keysigning-guide](https://github.com/cryptofest/keysigning-guide)

## Partneři

[FIT ČVUT](https://fit.cvut.cz/) [vpsFree](https://vpsfree.cz/) 

## Organizátor 

[Klub Silicon Hill](https://www.siliconhill.cz/)
