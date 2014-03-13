[Kent Beck's Guide to Better Smalltalk: A Sorted Collection](http://www.amazon.com/Kent-Becks-Guide-Better-Smalltalk/dp/0521644372?tag=rubyslava-20)
============================================

@jsuchal
--------

**TL;DR Excelent resource about the roots and core of good OO programming style.**

Why on earth would you want to read an old book about a programming language nobody seems to use today? 

1. Smalltalk was the ligua franca for OO pioneers when OO and design patterns started. 
2. Ruby (the language I use the most and like) was inspired by Smalltalk.
3. With the rise of functional programming right now, we really should look back and see why people switched from LISP to Smalltalk in the first place. Let's not repeat history.
4. Kent Beck is a recognized authority (e.g. pioneer of test driven development, design patterns...) and one of my favorite authors.

This book is a collection of academic articles published during '90s in various sources, but mostly from The Smalltalk Report and OOPSLA Proceedings.

Smalltalk syntax is extremely minimalistic and even though it's not explained anywhere in the book you will have no problem understanding it after a couple of minutes. If you use Ruby, you will actually feel little embarassed once you find out how much it copies Smalltalk. Sometimes one would like to scream "Ruby! You Smalltalk rip-off." That said Smalltalk is very different from languages you probably use today. It's purely object-oriented and has no syntax for primitive constructs that you probably use every day (if, case, while, for). These limitation somehow force you to think more on a proper OO way a.k.a. by sending messages and using blocks. The book contains multiple articles that show you how to think about your program in an OO way, how to start designing a system and find objects (from variables, methods, state), what are bad smells and how to fix them. Most of these advice comes from fixing real world projects that Kent Beck was working on during that time, others are purely academic exercises. I liked both. Make no mistake this book is not your weekly shallow refactoring screencast, it goes really deep and controversial at places you wouldn't expect.

I highly recommend this to anyone who wants to learn about how great OO design is done. You can skip the parts about various problems in Smalltalk implementations at those times though, they are problably not so relevant to you now.
