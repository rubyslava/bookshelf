[Kent Beck: Smalltalk Best Practice Patterns](http://www.amazon.com/gp/product/013476904X)
==========================================================================================

@jsuchal
--------

**TL;DR Zásady kvalitného programovania od otcov objektovo orientovaného programovania. Dobré a rýchle čítanie.**

Prečo čítať knihu z roku 1996 o programovacom jazyku, ktorý dnes už málokto pozná alebo nebodaj používa?
Kedže programujem už dosť dlho v Ruby, ktoré bolo inšpirované najmä Smalltalkom, jazykom od otcov pravého objektového programovania, povedal som si, že pozriem po zdrojoch ako to vlastne naozaj s tým OO mysleli. Ak je to navyše ako bonus od jedného z top autorov Kenta Becka.

Túto knihu Kent napísal dávno pred Fowlerovým Refactoringom, Evanovým Domain Driven Design alebo aj svojím Test Driven Development by Example, napriek tomu tam vidím presahy a silné inšpirácie.

Kniha je vo svojej podstate zbierkou tipov a pravidiel štábnej kultúry, ktoré by mali programátori používať a dodržiavať. On ich volá vzory, ale nie všetko sú to vzory v zmysle ako sa chápu dnes. Napríklad sú tam aj "vzory" ako nazvať premenné a metódy. Väčšina vzorov je však nezávislá na programovacom jazyku (tu Smalltalk) a diskusia okolo nich má hlbší kontext. Napríklad "It is much preferable to give an object more responsibility rather than have it act like a data structure." Čiže skôr ako by začal s getter/setter peklom by porušil SRP, zaujímavé.

Samotné ukážky kódu sú v Smalltalku a aj keď som v ňom v podstate nič v živote nespravil, tak syntax som chytil za pár minút. V kapitole o kolekciách som pochopil odkial má Ruby bloky, názvy metód a všeličo ďalšie. Smalltalk dokonca nemá if (ako klúčové slovo) ani switch. Vynucuje to blokmi a polymorfiou, krásny minimalizmus. Človek má hneď chuť si v tom niečo skúsiť.

Na konci knihy je ukážkový príklad kódu, ktorý dodržiava "vzory". Tí, čo čítali TDD by Example si určite spomenú na triedu Money.

Suma sumárum: Krátke pohodové čítanie, väčšina "vzorov" je nezávislá na jazyku a stále aktuálna, zopár inšpiratívnych citátov je naozaj na hlbšie zamyslenie. Syntax Smalltalku je stelesnený krásny minimalizmus. Trochu som sklamaný, že tematicky to bolo viac o pomerne mechanických pravidlách ako smerom k dizajnu objektového kódu, ale celkovo dobrý pocit.

PS. Pamätám si ako sme na FIIT mali na OOP urobiť jedno zadanie v Smalltalku/Squeaku. Neviem koho to bol nápad, ale strašne na to všetci študáci nadávali. Keby som sa s dnešnými znalostami mohol vrátiť v čase, urobím v tom všetky zadania a vôbec všetkým študákom by som to dal povinne.

PS2. Ruby + Smalltalk VM = Maglev.