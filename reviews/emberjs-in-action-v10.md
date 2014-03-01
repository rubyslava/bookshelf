# Ember.js in Action MEAP v10

## @m1k3

**Disclaimer: This review is done on the unfinished v10 of the book. It
may change if the final version changes significantly.**

**TL;DR Not very well written, but still worth a read since this is the
only contender in the space.**

The author does not admit this directly, but he must be a heavy
enterprise framwework liking person. Reading this book is just like
reading code written in any of the heavyweight frameworks Java people
like to use. Boilerplate commentary where you skim-read most of it, but
you have to stop and re-read the interesting parts. The code samples are
much the same story filled with unnecessary details and the commentary
discusses them instead of glancing over them. Granted the book has 'in
action' in the title so showing a live working example is fine. Leaving
completely irrelevant implementation details in (e.g. chapter 10 about
backburner.js controller setup code with the google analytics setup code
left in) is not.

On multiple ocasions there are waisted opportunities for showing off the
framework, best practices etc. and instead the focus is on building
clumsy solutions that cannot be used if you deviate from the tools the
author has chosen. The interesting parts are the ones where the author
shows off the framework. These can be found in part one where the
framework is examined in detail. The other two parts feel like filler
and should be skim-read at best, skipped at worst.

Even though the book is not very well written, I would still recommend
skim-reading it. It covers a lot of ground and is more homogenous than
trying to learn all the concepts from blog posts and other sources.

### Part 1

This is the part you want to read. The first chapter goes over the
Ember.js framework and explains the real MVC pattern (not the bastard
we've become used to on the server over the yeard) and builds a simple
app in the process. The other chapters (2-4) in this part go into depth
on various parts of the framework and are well worth reading.

### Part 2

You only want to read chapters 5 and 7 of this part. Chapter 5 goes over
ember-data and how to use it in an application. Chapter 7 goes over
custom components and how they can be used to share code between
applications.

The other chapters in this part can be skipped as they are only
marginally about the framework.  Chapter 6 builds a poormans data layer
even and upon reading this chapter you'll be wondering why the author
went to such trouble and didn't just use ember-data. Chapter 8 is on
testing, but there is very little on testing Ember.js specifics and a
lot on the tools to do the testing (QUnit and phantom.js). It spends a
lot of time building a testing harness which is useless if you decide
you want to use different tools for testing.

### Part 3

The only interesting chapter is chapter 10 which goes into how the guts
of Ember.js work and how not to get tripped up on them. Chapters 9 and
11 can be skipped. Chapter 9 goes over setting up an authentication
system with a third party provider and chapter 11 goes over packaging
the app with Grunt.js. Both chapters do this in a way that is too
coupled to the example and using the advice in any other setting is
problematic at best.
