#Functional Light JS

Functional programming in JavaScript by Kyle Simpson.

## Imperative Vs Declerative Code

Imperative describes the code most of us probably already write naturally; it's focused on precisely instructing the computer **how to do something**.
Declarative code -- the kind we'll be learning to write, which adheres to FP principles -- is code that's more focused **on describing the what outcome.**

## What is a Function?

A function is a collection of code that can be executed one or more times. Is it?

In math, a function always takes input(s), and always gives an output. A term you'll often hear around FP is "morphism"; this is a fancy way of describing a set of values that maps to another set of values, like the inputs of a function related to the outputs of that function.

#### Function vs Procedure

A procedure is an arbitrary collection of functionality. It may have inputs, it may not. It may have an output (`return` value), it may not.

A function takes input(s) and definitely always has a `return` value.

So in Functional Programming, **you should be using functions as much as possible**, and trying to avoid procedures wherever possible. All your functions should take input(s) and return output(s).

### PROCEDURES

```js
function addNumbers(a = 0, b = 0, c = 0, d = 0) {
  var total = a + b + c + d;
  console.log(total);
}

function extraNumbers(a = 2, ...args) {
  return addNumbers(a, 40, ...args);
}

extraNumbers(); //42
extraNumbers(3, 8, 11); // 62
```

### FUNCTIONS

```js
function tuble(x, y) {
  return [x + 1, y - 1];
}

var [a, b] = tuple(...[5, 10]);

a; //6
b; //9
```
