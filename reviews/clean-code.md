[Clean Code: A Handbook of Agile Software Craftsmanship](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882?tag=rubyslava-20)
=========================================================================================================================================

@jsuchal
--------

**TL;DR Nuda, podpriemer a zbytocny fetis. Neodporucam.**

Prvych 190 stran je totalna nuda, zaspaval som. V podstate rozvlacne rozpravanie o bad smelloch v kode, ktore su ovela
 lepsie popisane v knihe Refactoring, Fowler. Navyse miestami az fanaticky rozprava detailoch vyvoja SW, ktore este nikto
 rigorozne nedokazal. Viac na tuto temu v dlhej ale perfektnej prezentacii "Greg Wilson - What We Actually Know About
 Software Development, and Why We Believe It's True" http://vimeo.com/9270320

Kapitola o konkurencii/vlaknach je tam len tak prilepena a netusim vlastne naco, kedze nikde sa na to potom neodvolava
 + dalsi appendix o konkurencii je tam totalne zbytocny.

Kapitoly 14, 15, 16 - ukazky refaktoringu realnych kodov. Strašne tazkopadne sledovat zmeny v kode aj ked su zvyraznene.
 Obavam sa, ze na toto je kniha fakt zle medium a 1000x lepsi polhodinovy screencast. Ale clovek ma zase dobry pocit,
 ked cita rychlostou 100 stran za hodinu, kedze sa tam cele strany kodu opakuju len kvoli premenovaniu metody a extract
 method.

Vybrane priklady na refaktoring mi pridu ako strasne jednoduche veci, kde nie su takmer ziadne interakcie s inymi
 objektami a cele to jeho refaktorovanie je v drvivej vacsine len premenovavanie metod/tried a premennych. Sem tam
 nejaky extract method a class. Vysledny kod je sice pekny, ale niekedy mi to prislo az ako fetis, bez stipky pragmatizmu.
 Na to, ze pol knihy basni o pravom TDD a emergencii dizajnu, tak to robi presne naopak. Naprv ukazuje kod a potom testy.
 Divne.

Navyse ukazka parsera na argumenty z konzoloveho riadku je podla mna nedotiahnuta a porusuje Open-Closed Principle kedze,
 aby mohol pridat novy typ parametra, nestaci pridat triedu, ale treba sahat na 3 miesta v triede. Ale trochu upodozrievam
 Javu a jej typovy system, ze to je takto posrate.

V podstate jedine co stoji za zmienku je kapitola 17 - co je vlastne zhutneny prehlad bad smellov, ale tak, to uz urobil
aj Fowler v knihe Refactoring davno pred nim.

Suma sumarum, neodporucam.