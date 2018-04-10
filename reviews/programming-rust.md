# [Programming Rust](http://shop.oreilly.com/product/0636920040385.do)

## @yanchith

**TL;DR I completely recommend this book to anyone interested in the Rust
programming language or wishing to learn about systems programming in general.
The target audience is both mid-level engineers and experts**

Rust is not an easy language to learn for multiple reasons. One part of the
difficulties stems from the fact that it is a systems programming language.
When learning Rust, people unfamiliar with systems programming have to learn
those concepts as well (which was my case). Rust also has a compiler enforcing
very strict ownership semantics (it aims to move most undefined-behaviour-causing
programmer errors to the compile time) and a rich type system (trait
based generics, blanket impls), which contribute significantly to the learning curve.
To round it off, there are not enough learning resources covering all this.
In 2015, when I was first trying to learn Rust, I could not wrap my head
around the its generics system. This book would certainly be of great value to
me back then.

The book makes only some assumptions regarding its readers, mostly that Rust is not
their first language. It does not assume any experience with systems programming,
however, and explains those concepts (stack vs heap, pointers, references,
memory alignment) sufficiently. The first six or so chapters of the book proceed
in a linear order, building the reader's basic understanding of what is possible
in Rust. Afterwards the book branches out - each chapter covers a specific topic
in the language or standard library, and usually has no prerequisites for reading
other than the first six chapters. The chapters of most importance to me were:

- *Error Handling* (I totally agree with the emphasis on this chapter in the book)
- *Crates and Modules*, to be able to properly structure applications and libraries
- *Traits and Generics*, as these are very powerful, with many existing abstractions
are built on top
- *Closures* describes the differences between Rust's and other languages' closures
- *Concurrency* being one of the main selling points of Rust, this book explains
three most dominant approaches to concurrency and synchronization (fork-join,
channels, shared state)

The one thing I would like to highlight in the book's approach to teaching is,
that it does not oversimplify. All concepts are taught very thoroughly, as
deeper understanding is usually crucial when people reach for tools like C++
or Rust.

Overall, I find the book relevant. It imparts understanding of the core
language concepts, which will not change even with many new language/library features
in Rust's pipeline stabilizing soon. While I read it a Rust beginner, I believe
it would also be helpful for more experienced Rust engineers, both as a reference
and a guide.