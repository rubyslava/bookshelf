# [Building Microservices:Designing fine-grained systems](http://www.amazon.com/Building-Microservices-Sam-Newman/dp/1491950358?tag=rubyslava-20)

## @tomaj

**TL;DR I have to recommend this book for everyone who is interested in this microservices "pattern". If you are consider to split monolithic application it is a must read.**

I started reading this book when I was in a team and we were in a process of splitting a few big monolithic applications into various small applications. These applications are written in different technologies and frameworks. 
We thought that we were doing microservices but we created more service oriented architecture than microservices (based on information from book). Definition of a microservice is very tricky and hard to define. Also author of book ([Sam Newman](https://twitter.com/samnewman)) took some time to define it. One citation from book: *Microservice is something that could be rewritten in two weeks*.

Microservices are on hype these days and everybody is trying to go this way with projects. This book is a very good guide for everyone who wants to start with microservices (by splitting monolithic application or starting new one from scratch). Author is trying to put some facts on the table about how you can benefit from microservices architecture but for me more interesting were parts about disadvantages of microservices and what you can do wrong. You can end up with smaller apps but each update requires updating more than one service and it is very hard to maintain it. So you have invested a lot of time to split and decouple application modules but in end of the day the maintenance of this applications could be a nightmare.

Book is very good structured. I read it from the beginning to the end and it makes perfect sence for me to read it in this way. Maybe if you are familiar with microservices and you have done some projects this way you can read only chapters you are interested in.
Author starts with basic problems with monolithic application (use example of Music Shop) and tries to explain how it is possible to split this application into smaller apps. Basically all the time in the book HTTP JSON REST api is winner (or some kind of shared event managers). Only in special cases where you need extra performance you will need something else.

Book contains chapters about testing and deploying microservices. Which patterns and test types are good or not (integration test usually sucks). Testing in microservices enviroment is a hard stuff (and this chapter is really long). There are plenty of cases that you need to consider and also in deploying. You need to know how to deploy breaking changes to your microservices if you will deploy all services together or every service will have own release cycle. Book contains also chapters with real patterns and use cases for monitoring, scaling and securing services.

Few small higlights/facts (for me):
 - Book is new. All links, technologies are up to date right now. (docker, Consul...)
 - If you need client library for your app (some api wrapper in your language) - good pattern is to create this library by other person than who wrote api.
 - Really good book for start in thinking about microservices and real use cases how to do it or not.
