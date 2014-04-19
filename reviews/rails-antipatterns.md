# Rails Antipatterns - Best Practice Ruby on Rails Refactoring

## @m1k3

**TL;DR Good read for any intermediate Ruby on Rails developer.**

I've originally read this book shortly after it came out in 2011. I was
reminded of it recently when discussing a solution (I recalled reading in
this book about) and decided to write a review.

The concept of presenting ideas via antipatterns should be fairly well
known in the programming community. And for good reason. It works and
its very effective. By focusing on practical issues the authors saw in
codebases and presenting actual solutions that you can apply in your
code today they created a good library of solutions to problems that
plague Rails codebases to this day. To top it all off most (if not all)
of the advice is still relevant even though the book was written in the
Rails 3 days.

Some time has passed from the publish date and time wasn't kind to some
of the overly specific advice (recommending concrete gems, listing code
samples specific to a version of rails etc.). When skimmed, these
passages don't distract too much from the good points the book makes.
Overall the book is a must-read for any intermediate Ruby on Rails
developer. Seasoned developers won't see as much benefit from reading
it, but can still pick up a trick here and there.

The book is divided into chapers creating logical blocks of
antipatterns and solutions:

### 1 Models

This is probably the most interesting part of the book. The chapter
deals with the model layer and lists tips and tricks to make code there
as expressive and readable as possible. Almost everything mentioned in
it is best practice to this day.

### 2. Domain modeling

The chapter lists some good advice to think about when modelling data.
E.g. maybe you don't need to have a full-blown Roles model to store roles on a
User model. Maybe you do, but always think about [YAGNI](http://en.wikipedia.org/wiki/You_aren't_gonna_need_it).

### 3. Views

Provides some good ideas for working with Rails views. Some of the ideas
are controversial, but you need to be a seasonsed developer to appreciate
the nuances. E.g. The chapter goes on suggesting you use HAML as your
templating language. While I agree with the suggestion I know many
people don't so keep that in mind when reading it.

### 4. Controllers

The chapter starts by suggesting some older gems as examples of not
reinventing the wheel when doing authorization. Other than that all of
the tips there are relevant for current apps.

### 5. Services

This is a chapter about good programming practices in general. Seasoned
developers can skim so that they don't grinn to much when reading they
should use a gem to parse out HTML. Others should pay close attention.

### 6. Third-Party code

This is one of those chapters that you can skip entirely when you know
how to select a proper gem when building an app, but is indispensable
when you don't.

### 7. Testing

Some good ideas on testing, but there are much better books written on
the topic. The gems listed (e.g. FactoryGirl) is an excelent solution to
the fixture problem even today.

### 8 Scaling and Deploying

Some general tips on not making silly mistakes like forgetting SQL
indexes and doing things in the database rather than loading up
thousands of objects in memory and doing computations on them.

### 9. Databases

Very good practices when using database migrations and on validations
and the fact that as much of them as possible should be handled by the
database.

### 10. Build for failure

Again nothing new to seasoned developers, but nicely formulated examples
on why you need to be carefull and not have corrupted data as a result
of an exception and that your exceptions should fail loudly so that you
can do something about the problem.
