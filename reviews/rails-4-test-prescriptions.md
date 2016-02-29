# [Rails 4 Test Prescriptions: Build a Healthy Codebase](http://www.amazon.com/Rails-Test-Prescriptions-Healthy-Codebase/dp/1941222196)

## @jsuchal

**TL;DR Great overview of Ruby on Rails testing ecosystem, not so great if you actually want to learn testing.**

Rails 4 Test Prescriptions is a well written book about the current state of Ruby/Rails testing. If you are new to Rails/Ruby testing world, this book is invaluable. You will find everything you need to test you code from every angle. Testing models, controllers, helpers, views, frameworks... it's all there. However if you are looking for a great intro into TDD/BDD I would recommend you look up classics by Kent Beck: Test Driven Development by Example or if you want to get more advanced grab a copy of Growing Object Oriented Software Guided by Tests by Nat Pryce and Steve Freeman. These are Java books, but game-changing reads.

## @borisburdiliak

**TL;DR Very thorough exploration of testing ecosystem of Rails applications.**

"Rails 4 Test Prescriptions - Build a Healthy Codebase" is a very **thorough exploration of testing ecosystem** of Rails applications. The author **builds a proper (TDD) mindset** of readers incrementally and very carefully. He walks them through testing of **models**, **views**, **controllers**, creating **fixtures/factories**, **mocking** principle, **integration testing**, testing of **external services via VCR** and even testing of **javascrips**. All this with proper clarification of perfect **environment setup including tools** (and testing principles) to shorten your tests' response loop. Used examples are clear, author's explanation is concise, **straight to the point** without any clutter you can find in many IT books so often. All the chapters are intertwined with small prescriptions which point out significant messages of appropriate parts of the book. 
From the point of view of teaching fundamentals of writing tests, author introduces five criteria of good ones - SWIFT for Straightforward, Well defined, Independent, Fast and Truthful. As the length of this chapter is too short, it seems a beginner in testing has to extract theoretical concepts out of (well described) examples. I assume it was out of scope of this book to explicitly teach such concepts (Law of Demeter, SOLID, etc.). On the other hand, what I really **missed** is elaboration on **Value Objects** and **preservation of immutability** in the world of Ruby/Rails. 
The author mentions more options how to tackle appropriate problem quite often, following with explanations of pros/cons of each of them. He is a true expert in this domain and shares his tips and pinpoints pitfalls wherever possible.

## @martinliptak

If your are a beginner developer, you should definitely read this book. It will give you enough motivation to start testing (if you are not), introduce you into TDD and explain principles that make good tests. It covers basic tools like RSpec, Capybara, factories and test doubles. All of this is explained on a project-management application developed throughout the book. More advanced developers may still find a few chapters filling in gaps in their knowledge like unit-testing javascript or author's tips on debugging, running tests faster and testing legacy code. The world of testing is full of contrasting opinions and there is often no right answer (google "Unit-test Rails controllers?" or "Mock out ActiveRecord models?"). What I appreciate is that the author not only provided his opinions, but also mentioned the opposite ones describing trade-offs involved. I didn't find all the answers I was looking for, but they probably don't exist either and I have to find the best solutions for each project myself.
