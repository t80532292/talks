# Talk slides for various meetup presentations

## Join Calculus

Presented at [Scala Study Group meetup, November 10, 2013](http://www.meetup.com/Scala-Study-Group/events/149187102/).

### Abstract

This is a tutorial introduction to the Join Calculus and JoCaml. I show a demo of the Dining Philosophers problem using JoCaml and do a quick comparison of the Actor programming model with the Join Calculus.

Conclusions:

* Join calculus is concurrent programming in pure functional style

* Join calculus is similar to Actors but "more concurrent and more purely functional"


[Talk slides](join_calculus/join_calculus_talk.pdf)

## Temporal Logic and Functional Reactive Programming

Presented at [Bay Area Categories and Types meetup, April 25, 2014](http://www.meetup.com/Bay-Area-Categories-And-Types/events/174846952/) 

### Abstract

In my day job, most bugs come from imperatively implemented reactive
programs. Temporal Logic and FRP are declarative approaches that promise
to solve my problems. I will briefly review the motivations behind
and the connections between temporal logic and FRP. I propose a rather
"pedestrian" approach to propositional
linear-time temporal logic (LTL), showing how to perform calculations
in LTL and how to synthesize programs from LTL formulas. I intend
to explain why LTL largely failed to solve the synthesis problem,
and how FRP tries to cope.

FRP can be formulated as a lambda-calculus with types given by
the propositional intuitionistic LTL. I will discuss the limitations
of this approach, and outline the features of FRP that are required
by typical application programming scenarios.

My talk will be largely self-contained and should be understandable
to anyone familiar with Curry-Howard and functional programming.

[Talk slides](frp/frp_talk.pdf)

## That scripting language called Prolog

Presented at [SF Types, Theorems, and Programming Languages meetup, June 16, 2014](http://www.meetup.com/SF-Types-Theorems-and-Programming-Languages/events/185660512/)

### Summary

* What is "logic programming" and "constraint programming"

* Prolog in a nutshell

* How Prolog "makes pointers safe"

* Why Prolog was the ultimate scripting language for AI (backtracking search,
 interpreters, and DSLs for free)

* What is "functional-logic programming" (a taste of the programming languages
 Mercury and Curry)

[Talk slides](prolog/prolog_talk.pdf)

[Video: animated slides with audio recording](http://youtu.be/Fhc7fPQF1iY­)

## Elm-style Functional Reactive Programming demystified

Presented at [SF Types, Theorems, and Programming Languages meetup, April 13, 2015](http://www.meetup.com/SF-Types-Theorems-and-Programming-Languages/events/220473634/)

### Abstract

In my day job, most bugs come from implementing reactive programs imperatively. FRP is a declarative approach that promises to solve these problems.

FRP can be defined as a λ-calculus that admits temporal types, i.e. types given by a propositional intuitionistic linear-time temporal logic (LTL). Although the `Elm` language uses only a subset of LTL, it achieves high expressivity for GUI programming. I will formally define the operational semantics of `Elm`. I discuss the current limitations of `Elm` and outline possible extensions. I also review the connections between temporal logic, FRP, and `Elm`.

My talk will be understandable to anyone familiar with Curry-Howard and functional programming. The first part of the talk is a self-contained presentation of `Elm` that does not rely on temporal logic or Curry-Howard. The second part of the talk will explain the basic intuitions behind temporal logic and its connection with FRP.

[Talk slides](elm-talk/elm_talk.pdf)

