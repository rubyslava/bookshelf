[Michal Fogus and Chris Houser: The Joy of Clojure - Second Edition] (http://www.manning.com/fogus2/)
=====================================================================================================

@janherich
----------

Knižka 'The Joy of Clojure - Second Edition' má pomerne náročne poslanie. Cieľom jej Autorov bolo na jednej strane v knihe zohladniť všetko nové,
čo sa v Clojure svete udialo od vydania prvej edície, zároveň však ma poslúžiť ako 'complete guide' pre niekoho, kto zatial o Clojure ani nezavadil.

Kedže sa Clojure už venujem pomerne dlho (začal som s Clojure pracovať keď bola aktuálna verzia 1.2, momentálne je už vonku release 1.6 beta), nebudem
môcť celkom objektívne posúdiť knihu z pohľadu úplného začiatočníka, ale posnažím sa v tejto oblasti prejaviť čo najviac empatie.

Začiatok knihy mi prišiel pomerne kostrbatý (na druhej strane treba pamätať, že som mal k dispozícii stále len working-draft), po celkom peknom a
rozumnom úvode sa autori trocha zamotaju pri vysvetľovaní podstaty LISPu, hlavne pri banalite ako je infix verzus prefix usporiadanie operátorov, podľa
mňa celkom zbytočne vybafnú na newbie čitateľa (lebo len pre neho je sekcia určená) funkcie, ktore konvertuju z infix do prefix notácie len preto aby
nakoniec ajtak napísali, že sa jedná o velmi zjednodušenú implementáciu, ktorá funguje len do 3 argumentov (s odkazom na github repo s full implementáciou).
Toto môže podľa mňa úplného začiatočníka pomerne zmiasť, vystrašiť a odradiť, je mi síce jasné čo tým chceli autori ukázať, ale možno sa to dalo spraviť
trocha viac newbie friendly, aj ked si najmä po svojej poslednej prednáške o Clojure pre začiatočníkov dobre uvedomujem, že to vôbec nie je jednoduché.

Našťastie po tomto drobnom zaváhaní som už žiadne vačšie kiksy neobjavil a knihu je naozaj radosť čítať, filozofia Clojure jazyka a pridružených knižníc
je vysvetlená dobre, jasne a v správnej miere prekladaná praktickými príkladmi. Zvlášť by som chcel vyzdvihnúť kapitolu 'Why Clojure isn't especially object-oriented',
to doporučujem prečítať každemu OO programátorovi, ktorý sa obáva čo by získal a stratil ak by začal používať Clojure.

Vďaka talentu autorov vysvetliť aj zložité koncepty sa v knihe nájdu hodnotné informácie aj pre skúsených Clojure programátorov. Konkrétne v mojom prípade
sa jednalo o vysvetlenie konceptu reducerov (reducers framework), ktorý mi predtým nebol úplne jasný, pričom po prečitaní kapitoly 'Parallelism' som bol
doslova osvietený a zistil som, že myšlienka vedúca ku konceptu reducerov je geniálna a zázračne jednoduchá zároveň.

Sumár: Kniha určite stojí za prečítanie, nenechajte sa odradiť miestami trocha nemastným-neslaným začiatkom, zvyšok stojí za to.

### English version

Authors of the book 'The Joy of Clojure - Second Edition' had really difficult task. In their second book about Clojure, they try to explain new concepts which appeared
in the Clojure programming language since the first edition of 'The Joy of Clojure' was written, and at the same time, they try to write this new book in a such way, that
it's approachable even for total Clojure newcomers.

I already work with with Clojure for some time (i programm almost exclusively in Clojure for 2 years), so it will be difficult for me to judge the book from the total
beginner's point of view, but i will try to do my best.

I found the book start little bit inconsistent (but remember that i only red the working draft), after quite nice introductory explanation, the authors got little bit
stuck when explaining the differences between infix and prefix notations, they present a function which will convert operators and operands from one notation to another,
it's immediately noted that it's only toy implementation working only for up to three arguments and a link to repo with fully blown implementation is mentioned in a
footnote. I understand the purpose of this excercise, but i still think that the implementation of shifting function could be ommited because the total newcomers could be
confused and maybe even little bit scared - some less enlightened ones would probably think: "Oh, so i will need to write argument shifting functions in Clojure and it's
even not trivial ?" Because remember, that's the first Clojure code in the book that the readers will encounter.

But after particular point, the book is simply blast to read, very well written, the philosophy of Clojure core and contrib libraries is explained very well and this
explanation is interleaved with many practical code examples. I want to specially highlight the chapter 'Why Clojure isn't especially object-oriented' i recommend to
read this part for every OO programmer who is concerned about what he/she may lost if started using Clojure.

Because the book authors are so talented in the field of topics explanation, even seasoned Clojure veterans could find valuable informations and insights in this book.
In my case, it was the chapter about parallelism, more specific the part about reducers, this concept was not entirely clear to me, but after reading the well written
explanation, i was enlightened and i realized that the concept of reducible collections is genial and trivial at the same time.

Summary: this book is definitely worth reading, Clojure newcomers shouldn't be scared by the beginning, the rest of the book is amazing.
