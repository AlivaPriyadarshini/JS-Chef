*<!-- Variables and Data Types Worksheet -->

1.Which keyword would you use to declare a variable whose value will never change?
a) var
b) let
c) const

ans-(c)const

2.What will be the output of this code?
console.log(x);
var x = 5;
Explain your answer.

ans- The anser will be undeifined as it is the concept of hoisting in which only the declaration part is get hoisted not the initialization part.

3.Is the following code valid? Why or why not?
let a = 10;
let a = 20;

ans- No, this code is not valid beacuse let is a blocked scoped keyword and does not support redeclaration.

4.Identify the data type of each variable:
let name = "Bob";
let score = 99;
let isActive = false;
let nothing = null;
let notDefined;

ans - string,number,boolean,null,undefined

5.What is the difference between let and var in terms of scope?

ans- let is a block-scoped keyword in which reasignment and hoisting can't take place.whereas,
     var is a function-scoped keyword in which reasignment and hoisting can take place.

 6.What will be the output of this code?
const arr = [1, 2, 3];
arr.push(4);
console.log(arr);
Can you explain why this is allowed, even though arr is a const?

ans- output: [1,2,3,4]
    This is allowed because arr is not reassigned,it is only modified.const does not support reassignment but modification can be done.

7.Write code to demonstrate the difference between primitive and reference assignment.

let name = "Anisha";
let aim = name;

aim = "web dev";

console.log(name); // Anisha
console.log(aim); // web dev

let obj1 = { name: "Anisha" };
let obj2 = obj1;

obj2.name = "Aliva";

console.log(obj1.name); // Aliva
console.log(obj2.name); // Aliva

8.What will this code print? Explain why.
let a = { value: 5 };
let b = a;
b.value = 10;
console.log(a.value);

ans-output will be 10.As b=a that means whatever changes done in b will be reflected in a.

9.Is this code valid? Why or why not?
const x;
x = 10;

ans-No, this code is not valid as const is used as keyword which does not support reassignment.

10.Which of the following are primitive types in JavaScript?
a) String
b) Object
c) Boolean
d) Array
e) BigInt
f) Function

ans-string,boolean,BigInt