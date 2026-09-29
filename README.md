# Tehnogama Partner Hub — B2B demo

Interaktivni statički portal za prikaz na sastanku. Nema instalacije, servera, prijave na stvarni nalog ni API ključa.

## Postavljanje na GitHub Pages

1. Napravite novi **public** repozitorijum, npr. `Tehnogama-B2B`.
2. Raspakujte ZIP. U koren repozitorijuma otpremite **sav sadržaj**: `index.html`, `styles.css`, `app.js`, folder `assets` i folder `primeri`. Ne otpremajte ZIP kao jedini fajl.
3. Otvorite **Settings → Pages → Deploy from a branch**. Izaberite `main` i `/ (root)`, pa **Save**.
4. Demo će biti na adresi koju GitHub Pages prikaže u tom odeljku.

Možete i lokalno otvoriti `index.html` dvoklikom. Svi vizuelni resursi su u ZIP-u, pa radi bez spoljnog CDN-a.

## Predlog toka za sastanak

1. Uđite kao **AirTech Servis**. Katalog sadrži 24 stvarna naziva artikala Tehnogame, od ABAC kompresora i Cool sušača do Aignep pripreme vazduha, BOGE ulja i MAVEL motalica. Otvorite detalje sa tehničkim osobinama, šifrom, stanjem i cenom.
2. Dodajte artikle u korpu. U **Brzoj porudžbini** unesite SKU ili uvezite primer iz foldera `primeri` (CSV, TXT, XLSX ili XML). PDF ili fotografija se evidentira za ručnu proveru, bez čitanja sadržaja.
3. Pošaljite demo porudžbinu sa referencom. Pokažite statuse, ponavljanje porudžbine, izvoz pregleda u CSV i zahtev za ponudu/servis.
4. Promenite profil gore desno na **Tehnogama tim**. Otvorite porudžbinu, odobrite je i simulirajte slanje u ERP. Uredite partnerov osnovni rabat/limit, količinske rabate i lager pojedinačno ili kroz uvoz.
5. Pređite na **Metalopromet Plus** da pokažete drugačiji asortiman, popust i limit.

## Funkcije

- Odvojeni demo ulaz za dva kupca i administraciju; promena profila bez lozinke.
- Katalog sa pretragom, filterima po kategoriji/brendu/stanju, fotografijama, detaljima, šiframa i dokumentom sa specifikacijom.
- Ugovoreni popusti po partneru i podesivi količinski rabati na 10+, 20+ i 50+ komada.
- Korpa, referenca narudžbenice, napomena i dostava; statusi, istorija, ponovno naručivanje i kreditni limit.
- Uvoz porudžbine i admin uvoz zaliha iz CSV, TXT, XLSX i XML sa pregledom nepoznatih šifara pre primene.
- Zahtevi za ponudu i servis, administrativni pregled zahteva i simulirani ERP tok.
- Izvoz demo pregleda u CSV i lokalno čuvanje izmena u `localStorage`; **Resetuj demo** vraća početne podatke.

## Važno za prikaz

Nazivi proizvoda su preuzeti sa javne Tehnogamine prodavnice; link na izvorni artikal je u detaljima. Fotografije dostupne u demou su lokalne kopije javnih fotografija tog artikla. Šifre sa prefiksom `DEMO-` su pomoćne šifre za prototip. Partneri, osnovne B2B cene, popusti, količinski rabati, lager, porudžbine i zahtevi su ilustrativni. ERP tok i upload PDF/fotografije ne šalju podatke stvarnoj Tehnogami. Sistem nema stvarnu autentifikaciju ni plaćanje.

Detalji izvora su u `IZVORI.md`.
