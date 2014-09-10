[Working Effectively with Legacy Code](http://www.amazon.com/Working-Effectively-Legacy-Michael-Feathers/dp/0131177052?tag=rubyslava-20)
=======================================================================================================================

@sukihub
--------

**TL;DR Nenechajte sa odradiť názvom, čítajte ak robíte akúkoľvek údržbu softvéru.**

*Working Effectively with Legacy Code* je veľmi zavádzajúci názov. Som si istý, že by som túto knihu úplne vynechal, ak by sa mi 
práve *legacy* kód nedostal pod ruky. Teraz viem, že by to bola veľká chyba. Kniha totiž ponúka omnoho viac ako len pár tipov 
a trikov špecifických pre 20 rokov staré kódy.

V prvom rade si pri čítaní uvedomíte, že slovo *legacy* neznamená len tie 20 rokov staré céčkové, fortranové alebo iné bájne aplikácie, 
o ktorých sem-tam počujeme, že ešte stále fungujú. Je to aj trieda, pri ktorej ste predvčerom (z lenivosti, pod hrozbou deadline-u, ...) 
porušili všetky pravidlá slušného programovania a obhájili to komentárom `// TODO ugly, will rewrite later`.

Povedzme, že ste na to mali dobrý dôvod. O mesiac ale už deadline netlačí a je čas triedu opraviť. Samozrejme je už v produkcii, iné 
časti aplikácie na nej závisia a vy si uvedomíte, že každý pokus o *rewrite later* bez toho, aby ste s ním strávili príliš veľa času, 
je beznádejne odsúdený na neúspech. A čím viac budete prepísanie odkladať, tým ťažšie ho bude naozaj spraviť.
 
No a podľa knihy je už aj toto kód, ktorý by mal dostať prívlastok *legacy*. Každý programátor by preto mal vedieť, čo s ním Michael Feathers odporúča robiť.

Ukazuje ako robiť *bezpečné* zmeny, ktoré nemajú nečakané následky. Sú prakticky zamerané, riešia reálne problémy. Nie sú vždy pekné alebo 
architektonicky správne, niekedy dokonca komplikujú kód. Ale v konečnom dôsledku ho umožnia riadok za riadkom zlepšovať.

Hlavnou myšlienkou knihy je, že starú triedu máte pokryť testami ešte predtým, ako sa jej dotknete. Za zmienku stojí aj to, že kniha 
bola vydaná v roku 2004 a Michael Feathers už vtedy (v čase písania recenzie to bolo pred 10 rokmi) bral unit testy ako hotovú a nevyhnutnú vec.
 
Škoda, že sa kniha nedá čítať štýlom 10 strán každý večer pred spaním. Musíte totiž dávať pozor, rozmýšľať a vracať sa k prečítaným častiam. 
Ja osobne som sa do čítania niekedy musel nútiť. Môže ale byť technické a odborné čítanie iné?

**Sumár:** Na začiatku som písal, že kniha má veľmi zavádzajúci názov. Ako by som ju teraz nazval ja? *Making Crappy Code Better, One Line at a Time*. 
Rátajte ale s tým, že čítať by ste ju mali pomaly a pozorne. A to, že sa treba potrápiť s príkladmi v C++ je už len malá cena, ktorú 
sa určite oplatí zaplatiť.

@dmacjam
--------

Aj tí najdisciplinovanejší občas, napríklad pod tlakom deadlinu, porušia správne princípy OOP programovania, kód degraduje časom alebo sa jednoducho dostaneme k “nepekným” zdrojákom od niekoho iného. Toto všetko sú príklady legacy kódu - je to kód náročný na pochopenie, zmenu a podľa autora knihy, jednoducho, kód bez testov. Tak ako efektívne pracovať s takýmto kódom, a robiť bezpečné zmeny?

Keďže pracujeme s neotestovaným kódom, musíme byt veľmi opatrní. Hlavnou ideou je, že nemôžeme efektívne pracovať s kódom pokiaľ nie je pokrytý testami - cieľom sú najmä rýchle UNIT testy. Náš čas je však cenný a dôležité je preto určiť, čo a v akej miere treba pokryť testami, aby naša plánovaná zmena bola bezpečná. Problémom pri testoch(v staticky typovaných jazykoch) tiež môže byť veľké množstvo závislostí, pretože pri testovaní je potrebné vytvorenie množstva ďalších spolupracujúcich objektov. Tie často nemožno vytvoriť alebo je ich vytvorenie príliš drahé(spojenie s db, sieťové pripojenie,..). Preto nás autor sprevádza príkladmi legacy kódu z praxe, na ktorom sú vysvetlené techniky, ako rozbiť a minimalizovať závislosti v kóde. 

Každá kapitola je ako keby otázkou vo FAQ, teda dá sa čítať samostatne a je odpoveďou na špecifický problém. V záverečnej časti knihy je samostatný zoznam dôležitých dependency-breaking techník na ktoré sa autor často v texte odkazuje. Tieto techniky sú vysvetlené na konkrétnych príkladoch a doplnené všeobecnými postupmi.  

Celkovo je to kniha pre tých, ktorí sa musia rýchlo zorientovať v novom projekte, programátorov pracujúcich na údržbe softvéru a v neposlednom rade pre každého so záujmom postupne zlepšovať kvalitu svojho či kolegovho kódu.

