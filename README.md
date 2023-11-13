# learn-agda-by-doing-exercises

A large collection of cumulative Agda exercises to aid in learning with brief and to-the-point explanations. A primary goal of this tutorial is to avoid making conceptual leaps and to introduce as few concepts as possible at once, so that each tiny concept can be explained and practiced in a maximally isolated manner. At the same time, explanations are very dense with information, so exercises (which are entire agda files) can also be used as a reference. Absolutely no prior experience is expected but due to the information-dense style, experience with programming (especially functional programming) will likely be helpful.

Each exercise may be completed independently, though they generally build off of content in previous exercises. Exercises mostly use naming conventions from the Agda stdlib while providing ascii synonyms for users who don't want to type unicode symbols. This allows "Agda exercises" to double as "Agda stdlib exercises". Each exercise imports definitions from the provided solutions (in the Solutions directory) to previous exercises, so exercises do not depend on the reader's solutions (in the Exercises directory).

To get started, [install Agda](https://agda.readthedocs.io/en/latest/getting-started/installation.html) (I promise it's worth the pain) and clone this repo. Then open Exercises/Ex0.agda (or whatever piques your interest, if you have prior experience) and start reading.

Files may contain comments up to 150 characters long, so be prepared to turn on line wrap if your display isn't wide enough.

## Other Resources

These Exercises aim to be more or less exactly what I wish existed when I started learning Agda. They may however not be helpful to everybody, and, even more so, may not be sufficient for learning Agda without other resources. The amount of new knowledge you need to absorb tends to ramp up very quickly when following any Agda tutorial and, consequently, you may quickly hit a dead end, at which point things become too difficult and confusing to progress further. I therefore highly recommending learning from multiple sources at once, as they will all re-explain various important concepts in different ways and touch on slightly different topics. This will also allow you to get as far as you can with each resource, and then move on to the next. By the time you circle back around to a resource again, you will understand more and be able to make it further. For this purpose I recommend the following resources. Start at the top and work your way down as you see fit. If one resource isn't working then try another one, and maybe come back to the first one later.

### Agda From Nothing Follow-Along Introductory Lectures

[Github repo](https://github.com/scott-fleischman/agda-from-nothing)

[Part 1 on Youtube](https://www.youtube.com/watch?v=-i-QQ36Nfsk)

[Part 2 on Youtube](https://www.youtube.com/watch?v=XprGyVWXwks)

- Short lecture series recording
- For a (more) general audience
- Stays relatively surface-level

### Connor McBride's Lecture Series CS410 2017

[Github repo with exercises and lecture notes](https://github.com/pigworker/CS410-17)

[Youtube playlist Lecture 1](https://www.youtube.com/watch?v=O4oczQry9Jw&list=PLqggUNm8QSqmeTg5n37oxBif-PInUfTJ2&t=500s)

- In-depth university course recording
- Great exercises :^)
- Sharp learning curve

### Agda Tutorial from ELTE Budapest

[Agda Tutorial](https://people.inf.elte.hu/divip/AgdaTutorial/Index.html)

- Programmer's tutorial to Agda
- Open ended exercises :^)
- Easy to navigate

### Official Agda Documentation

[Index](https://agda.readthedocs.io/en/latest/language/index.html)

[Interactive Mode Commands](https://agda.readthedocs.io/en/latest/tools/emacs-mode.html#keybindings)

- Exhaustive documentation of all of Agda
- Definitely not intended to be used as a tutorial
- Still can be very helpful and informative about specific features

### Zulip Chatroom

[Zulip Agda](https://agda.zulipchat.com/)

- Most popular (to my knowledge) Agda-related chat/forum
- Many friendly and enthusiastic people ready to help and answer questions
- You can learn a lot by reading answers to old questions

### Codewars Exercises

[Codewars.com](https://www.codewars.com/)

[Codewars Agda Docs](https://docs.codewars.com/languages/agda)

- Still "in beta" though completely usable as far as I can tell
- Plenty of good and fun challenges about various topics
- Uses an old version of stdlib :(

### An introduction to Agda targeted at Haskell programmers

[Programming and Proving in Agda](https://github.com/jespercockx/agda-lecture-notes/blob/master/agda.pdf)

- Simple and well written intro
- Doesn't go super deep
- Exercises are good but few

### An introduction to programming language theory in Agda with exercises

[Programming Language Foundations in Agda](https://plfa.github.io/Preface/)

[Exercises](https://github.com/plfa/plfa.github.io/tree/dev/courses/TSPL/2022)

- Generally challenging content
- Lots of great exercises :^)
- Introduces the Agda stdlib

### A video introduction series on Agda and Type Theory

[Introductory Lectures on Type Theory playlist first lecture](https://www.youtube.com/watch?v=Y7blCeETJo8&list=PL3XL6suc7Hp70kLZVUImSDYXd4GE_E8Ys)

- Goes slowly and clearly through some underlying theory of Agda
- Examines various topics in logic and type theory
- Content is further away from practical programming

### An interactive introduction to Agda and Homotopy Type Theory

[The HoTT Game](https://thehottgameguide.readthedocs.io/en/latest/index.html)

- Dives into homotopy type theory in addition to plain type-theory/logic
- Learning by doing exercises :^)
- Aimed at Mathematicians

### A series of lectures on (Homotopy) Type Theory and (Cubical) Agda with exercises

[Type Theory Lecture 1](https://www.youtube.com/watch?v=HvYYCHMeM-8&list=PLtIZ5qxwSNnzpNqfXzJjlHI9yCAzRzKtx&index=1)

[Type Theory Exercises](https://github.com/martinescardo/HoTTEST-Summer-School/tree/main/HoTT/Worksheets)

[Agda Lecture 1](https://www.youtube.com/watch?v=fJxWLQaaCX4&list=PLtIZ5qxwSNnzpNqfXzJjlHI9yCAzRzKtx&index=3)

[Exercises for Agda lectures 1-3, Vanilla Agda](https://github.com/martinescardo/HoTTEST-Summer-School/tree/main/Agda/Exercises)

[Exercises for Agda lectures 4-6, Higher Inductive Types](https://github.com/martinescardo/HoTTEST-Summer-School/tree/main/Agda/HITs)

[Exercises for Agda lectures 7-9, Cubical Agda](https://github.com/martinescardo/HoTTEST-Summer-School/tree/main/Agda/Cubical)

- Large series with lectures both on pure theory, and on using Agda
- Lots of great exercises :^)
- Content can sometimes be difficult to follow

## The Best Resource

And finally, the most important resource (in my opinion), is to just go screw around in Agda. Try to formalize random things that interst you, play around, and have FUN.

Good luck on your Agda journey!

## Table of Contents

### Part 1 - Functional Programming

### Ex0 - Functions

- Basic OPTIONS and top-level modules
- Unicode support and interactive editing
- Polymorphic functions
- Normal vs implicit/inferred parameters
- Currying
- Lambdas
- Higher order functions
- Absurdities

### (WIP Table of not-yet-completed Contents)

### Booleans

- "import", "open", and "open import"
- The definition of Bool
- Indentation and whitespace
- Pattern matching
- Infix operators, precedence, and confusing errors
- Evaluating/normalizing expressions
- Functions into Set and compile-time computations

### Natural Numbers

- Recursion and termination checking

### Maybe

- Universe levels

### Lists

### Part 2 - Constructive Logic

### Propositions

- Re-defining important functions from Ex0 with levels and stdlib-style syntax
- Unit
- Empty
- Negation

### Sums

### Products

### Part 3 - Dependent Types

### Pi

- Dependent pattern matching

### Sigma

### Recursors and Eliminators

- "if then else"
- natural-induction

### GADTs

- Reflects

### Part 4 - Equality

### Propositional Equality

### Decideable Equality

- instance arguments

### Extensionality

### Part 5 - Programming with Types

### Church Encodings

- Free theorems from parametricity

### Finite Sets

### Length-indexed Lists

- Bit arrays and operations

### Termination

- Well founded relations

### Part 6 - Mathematical Constructs

### Isomorphisms

- Cardinalities and operations on finite sets

### Abstract Algebra

- Semigroup
- Monoid
- Group

### Setoids

### Double-Negation

- Double negation elimination
- Law of excluded middle
- Double negation shift

### Part 7 - Category Theory

### Categories

### Functors

### Natural Transformations

### Monads

### Monad Transformers

### Part 8 - Infinity

### Infinite Series

### Coinduction

- --guardedness
- Stream
- Colist
- Delay
- Conat
- Bisimilarity

### Cardinalities

- Non-invertible functions
- type-in-type paradox?

### Part 9 - Cubical Agda

### Paths

- Proof of extensionality

### HITs

### Quotients

### Univalence

### Part 10 - Beyond

### Logic

### Set Theory

- Defining various forms of set theory
- Modeling a simple constructive set theory

### Lambda Calculus
