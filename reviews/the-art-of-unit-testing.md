[The Art of Unit Testing](http://www.manning.com/osherove/)
============================================
**[@mcsdodo](https://twitter.com/mcsdodo)**
-----------
>"The book is for anyone who writes code and is interested in learning best practices for unit testing" 

Kniha je logicky rozdelena na 3 celky (okrem uvodu) - zakladne pojmy/metody unit-testingu, organizacia testovacieho kodu a 
nakoniec nieco o designe a procesoch v testovani. Ako autor viac krat spomina, tato kniha je urcena pre ludi, ktori sa chcu naucit best-practices pre pisanie unit-testov. Neuci design, neuci OOP a neuci ani TDD, aj ked pri vyklade sa opiera o OO principy, v podstate sa odkazuje na ine knihy ak ma citatel zaujem o detaily. Odporuca postup krok za krokom, najpr si osvojit zaklady testovania, potom OO navrh a TDD (kniha _Growing Object-Oriented Software, Guided by Tests_).

Priklady v knihe su pisane v C#. Pre programatorov v dynamickych jazykoch, kde mozme vymenit hocico pocas runtime sa niektore postupy mozu zdat trochu overkill (virtual-by-default, interface-based design, DI) ale pre testovatelny kod sa tomu v statickych jazykoch nevyhneme, inde minimalne zjednodusi pisanie a citatelnost testov.
  
Zo zaciatku popisuje co to vlastne unit-testy su, vysvetluje koncept mockov a stubov, priklady izolacnych frameworkov pre .NET ale aj Javu a potom trochu detailnejsi pohlad na jednotlive frameworky, ktory ma velmi nezaujal. Zaujimava je 8 kapitola - __The pillars of good unit tests__. Jasne a prehladne opisuje atributy dobrych unit testov, naming konvencie, ako udrzat prehladnost.

Najviac ma vsak zaujala posledna cast __Design and process__ kde popisuje postupy ako zaviest unit-testovanie do organizacie, ako testovat legacy-code a ako argumentovat pouzitie TDD pripadne testovania vobec manazerom. Nakoniec tiez kapitola __Design and testability__ kde diskutuje vyznam design-for-testability a vseobecna napoveda, ako manazovat kod statickych jazykov pre testovatelnost.

__Zhrnutie__: odpocucam kazdemu, kto chce zacat testovat svoj kod, kto chce najst nove argumenty pre skeptikov vo firme, kto si chce rozsirit obzory alebo oprasit vedomosti ziskane z 1000 online zdrojov.

A citat z knihy nakoniec: 
>"A good bottle of vodka never hurts when dealing with legacy code"
