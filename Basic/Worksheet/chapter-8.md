## 📝 JavaScript Array Methods Worksheet

### Instructions:
- Answer the following questions about JavaScript array methods.
- Questions are arranged from **easy** to **hard**.
- Write code where required and explain your reasoning briefly.

---

### **Easy (1-7)**

**1.**  
Which method adds one or more elements to the end of an array?

:push()

---

**2.**  
What does the `pop()` method do to an array?

:- Remove the last element
---

**3.**  
Write code to remove the first element from this array:  
```js
let nums = [10, 20, 30];
```
let nums = [10, 20, 30];
nums.shift();
console.log(nums);
---

**4.**  
How do you add `"apple"` to the beginning of this array?  
```js
let fruits = ["banana", "cherry"];
```
let fruits = ["banana", "cherry"];
fruits.unshift("apple");
console.log(fruits)
---

**5.**  
What will be the result of this code?  
```js
let arr = [1, 2, 3];
arr.reverse();
console.log(arr);
```
it will reverse the element in an array 
[3,2,1];
---

**6.**  
Which method returns a shallow copy of a portion of an array, without modifying the original?

:-slice()
---

**7.**  
How do you check if the number `5` exists in this array?  
```js
let arr = [1, 3, 5, 7];
```
using includes()

let arr = [1, 3, 5, 7];
console.log(arr.includes(5))
---

### **Medium (8-14)**

**8.**  
Write code to combine these two arrays into a new array:  
```js
let a = [1, 2];
let b = [3, 4];
```
let a = [1, 2];
let b = [3, 4];
let combined = [...a,...b];
console.log(combined)
---

**9.**  
What does the following code output?  
```js
let arr = [1, 2, 3, 4];
arr.splice(1, 2);
console.log(arr);
```
:[1,4]

---

**10.**  
How would you replace the value `20` with `99` in this array using `splice`?  
```js
let arr = [10, 20, 30];
```
let arr = [10, 20, 30];
arr.splice(1,1,99);
console.log(arr)
---

**11.**  
What does this code print and why?  
```js
let arr = [1, 2, 3];
console.log(arr.slice(1, 3));
console.log(arr);
```
This code will print :
[2,3]
[1,2,3]

because:
slice(1,3) will return elements from index 1 to 2.
slice() doesn't modify orginal array so arr remains same [1,2,3]

---

**12.**  
Write code to join all elements of this array with a dash (`-`):  
```js
let arr = ['a', 'b', 'c'];
```

---

**13.**  
How do you find the index of `"cat"` in this array?  
```js
let pets = ["dog", "cat", "bird"];
```
let pets = ["dog", "cat", "bird"];
console.log(pets.indexOf("cat"))
---

**14.**  
What does the following code print?  
```js
let arr = [2, 4, 6];
console.log(arr.every(n => n % 2 === 0));
```
:true
---

### **Hard (15-20)**

**15.**  
Write code to double every number in this array using `map`:  
```js
let nums = [1, 2, 3];
```
let nums = [1, 2, 3];
let doubled = nums.map(n => n*2);
console.log(doubled);

---

**16.**  
How would you create a new array with only the odd numbers from this array?  
```js
let arr = [1, 2, 3, 4, 5];
```
let arr = [1, 2, 3, 4, 5];
let odds = arr.filter( n => n % 2 !== 0 );
console.log(odds);

---

**17.**  
What does this code print?  
```js
let arr = [1, 2, 3];
let sum = arr.reduce((acc, curr) => acc + curr, 0);
console.log(sum);
```

---

**18.**  
Write code to find the **first number greater than 10** in this array:  
```js
let arr = [2, 7, 15, 3];
```

---

**19.**  
How do you check if **at least one** number in the array is negative?  
```js
let arr = [4, -2, 7];
```

---

**20.**  
Write code to remove the second and third elements from this array and insert `"a"` and `"b"` in their place:  
```js
let arr = [0, 1, 2, 3, 4];
```

---

### ✅ **Bonus:**
Try to answer all questions without running the code first. Then test your answers in a JavaScript environment to check your understanding!