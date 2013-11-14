[Michal Fogus and Chris Houser: The Joy of Clojure - Second Edition] (http://www.manning.com/fogus2/)
=====================================================================================================

@janherich
----------

Authors of the book 'The Joy of Clojure - Second Edition' had really difficult task. In their second book about Clojure, they try to explain
new concepts which appeared in the Clojure programming language since the first edition of 'The Joy of Clojure' was written, and at the same
time, they try to write this new book in a such way, that it's approachable even for total Clojure newcomers.

I already work with with Clojure for some time (i programm almost exclusively in Clojure for 2 years), so it will be difficult for me to judge
the book from the total beginner's point of view, but i will try to do my best.

I found the book start little bit inconsistent (but remember that i only red the working draft), after quite nice introductory explanation, the
authors got little bit stuck when explaining the differences between infix and prefix notations, they present a function which will convert
operators and operands from one notation to another, it's immediately noted that it's only toy implementation working only for up to three
arguments and a link to repo with fully blown implementation is mentioned in a footnote. I understand the purpose of this excercise, but i still
think that the implementation of shifting function could be ommited because the total newcomers could be confused and maybe even little bit scared
- some less enlightened ones would probably think: "Oh, so i will need to write argument shifting functions in Clojure and it's even not trivial ?"
Because remember, that's the first Clojure code in the book that the readers will encounter.

But after particular point, the book is simply blast to read, very well written, the philosophy of Clojure core and contrib libraries is explained
very well and this explanation is interleaved with many practical code examples. I want to specially highlight the chapter 'Why Clojure isn't especially object-oriented'
i recommend to read this part for every OO programmer who is concerned about what he/she may lost if started using Clojure.

Because the book authors are so talented in the field of topics explanation, even seasoned Clojure veterans could find valuable informations and
insights in this book. In my case, it was the chapter about parallelism, more specific the part about reducers, this concept was not entirely clear
to me, but after reading the well written explanation, i was enlightened and i realized that the concept of reducible collections is genial and
trivial at the same time.

Summary: this book is definitely worth reading, Clojure newcomers shouldn't be scared by the beginning, the rest of the book is amazing.
