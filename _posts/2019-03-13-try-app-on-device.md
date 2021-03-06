---
layout: post
title: Afprøv dine apps på en enhed
subtitle: Aktiver Android developer mode
comment: true
tags: [uge 11, appudvikling, android]
---

Det er jo rigtig fint at man kan afprøve sine apps på [android-emulatoren](2019-02-24-emulering) der følger med Android Studio. Men det føles nu stadig mere rigtigt at afprøve tingene på en fysisk enhed. 

Og da jeg netop har fået fat i en lidt ældre android telefon, vil jeg lige beskrive hvordan jeg gjorde telefonen klar til at modtage apps fra Android Studio.

Dette virker på en Samsung S5 neo. 
- gå ind i indstillinger

![alt text](/img/andev1.png "Indstillinger")

- scroll ned til bunden og klik på "Om enheden"

![alt text](/img/andev2.png "Om enheden")

- scroll ned til bunden og klik på "Softwareinfo"

![alt text](/img/andev3.png "Softwareinfo")

- Find det felt der hedder "Build-nummer"
- tab på feltet 7 gange

![alt text](/img/andev4.png "Build-nummer")

- gå tilbage til indstillingers grundmenu
- lige over "Om enheden" er der kommet et felt der hedder "Udviklerindstillinger"

![alt text](/img/andev5.png "Udviklerindstillinger")

- under afsnittet "Fejlsøgning" skal du aktivere indstillingen "USB-fejlsøgning"

![alt text](/img/andev6.png "USB-fejlsøgning")

Sæt et USB-kabel i computeren og i telefonen. På Windows skal der måske lige installeres nogle device drivers (skete automatisk på Win10), men når det er gjort er du klar til at smide dine udviklede apps over på telefonen. 

## Hvad hvis du har en anden type telefon?
Så kan det godt være at fremgangsmåden er en lille smule anderledes. Prøv at søge på nettet efter din telefonmodel, så burde det være muligt at få en vejledning frem.
