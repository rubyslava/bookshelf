[Growing Object-Oriented Software, Guided by Tests](http://www.amazon.com/Growing-Object-Oriented-Software-Guided-Tests/dp/0321503627?tag=rubyslava-20)
===============================

@smolnar
------

**TL;DR Must-read for every developer.**

At the beginning of a book, authors provide an inside into theoretical fundamentals of testing and object-oriented design as well. Since they only intended to provide an inside, principles of object-oriented design are not covered in depth, but rather serve as a reference for further reading. As a developer who tries to apply TDD as much as possible, I equated with most of ideas and design authors proposed as a introduction to test-driven development, but I think that a developer who just discovers fundamentals and benefits of TDD might find hard to perceive all principles of unit and acceptance testing at the beginning. 

After brief introduction, authors dive right into developing a working example for testing. The application is written in Java and provides watching and bidding on auctions. Since the application design is driven by client-server design, the communication is performed via XMPP protocol, which, in my opinion, is a good example to demonstrate capabilities of TDD by mocking objects for network responses. Another interesting note worth mentioning is when the authors point out that a first setup of application takes always more time than we expect.

As authors progress and refactor the application throughout the book to apply principles proposed in first chapters, design of their test-driven approach is very clear - use of mock objects along with end-to-end tests. Authors' object-oriented design is present in every example - e.g. heavy utilization of interfaces. But from most part, I appreciated how authors discussed the application design step by step and reflected on various viewpoints for testing.

To sum up, the most interesting parts for me were the beginning chapters of the book. Before I jump right into theory of TDD, I learned by example by reading bunch of blogs and tutorials for Rspec. In my opinion, it was not such a bad approach, since it helped me to embrace domain design for tests and overall, understand how to write tests in order to make them as descriptive as it gets. After reading first chapters and theoretical fundamentals to TDD, I organized my thoughts on acceptance testing and look more closely to fundamental reason for TDD.
