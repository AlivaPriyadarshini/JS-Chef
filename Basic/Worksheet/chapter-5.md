//! 1.Write a simple function called greet that prints "Hello, World!" to the console.

ans - function greet(){
    console.log("Hello, World!")
}
greet();

//! 2.What is the difference between a parameter and an argument in a function?

ans - Argument is the actual value passed to a function and written in function call whether Parameter is a reference of the actual value, written in function definition.

//! 3.What will be the output of this code?

//!function add(a, b) {
//!  return a + b;
//!}
//!console.log(add(2, 3));

ans - 5

//! 4.How do you call (invoke) a function named showMessage?

function showMessage(msg){
    console.log(msg);
}
showMessage("Jay Jagannath!");

//! 5.Rewrite the following function as an arrow function:

//!function square(x) {
//!  return x * x;
//!}

ans - const square = (x)=>{
      return x*x;
}
console.log(square(2));

//! 6.What will this code print? Explain why.

// function test() {
//   return;
//   console.log("Done");
// }
// console.log(test());

ans - undefined,as test() did not return anything.Argument

//! 7.Write a function expression (assigned to a variable) that multiplies two numbers and returns the result.

const multi = function(a,b){
    return a*b;
}
console.log(multi(2,3));

//! 8.Write a function isEven that returns true if its argument is an even number, and false otherwise.

function isEven(a){
    if(a%2==0){
        return true;
    }else{
        return false;
    }
}
let result = isEven(9);
console.log(result);

or 

function isEven(a){
    return a%2==0;
}
console.log(isEven(9))

//!  9.What is the difference in how this works in a regular function vs. an arrow function?

//! 10.Write a function factorial(n) that returns the factorial of n (e.g., factorial(5) returns 120).
let f=1;
function factorial(n){
    for(let i = 1; i <= n; i++){
        f = f*i;
    }   
    return f; 
}
let result = factorial(6);
console.log(result);