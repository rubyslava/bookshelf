[Domain-Driven Design: Tackling Complexity in the Heart of Software](http://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)
===========================================================================================================================================================

@jsuchal
--------

**TL;DR Dlhé a náročné čítanie, určite stojí za to.**

Ak kniha o vývoji softvéru stojí po 10 rokoch od vydania ešte stále okolo $50 a predslov napísal Martin Fowler, je jasné,
 že pôjde o klasiku.

Eric Evans píše o tom ako modelovať komplexnú doménovú logiku, niečom čo je v dnešnom svete rýchlych startupov
 a frameworkov, kde sa robia TODO listy do 10 minút, už takmer zabudnuté. Pre softvér, čo má byť použiteľný,
 pochopiteľný a rozšíriteľný dlhšie ako polčas rozpadu startupu je to nevyhnutnosťou. No tak k veci:

Kniha je fakt náročné a dlhé čítanie. 560 strán hutných informácií. Ja som to dal až na druhý krát. Možno som to prvý
 krát čítal rýchlo (alebo prosto nepochopil), no druhý krát to už doklaplo. Hlavnou pointov knihy je, že model domény by
 mal čo najvernejšie odrážať realitu. Od názvu tried, metód či parametrov až po moduly a architektúry. (Tím, čo teraz
 cuká kútikom úst, že dobré ráno stará mama, kusnite si do pery a vydržte.)

Eric navrhuje, aby samotná diskusia medzi doménovým expertom (alebo zákazníkom) a programátorom prebiehala v spoločne
 ujednotenom jazyku, ktorý obsahuje slová, ktoré presne zodpovedajú artefaktom (triedam, metódam...) v naprogramovanom
 softvérovom modeli. Programátor je tak nepriamo nútený oddeliť doménovú logiku od infraštruktúry, kedže doménový expert
 hlúpostiam ako singleton, databáza, select alebo polymorfia nerozumie a nepotrebuje rozumieť. Výsledkom je čistá
 doménová vstva, ktorá odráža realitu, a akonáhle nový programátor pochopí ju, bude môcť diskutovať s doménovým expertom
 v rovnakom jazyku. Refaktoringom tejto vrstvy však získavame niečo ovela cennejšie, hlbší a krajší model samotnej
 domény, ktorú modelujeme. Nie je to však pravidlom, no v knihe je zopár ukážok, síce zjednodušených, ale vychádzajúcich
 z reálnych projektov, kde autor pôsobil.

Druhá časť knihy je niečo pre milovníkov kódu ako ja, popisuje konkrétne typy objektov, ktorými modelovať doménu
 a praktické typy ako organizovať moduly a čo vlastne kam patrí.

Tretia časť knihy ide vyššie a ukazuje ako pristupovať k refaktoringu domény. Nejde však o klasický refaktoring ako
 poznáme napr. od Fowlera (vyňatie triedy, ...), toto je niečo o 2 úrovne abstrakcie vyššie. Skvelé žrádlo.

Štvrtá časť ide ešte vyššie a rieši vzory architektúr projektov ako takých. Toto však bolo na mňa už trochu mlátenie
 slamy naprázdno, ale aspoň viem, aké majú tie vzory mená.

Mám však dve veľké výhrady, ktoré vychádzajú z predpokladu, že doménový expert je niekto o čo sa dá oprieť a extrahovať
 jeho znalosti domény, ktoré sa pretavia do krásneho softvérového doménového modelu.

1. Moja skúsenosť je taká, že zákazník (a to je väčšinou doménový expert) niekedy absolútne netuší čo chce a jeho  znalosť domény dobehnem (a predbehnem) hneď po zopár rozhovoroch. Je možné, že nerobím v nejako extra komplexnýchdoménach, uznávam.
2. Ak robím novú vec kde experimentujem, tak doménového experta jednoducho nemám. Čo s tým?

Suma sumárum: Vačšina knihy určite stojí za prečítanie, ale je to naozaj náročné čítanie. Jednak štýlom písania, ktorý mne úplne nesadol a dvak množstvom nových abstrakcií.

PS. Skrátená verzia knihy (od iných autorov) je síce free (http://www.infoq.com/minibooks/domain-driven-design-quickly), ale kvalitou je silne pod úrovňou originálu od Evana. Neodporúčam.