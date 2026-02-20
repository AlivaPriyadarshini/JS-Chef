## 📝 JavaScript Arrays Worksheet

### Instructions:
- Answer the following questions about arrays in JavaScript.
- Questions are arranged from **easy** to **hard**.
- Write code where required and explain your reasoning briefly.

---

### **Easy (1-4)**

**1.**  
How do you declare an empty array in JavaScript?

:- let arr = [];
---

**2.**  
What is the index of the last element in this array?  
```js
let colors = ['red', 'green', 'blue', 'yellow'];

:- 3
```

---

**3.**  
What will this code output?  
```js
let arr = [10, 20, 30];
console.log(arr[1]);

:- 20
```

---

**4.**  
How many elements does this array have?  
```js
let nums = [5, 7, 9, 11, 13];

:-5
```

---

### **Medium (5-7)**

**5.**  
Change the value `'banana'` to `'grape'` in the following array:
```js
let fruits = ['apple', 'banana', 'cherry'];


:-
let fruits = ['apple', 'banana', 'cherry'];
fruits[1] = 'grape';

```

---

**6.**  
What will be the result of this code? Explain why.
```js
let a = [1, 2, 3];
let b = a;
b[0] = 99;
console.log(a);
```
:-The result will be [99,2,3];


---

**7.**  
Write code to access the value `6` from this array:
```js
let nested = [1, [4, 5, 6], 7];
```
let nested = [1, [4, 5, 6], 7];
console.log(nested[1][2])
---

### **Hard (8-10)**

**8.**  
What will this code print? Why?
```js
let arr = [1, , 3];
console.log(arr[1]);
console.log(arr.length);
```
:- undefined 
3

---

**9.**  
Create a new array `copyArr` that is a copy of `arr1` but independent (so changes to `copyArr` do not affect `arr1`):
```js
let arr1 = [10, 20, 30];
```
let arr1 = [10, 20, 30];
let copyArr = [...arr1]
---

**10.**  
Given the following 2D array, write code to print the value `8`:
```js
let matrix = [
  [2, 4],
  [6, 8]
];
```
let matrix = [
  [2, 4],
  [6, 8]
];

console.log(matrix[1][1])
---

### ✅ **Bonus:**
Try to answer all questions without running the code first. Then test your answers in a JavaScript environment to check your understanding!