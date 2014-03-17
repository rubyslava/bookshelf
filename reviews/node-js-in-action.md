[Node.js in Action](http://www.manning.com/cantelon/)
=================

@markoph
--------

_[English review below](#nodejs-in-action---english-review)._

TLDR
----

Kniha je skvelým úvodom do sveta Node.js pre úplných začiatočníkov aj pre developerov so základmi Node.js, ktorí sa chcú posunúť k frameworkom Connect a Express. Vysvetlené sú nevyhnutné základy asynchrónneho a udalosťami riadeného programovania spolu s callbackmi, udalosťami a kanálmi. Kniha ukazuje silné stránky platformy ako serverového riešenia, pri implementácií klienta pomocou najpoužívanejších frameworkov aj pri vývoji aplikácie pre príkazový riadok. V prílohe autori prevedú čitateľa skrz inštaláciu, testovanie a debugovanie platformy Node.js. Spolu s úvodom do platformy na začiatku a pokročilým technikám na konci, je túto knihu možné považovať za **All in One Node.js pre začiatočníkov**.


Úvod
----

Akýkoľvek skepticizmus či výhovorky, prečo sa do Node.js nepúšťať, som po druhej kapitole knihy mohol zahodiť za hlavu. Pred sebou som mal totiž funkčnú chat aplikáciu. Niekto by mohol nesúhlasiť a sťažovať sa na to, že takto zložitá aplikácia hneď v úvode knihy je zbytočným rozptyľovaním a zneisťovaním, pretože čitateľ ešte dostatočne nerozumie kódu. A áno, pár častí v danom momente ostávalo záhadou, ale každý vývojar, ktorý vyvíjal modernú webovú aplikáciu a aspoň trochu pozná ako javascript funguje, musel pochopiť základy tohto kódu _(ak nespĺňate podmienku "aspoň trochu pozná javascript", nepúšťal by som sa do tejto knihy)_. A ak nič iné, čitateľ ihneď na začiatku vidí ako môže Node.js znateľne urýchliť vývoj backendu a priamo ho napojiť na frontend.

V prílohe sa nachádza skvelý návod ako nainštalovať Node.js _(podrobne vysvetlené pre Windows, Linux aj OS X)_, odporúčam sa tam zastaviť pred budovaním chat aplikácie.

Kniha začína vysvetlením, čo presne si má čitateľ predstavovať pod asynchronná a udalosťami riadená platforma. V čom sú výhody asynchrónneho servera, ako asynchrónne pracuje browser, sériové a paralelné spracovanie taskov a ďalšie **low-level detaily, ktoré človek potrebuje pochopiť, aby mohol budovať kvalitnú a rýchlu aplikáciu v Node.js**. Túto časť **odporúčam začiatočníkom nepreskakovať**, v prípade potreby prečítať aj viac krát.

Hneď v úvode **musím pochváliť prácu s code snippetmi**. V knihe je zvládnutá na jedničku. Zložitejší kód je rozdelený na viacero častí a podrobne vysvetlený. Po stranách kódu sú krátke popisy k jednotlivým zápisom, s ktorými sa čitateľ ešte nestretol, alebo sú na toľko pozmenené, že je potrebné ich vysvetliť.

Ďalším krokom v základoch Node.js sú moduly. Ako ich sťahovať a inštalovať, používať vo svojich aplikáciach, ako sa rýchlo dostať k ich dokumentácií a ako vytvárať vlastné moduly. Autori často spomínajú a odkazujú na kvalitné moduly, či už tie použité v príklade alebo alternatívy k ním. **Čitateľ tak získa približný prehľad o najpoužívanejších a najkvalitnejších moduloch.** Tiež sa dozvie aké sú rozdiely medzi spracovaním jednorazových odpovedí pomocou _callbackou_ a udalosťami riadeným kódom za pomoci takzvaných _event listeners_ a ako obe možnosti použiť.


Node.js Core
------------

Po zvládnutí týchto predpokladov, kniha v druhej časti predstavuje čitateľovi low-level základy Node.js. Či už ide o **zasielanie hlavičiek, základnú bezpečnosť aplikácie a zachytávanie chýb**, ktoré by mohli zhodiť server. Čitateľ si postaví REST aplikácie _(pre príkazový riadok)_ a vytvorí **vlastný server**, ktorý posiela klientovi statické súbory. Na konci prvej kapitoly druhej časti sa nachádza aj návod ako zabezpečiť komunikáciu servera s klientom pomocou HTTPS. **Autori sa tu nesnažia predstaviť všetky core moduly, takže ak niekto očakáva technickú príručku, chystá sa na nesprávnu knihu.**

Jedna celá kapitola je venovaná ukladaniu dát pomocou Node.js. Možností je veľa, ale kniha prevedie čitateľa cez ukladanie do RAM _(in-memory)_ či do súborov _(filesystem)_, do relačných databáz _(MySQL a PostgreSQL)_ a nakoniec NoSQL _(Redis a MongoDB spolu s Mongoose - interface pre jednoduchú správu MongoDB)_.

Pri databázach sa na chvíľu pozastavím kvôli dvom poznámkam. Kniha občas obsahuje na môj vkus príliš podrobné informácie. Pravdepodobne preto, že sa snaží cieliť aj na ľudí, ktorí nikdy nevyvýjali backend, na ľudí, ktorí kódovali len v javascripte a neprišli do kontaktu zo databázami. Asi práve preto je v knihe dôkladne vysvetlené, čo je to MySQL, rozdiely medzi MySQL a PostgreSQL či medzi relačnými databázami _(RDMS)_ a NoSQL.

Našťastie som takýchto pasáži neobjavil veľa a aj tých pár sa dá preskočiť. Práve vďaka tomu **ako skvelo je pripravený úvod a záver jednotlivých častí** _(a väčších kapitol)_ knihy. Začínajú sa zoznamom vecí, ktoré budú predstavené v priebehu nasledujúceho textu. Čo je výhodne pre ľudí, ktorí už nejaké znalosti Node.js majú a môžu tak s čistým svedomím tieto časti preskočiť. A **záver** naopak **pomôže nováčikom prejsť si ešte raz, čo všetko by si mali z danej časti odniesť**, aby mohli prejsť do ďalšej časti. Takže v prípade neistoty sa môže k nedostatkom vrátiť.


Connect & Express
-----------------

Ďalšie kapitoly druhej časti knihy sa venujú frameworkom, čo by už mohlo zaujať aj ľudí, ktorí sa s Node.js stretli v jeho rannej fázi a zdalo sa im príliš ťažkopádné. **Framework Connect** či **webový framework Express**, ktorý je vybudovaný nad Connectom, sú tým poriadným mäsitým pokrom **pre rýchly vývoj robustných a kvalitných aplikácií**. Ak vás na začiatku zaujme rýchlosť s akou je v Node.js možné vybudovať jednoduchú chat aplikácia, tak sa môžete tešiť na to, čo dokážete s Connectom a Expressom.

Dve celé kapitoly druhej časti sú venované Connectu, ako ho nastaviť a jeho hlavnej zbrani - **middleware** - akýmsi funkčným komponentom, ktoré sú znovupoužiteľné. Chvíľu som si ich v hlave prirovnával k metódami objektov, bohužiaľ prvá zmienka o sekvenčom naväzovaní jedného middleware na druhý táto myšlienka z hlavy vyfučala. Tieto kapitoly sa im venujú v dostatočnom rozsahu, takže čitateľ určite pochopí o čo ide, ako tieto middleware nasadiť na server a ako používať. Príklady začínajú opäť s jednoduchými záležitosťami ako je logovanie, hello world a prechádzajú k zložitejším ako je napríklad používanie middlewaru **vhost()** na nastavenie a správu virtual hostov _(umožňuje správu viacerých stránok na jednom servery)_ či prácu so **session** _(ktoré tuším ani nie sú v rámci samotného core low-level Node.js pokryté)_.

So znalosťami z predchádzajúcich dvoch kapitol, môže čitateľ prejsť k Expressu, s ktorého pomocou je budovanie webových aplikácií zábava. Po inštalácií a nastaveniach sme prevedení pomocou ukážkovej aplikácie - mini foto galérií, skrz nahrávanie súborov, zobrazovanie pomocou šablonovacieho systému EJS _(postačujúco vysvetleného)_ a v časti pokročilý Express sa pozrieme na autentifikáciu užívateľov, routovanie a vytváranie REST API.

Trochu ma prekvapilo, že ukážky a príklady, ktoré sa ťahajú celou knihou, sú len občas použité znovu. Často ide o technológiu, ktorá nejakým spôsobom vylepšuje niečo, čo sa čitateľ naučil v predchádzajúcich kapitolach. Na tomto by **sme mohli** budovať a s každou ďalšou časťou **vytvárať kvalitnejšiu** _(čo sa týka kódu)_ **a komplexnejšiu** _(čo sa týka funkcionality)_ **aplikáciu**, na ktorej by čitateľ pochopil rozdiely medzi jednotlivými low-level zápismi a použitím frameworku _(ktorý napríklad zložitý viacvrstvový callback zvládne jediným zavolaním middleware)_. Namiesto toho **sme nútení neustále vytvárať nové aplikácie**.

Aj vďaka tomu je občas cítiť, že knihu písalo viacero autorov. Chýba čosi ako kontinuita kódu a budovanej aplikácie.


Záver knihy
-----------

Zvyšné dve kapitoly druhej časti sa venujú **testovaniu** _(Unit testing, Acceptence tests)_ a **šablónovaniu** v Node.js. Neidú zbytočne do hĺbky, ale čitateľ bude mať po prečítaní v oboch sférach dostatočný prehľad aj keď sa so žiadnou z nich nestretol. Som rád, že autori nevynechali testovanie z knihy. Kapitola so šablónami zas poslúži ako akési zhrnutie existujúcich alternatív _(EJS, Mustache, Jade)_, aby si budúci Node.js vývojar vedel vybrať.

Posledná, tretia časť knihy sa venuje Node.js v inom svetle, mimo reflektorov webu a moderných "AJAX"ových klikacích aplikácií. Základy deployovania určite využije každý, kto bude chcieť Node.js použiť v produkcii. Rovnako kapitola o výkone obsahuje pár užitočných trikov ako zvýšiť uptime servera či využiť viacero CPU jadier. Kapitola o Socket.io medziiným obsahuje trik, ktorý určite poteší webdizajnerov pri úpravach stylesheetov _(realtime reload stránky po zmene súboru na servery; mňa teda určite potešil)_.


Sumarizácia
-----------

Ako developer, ktorý nikdy vo veľkom rozsahu nepracoval s javascriptom, som si túto knihu o Node.js veľmi užil. Vďaka nej sa mi Node.js dostalo pod kožu a jej prečítanie odporúčam každému začiatočníkovi, ktorý premýšľa o vývoji v Node.js a taktiež pokročilejším developerom, ktorí sa chcú pozrieť na Connect a Express. Ako som už v úvode napísal, túto knihu môžem s pokojným svedomým označiť ako **All in One Node.js**.


---------

[Node.js in Action](http://www.manning.com/cantelon/) - English review
==================================

@markoph
--------

TLDR
----

This book is great intro into the world of Node.js for the beginners. It will be good guide also for developers working with Node.js but trying to move deeper with Connect and Express frameworks. Explained are necessary basis for asynchronous and event driven programming along with callbacks, events and channels. Book shows strengths of platform for server, client implementation with help of powerful frameworks and for development of command line app. In appendix authors show to reader how to install Node.js, how to debug and test it. Together with the intro into Node from the first part and advanced techniques at the end, this book can be considered as **All in One Node.js for begginers**.


Intro
-----

Any skepticism or excuses not to learn Node.js I had before diving into it, I could leave behind after the second chapter of the book. In front of me I had a functional chat application. Some might disagree and complain that such complex application at the very beginning of the book is unnecessary distraction because reader does not understand a code enough yet. And yes a couple of bits at the moment remained a mystery but every developer who worked on modern web application and is at least a little familiar with how javascript works should understand the basics of this code _(if you do not qualify "at least a little familiar with javascript" I do not recommend this book)_. And if nothing else a reader immediately in the beginning of the book sees how can Node.js noticeably accelerate development of the backend and directly connect it to the frontend.

Book has great manual _(first appendix)_ for Node.js installation _(with details for Windows, Linux and OS X)_, I recommend to install Node.js before starting with a chat application.

First chapters of a book explain everything about asynchronous and event-driven platform. Where are benefits of asynchronous server, how works asynchronous browser, serial and parallel tasks processing and more of **low-level details, which are needed to understand for building high quality and quick applications with Node.js**. **Beginners shouldn't skip this part**, if needed for understanding they actually should read it several times.

Right at the beginning **I must uphold work with code snippets**. More complex parts of code are divided and explained in detail. Along the sides of code are short descriptions for each new or changed line _(or code block)_ with which reader didn't met before.

The next step in the basics are modules. How to download and install them, how to use them in your applications, how to quickly get to their documentation and of course how to create your own modules. Authors are frequently noting and linking to quality modules, whether those used in examples or alternatives. **So reader finds in this book also an overview of the most used and best quality modules.** After code organisation authors explain and show examples of the difference between two models of processing asynchonous response. Processing one-off answers with the help of _the callbacks_ and _the event listeners_ for event-driven logic.


Node.js Core
------------

After mastering these preconditions, the second part of the book presents the reader with the basics of low-level Node.js. Whether it's **sending headers to client, basic security of applications or capturing errors** which could crash server. The reader will build REST application _(for the command line)_ and create **own server**, which will serve static files to the client. At the end of the first chapter of the second part is a guide to secure communication with the client server using HTTPS. **The authors are not trying to introduce all core modules of Node.js, so this is wrong book for anyone who expects a technical guide.**

Entire chapter is devoted to storage used with Node.js. The possibilities are many, but the book goes through few most used. RAM _(in-memory)_ , to files _(filesystem)_, into relational databases _(MySQL and PostgreSQL)_ and finally NoSQL _(Redis and MongoDB with Mongoose - interface for easy management of MongoDB)_.

Here I will stop for a moment with two notes. Book sometimes contains too much detailed information for my taste. I guess it's because they are trying to target also the people from frontend who coded only in Javascript and didn't touched databases. Maybe this is exactly the reason of too much information about MySQL, what it is, how it's different from PostgreSQL and what are differencies between relational databases and NoSQL.

Luckily, I did not discover many such passages, and even those few can be skiped. And that's possibly thanks to **great intro and summary** of the individual parts _(and bigger chapters too)_. Authors start with a list of things presented during next part of book. What is beneficial for people who already have some knowledge of Node.js so they can in good conscience skip those parts. And **summary will help newcomers to go again through all they should take with them** from current part to the rest of the book.


Connect & Express
-----------------

Other chapters of the second part are devoted to frameworks, what could already be of interest to people with basic knowledge of Node.js. **Framework Connect** or **web framework Express**, which is built over Connect, are real meat here **for rapid development of robust and high-quality applications**. If you were amazed how quickly it is possible to build with Node.js simple chat application, you will enjoy what you can do with Connect and Express.

Two entire chapters are devoted to Connect. You learn how to set it up and all about its main weapon - **middleware** - some kind of functional components that are reusable. For a moment I had them in the head imagined as the methods of the object, (un)fortunately until the first mention of sequencing middleware. They devote a middleware a sufficient part so the reader will understand what's going on, how to use it and mount to the server. Examples begin again with simple issues as logging, hello world and are getting more complex with such functionalities as the use of middleware **vhost** _(to set up and manage virtual hosts, which allows you to manage multiple sites on one server)_ or work with **session** _(which I guess is not covered within the core low-level Node.js)_.

With knowledge of the previous two chapters, the reader continue with Express, through which is building web applications fun. After installation and setup, we build sample application - mini photo gallery; from uploading files, viewing through EJS templating system; to an advanced Express for user authentication, routing and creating REST API.

I was little surprised _(and maybe disappointed)_ that examples from all the book are only occasionally used again. Often we are learning new techniques which should improve something we learned before in previous chapters. On this **we could build** and with every piece of knowledge create **superior** _(in terms of code)_ **and more complex** _(in terms of funcionality)_ **application** where reader could understand differencies between the low-level Node.js _(where you need a block of code)_ and Framework driven programming _(where you can use one middleware)_. But this did not happen and **we were pushed to create new applications** all over again.

Also thanks to this I sometimes really felt that the book was written by several authors. The book is missing a kind of continuity of the text and code.


End of book
-----------

The remaining two chapters of the second part are devoted to **testing** _(Unit Testing, Acceptence tests)_ and **templating** in Node.js. They don't go too deeply, but the reader will have in fact a good overview. I am glad that the authors didn't leave out testing part from the book. Chapter about templates serves as a kind of summary of existing alternatives _(EJN, Mustache, Jade)_ so every developer could chose.

Last, the third part of the book is devoted to Node.js in a different light, out off reflectors of modern AJAX clickable applications. Basics of deployment will be to use for everyone who wants to use Node.js in production. Also the chapter about performence includes some useful tricks to increase server's uptime and use multiple CPU cores. The chapter on Socket.io among other things contains a trick that will sure delight web designers editing theirs stylesheets _(realtime reload of the Node.js page after changing the file on server)_.


Summary
-------

As developer who never worked on a large scale with javascript, I really enjoyed this Node.js book. The book got Node.js under my skin. I recommend to read it to every beginner who is thinking about development in Node.js as well as to advanced developer who want to look at Connect and Express frameworks. As I wrote in the beginning for me is this **All in One Node.js** book.