[Use The Index, Luke! A Guide to SQL Performance](http://j.mp/HsprUO)
=====================================================================

@jsuchal
--------

**TLDR; Povinné čítanie pre každého databázistu, odporúčam.**

Pre tradičného zástancu relačných databáz ako ja určite jeden z najlepších verejne dostupných zdrojov o optimalizácii SQL dopytov pomocou správneho indexovania. Doplnené fajn obrázkami a niekedy dokonca animáciami.

Od úplných základov ako:
- Ako vyzerá teda ten index? Čo je to zložený index?
- Kedy sa index použije a kedy nie?
- Tri rôzne typy joinov (nie left, inner, outer) ale algoritmy (hash join, nested loop join a sort-merge join)

Cez pokročilejšie použitie:
- covering index
- function based index
- partial index
- bitmapové indexy
- optimalizácia order by a group by pomocou zložených indexov
- optimalizácia top-k (limit) dopytov

Až po pikošky ako:
- zmiešané smery usporiadania v zložených indexoch a poradie NULL
- Kedy je prepared statement nevýhodný
- čo sú index-ordered tables

Dá sa to prečítať celé na jeden šup. Odteraz to považujem za základnú povinnú literatúru každého databázistu. Resp. aj nedatabázisti by sa čo-to naučili.

*PS. Kto po prečítaní siahne ešte po MySQL musí mať sakra dobrý dôvod alebo je čistý blázon.*