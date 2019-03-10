# PR19up

## YouTubovi priljubljeni videi

[YouTube](https://www.youtube.com/) je popularna spletna stran, kamor lahko uporabniki naložijo videoposnetke, na njih komentirajo in jih ocenijo. YouTube vsak dan na [zavihku _Priljubljeno_](https://www.youtube.com/feed/trending) s pomočjo algoritmov ponudi vrsto videov, za katere meni, da so tisti čas popularni.

## Trending YouTube Video Statistics

Za projekt pri Podatkovnem rudarjenju bi uporabil podatke, zbrane [tukaj](https://www.kaggle.com/datasnaek/youtube-new). Zbirka vsebuje razne podatke o videih na strani Priljubljeno, od naslova, kategorije, števila ogledov, vse do števila _like_-ov in _dislike_-ov, števila komentarjev, datuma objave, ter mnogo drugih. Podatki so razvrščeni v posamezne datoteke glede na državo, trenutno so na voljo za 10 držav.

S temi podatki bi lahko poiskali mnogo zanimivih povezav. Nekaj idej:
* Povprečni delež _like_-ov (_ratio_) glede na kategorijo videa
* Za katere kanale YouTube najbolje in za katere najslabše predlaga videe pod priljubljeno, ugotovljeno glede na _ratio_
* Kateri kanali se najbolj konsistentno prikazujejo pod priljubljeno
* Katere oznake so najbolj pogoste med priljubljenimi videi
* Iskanje vzorcev med naslovi videov (ali so katere besede ali fraze zelo pogoste, kako VELIKE ČRKE v naslovu vplivajo na uvrstitev med priljubljene ...)
* Nekatere zanimive ideje predlagajo tudi na sami strani podatkov:
  * Kateri faktorji najbolj vplivajo na to, kako popularen bo video
  * Analiza podatkov skozi čas (kako se podatki spreminjajo, ali lahko poiščemo kakšne trende)
  * Uporaba kakšnih naprednih metod (nevronske mreže, procesiranje naravnega jezika ...)
