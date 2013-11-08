[Nathan Marz and James Warren: Big Data - Principles and best practices of scalable realtime data systems] (http://www.manning.com/marz/)
=========================================================================================================================================

@vladozc
--------

**TL;DR Pre tych, ktorym nestaci precitanie dvoch tutorialov k NoSQL databazam, ale chcu vidiet pod kapotu.**

Tato knizka pojednava o problemoch, pri ktorych je vyhodnejsie uchovavat data v NoSQL databaze namiesto relacnej. Jej cielom je opisat mechanizmus tychto databaz, nie konkretnu implementaciu. Je vhodna aj pre citatela, ktory zatial nema prakticke skusenosti s NoSQL (moj pripad).

V prvej kapitole je nastoleny vzorovy problem. Nasledne je nacrtnute riesenie za pouzitia relacnych aj NoSQL databaz. Asi nemusim zdoraznovat, ze problem bol zamerne zvoleny tak, aby "zvitazili" NoSQL :) Kazdopadne tento uvod je skvelou motivaciou preco data neukladat v relacnych tabulkach. Teda aspon v urcitych pripadoch.

Zvysok knihy sa uz vacsinou venuje len vytvoreniu jednoduchej aplikacie SuperWebAnalytics.com — obdoba Google Analytics. Na tomto priklade je opisana cela Lambda architektura a jednotlive kapitoly sa venuju tvorbe jej vrstiev. Vsetky priklady su v Jave. Prekvapilo ma, ze autor chcel knihu ponat vseobecne (nie pre konkretnu databazu), avsak pouziva na to konkretne technologie - Hadoop, Pail, Thrift, ... Neznalost tychto nastrojov moze sposobit mensie komplikacie pri snahe o pochopenie kodu.

Celkovo si myslim, ze zatial ide o dobru knihu. Niektore kapitoly isli podla mojho nazoru prilis do hlbky (HDFS + Pail), ale vacsina informacii je uzitocna. Aspon pre niekoho, kto zatial pozna NoSQL databazy len okrajovo.

Zatial je napisana iba priblizne prva polovica knihy. Recenziu doplnim po vydani zvysnych kapitol.

