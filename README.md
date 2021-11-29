# Analiza podatkov s programom R - 2021/22

Vzorčni repozitorij za projekt pri predmetu APPR v študijskem letu 2021/22. 

## Tematika

V prvem delu projektne naloge bom analizirala dosežke učencev in učenk iz različnih držav, ki so sodelovali v mednarodnem programu PISA.

V drugem delu projektne naloge pa bom poskušala ugotoviti povezavo med dosežki učencev v projektu PISA in pa življenskim slogom učencev v posameznih državah.

PISA je mednarodna raziskava za preverjanje dosežkov učencev na treh področjih: 
bralna, matematična in naravoslovna pismenost. Raziskava se izvaja pod okriljem Organizacije za ekonomsko sodelovanje in razvoj (OECD). Raziskava poteka na vsake tri leta.

V raziskavo so vključeni 15-letniki, ne glede vrsto izobrazbe, razen tistih, ki ne obiskujejo izobraževalnih ustanov.

Podatke bom pridobila iz spletne strani OECD in zajela podatke za leta 2003, 2006, 2009, 2012, 2015 in 2018.

V drugem delu bom za 27 držav iz spletne strani Svetovne zdravstvene organizacije zajela podatke o zdravem življenskem slogu otrok in sicer:
* uživanje zajtrka
* telesna aktivno
* indeks telesne mase
* zadovoljstvo do življenja

Na voljo so podatki za leta od 2014 do 2018.

Povezava do spletnih strani:
* Mednarodna spletna stran projekta PISA: 
https://data.oecd.org/pisa/reading-performance-pisa.htm#indicator-chart
* Svetovna zdravstvena organizacija: 
https://gateway.euro.who.int/en/datasets/hbsc/

## Program

Glavni program in poročilo se nahajata v datoteki `projekt.Rmd`.
Ko ga prevedemo, se izvedejo programi, ki ustrezajo drugi, tretji in četrti fazi projekta:

* obdelava, uvoz in čiščenje podatkov: `uvoz/uvoz.r`
* analiza in vizualizacija podatkov: `vizualizacija/vizualizacija.r`
* napredna analiza podatkov: `analiza/analiza.r`

Vnaprej pripravljene funkcije se nahajajo v datotekah v mapi `lib/`.
Potrebne knjižnice so v datoteki `lib/libraries.r`
Podatkovni viri so v mapi `podatki/`.
Zemljevidi v obliki SHP, ki jih program pobere,
se shranijo v mapo `../zemljevidi/` (torej izven mape projekta).
