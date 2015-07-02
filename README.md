# Agile-Notes
Notes for agile methodology

Table of Contents
=================

* [The Agile Manifesto](#The Agile Manifesto)
* [Test-driven development](#Test-driven development)
* [Rules Of Simplicity](#Rules Of Simplicity)


##The Agile Manifesto
Manifesto for Agile Software Development 

We are uncovering better ways of developing software by doing it and helping others do it. Through this work we have come to value: 

* **Individuals and interactions** over processes and tools
  * in agile development, self-organization and motivation are important, as are interactions like co-location and pair programming.
* **Working software** over comprehensive documentation
  * working software will be more useful and welcome than just presenting documents to clients in meetings. 
* **Customer collaboration** over contract negotiation
  * requirements cannot be fully collected at the beginning of the software development cycle, therefore continuous customer or stakeholder involvement is very important.
* **Responding to change** over following a plan
  * agile development is focused on quick responses to change and continuous development
That is, while there is value in the items on the right, we value the items on the left more.

The Agile Manifesto is based on twelve principles:

1. Customer satisfaction by rapid delivery of useful software
2. Welcome changing requirements, even late in development 
3. Working software is delivered frequently (weeks rather than months) 
4. Working software is the principal measure of progress 
5. Sustainable development, able to maintain a constant pace 
6. Close, daily cooperation between business people and developers 
7. Face-to-face conversation is the best form of communication (co-location) 
8. Projects are built around motivated individuals, who should be trusted 
9. Continuous attention to technical excellence and good design 
10. Simplicity—the art of maximizing the amount of work not done—is essential 
11. Self-organizing teams 
12. Regular adaptation to changing circumstances

##Test-driven development
"Test-driven development" refers to a style of programming in which three activities are tightly interwoven: coding, testing (in the form of writing unit tests) and design (in the form of refactoring).

It can be succinctly described by the following set of rules: - See more at: http://guide.agilealliance.org/guide/tdd.html#sthash.RAkavwcB.dpuf

* write a "single" unit test describing an aspect of the program
* run the test, which should fail because the program lacks that feature
* write "just enough" code, the simplest possible, to make the test pass
* "refactor" the code until it conforms to the simplicity criteria
* repeat, "accumulating" unit tests over time

###Common Pitfalls
Typical individual mistakes include:

* forgetting to run tests frequently
* writing too many tests at once
* writing tests that are too large or coarse-grained
* writing overly trivial tests, for instance omitting assertions
* writing tests for trivial code, for instance accessors

Typical team pitfalls include:
* partial adoption - only a few developers on the team use TDD
* poor maintenance of the test suite - most commonly leading to a test suite with a prohibitively long running time
* abandoned test suite (i.e. seldom or never run) - sometimes as a result of poor maintenance, sometimes as a result of team turnover


## Rules Of Simplicity

Definition
A set of criteria, in priority order, proposed by Kent Beck to judge whether some source code is "simple enough":

* the code is verified by automated tests, and all such tests pass
* the code contains no duplication
* the code expresses separately each distinct idea or responsibility
* the code is composed of the minimum number of components (classes, methods, lines) compatible with the first three criteria


* [pinterest](https://www.pinterest.com)