#Functional Light JS

Functional programming in JavaScript by Kyle Simpson.

## Imperative Vs Declerative Code

Imperative describes the code most of us probably already write naturally; it's focused on precisely instructing the computer **how to do something**.
Declarative code -- the kind we'll be learning to write, which adheres to FP principles -- is code that's more focused **on describing the what outcome.**

## What Is a Function?

A function is a collection of code that can be executed one or more times. Is it?

In math, a function always takes input(s), and always gives an output. A term you'll often hear around FP is "morphism"; this is a fancy way of describing a set of values that maps to another set of values, like the inputs of a function related to the outputs of that function.

#### Function vs Procedure

A procedure is an arbitrary collection of functionality. It may have inputs, it may not. It may have an output (`return` value), it may not.

A function takes input(s) and definitely always has a `return` value.

So in Functional Programming, **you should be using functions as much as possible**, and trying to avoid procedures wherever possible. All your functions should take input(s) and return output(s).
