//! 1.Identify whether x is in the global or local scope:

// let x = 10;
// function test() {
//   console.log(x);
// }

ans - Here, x is in the global scope as it is declared outside the function.

//! 2.What will this code output?

// console.log(a);
// var a = 5;

ans - undefined

//! 3.True or False:
// A variable declared with let inside a block {} can be accessed outside that block.
// Explain your answer.

ans - False, because the let is "block-scoped" keyword, can be acccesed only inside a block.

//! 4.What is the output of this code?

// function greet() {
//   console.log("Hello");
// }
// greet();

ans - Hello

//! 5.What is the output? Why?

// let outer = 10;
// function innerFn() {
//   console.log(outer);
// }
// innerFn();

ans - 10

//! 6.Why does this code throw an error?

// console.log(b);
// let b = 20;

ans - As let is a block-scoped keyword so, it  can be accessed after before it is defined.As

//! 7.Rewrite this function declaration as a function expression and explain how hoisting affects it:

// function sayHi() {
//   console.log("Hi");
// }

const sayHi = function() {
  console.log("Hi");
};
sayHi(); // "Hi"

Hoisting Effect- Function declarations (function sayHi()) are hoisted → can call before defining.
                 Function expressions (const sayHi = function()) are not hoisted → can't call before defining.

//! 8.What will this code print? Explain the role of lexical scoping:

// function outer() {
//   let x = "outer";
//   function inner() {
//     console.log(x);
//   }
//   return inner;
// }
// const fn = outer();
// fn();

//! 9.Predict the output and explain the hoisting behavior:

var c = 1;
function test() {
  console.log(c);
  var c = 2;
}
test(); 
//! 10.Write a code snippet that demonstrates the Temporal Dead Zone (TDZ) for const.