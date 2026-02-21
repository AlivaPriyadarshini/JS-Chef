## 📝 JavaScript Objects Worksheet

### Instructions:
- Answer the following questions about JavaScript objects and their usage.
- Questions are arranged from **easy** to **hard**.
- Write code where required and explain your reasoning briefly.

---

### **Easy (1–6)**

**1.**  
What is an object in JavaScript? Give an example.

:objects are collection of key-value pairs.keys are always string and valuecan be any data type.

const student={
  name:"Aliva",
  age : 17,
  branch : "BCA";
}
---

**2.**  
How do you create an empty object?

:-
const user = new Object();
console.log(user);

---

**3.**  
Given this object, how do you access the value `"Alice"`?
```js
let user = { name: "Alice", age: 25 };

:-
let user = { name: "Alice", age: 25 };
console.log(user.name);
```

---

**4.**  
How do you add a new property `city` with value `"Paris"` to the object above?
:-
let user = { name: "Alice", age: 25 };
console.log(user.name);
user.city="Paris";
---

**5.**  
What will this code output?
```js
let car = { brand: "Toyota", year: 2020 };
console.log(car["brand"]);
```
:- "Toyota"
---

**6.**  
How can you check if an object has a property called `"age"`?

:-
let user = { name: "Alice", age: 25 };
console.log("age" in user);
---

### **Medium (7–12)**

**7.**  
Write code to loop over all properties of an object and print their keys and values.

:-
let obj = { a: 1, b: 2, c: 3 };
for (let key in obj) {
  console.log(`${key}: ${obj[key]}`);
}
---

**8.**  
What is the difference between dot notation and bracket notation for accessing object properties?
:- - Dot notation: obj.property (property name is fixed)
- Bracket notation: obj["property"] (property name can be dynamic)  
---

**9.**  
How do you delete a property from an object? Show with code.

:-
let obj = { a: 1, b: 2 };
delete obj.a;
console.log(obj); // { b: 2 }
---

**10.**  
Given:
```js
let person = { name: "Bob", hobbies: ["reading", "sports"] };
```
How do you access the second hobby?

:-

let person = { name: "Bob", hobbies: ["reading", "sports"] };
console.log(person.hobbies[1]);
---

**11.**  
How do you merge two objects into a new object (without modifying the originals)?

:-
let obj1 = { a: 1, b: 2 };
let obj2 = { c: 3, d: 4 };
let merged = { ...obj1, ...obj2 };
console.log(merged); // { a: 1, b: 2, c: 3, d: 4 }
---

**12.**  
What does `Object.keys(obj)` return?
:-
An array of the object's own enumerable property names.

---

### **Hard (13–18)**

**13.**  
Write a function that takes an object and returns the number of properties it has.

:-
function countProps(obj) {
  return Object.keys(obj).length;
}
---

**14.**  
What will this code output? Explain.
```js
let a = { value: 10 };
let b = a;
b.value = 20;
console.log(a.value);
```
:- 20

---

**15.**  
How do you create a shallow copy of an object?

:-
let obj = { a: 1, b: 2 };
let copy = { ...obj };

---

**16.**  
What is the difference between a method and a property in an object? Give examples.

:-
- Property: a value associated with a key (name: "John")
- Method: a function associated with a key (greet: function() { ... })
---

**17.**  
Write an object `calculator` with methods `add(a, b)` and `subtract(a, b)` that return the sum and difference.

:-
let calculator = {
  add: (a, b) => a + b,
  subtract: (a, b) => a - b
};
---

**18.**  
Given:
```js
let obj = { x: 1, y: 2 };
for (let key in obj) {
  obj[key] = obj[key] * 2;
}
console.log(obj);

```
What will be the value of `obj` after this code runs?

:- { x: 2, y: 4 }
---

### ✅ **Bonus:**
Try to answer all questions without running the code first. Then test your answers in a JavaScript environment to check your understanding!