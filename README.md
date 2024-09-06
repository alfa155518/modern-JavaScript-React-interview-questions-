# modern JavaScript & React interview Questions & Answers

 Click :star:if you like the project and follow [LinkedIn Profile](https://www.linkedin.com/in/ahmed-hassop) for more updates. Check [API Collection Free](https://github.com/alfa155518/API-s-collection-free) 


# Don't forget to pray and support our people in Gaza and Palestine <img src="https://upload.wikimedia.org/wikipedia/commons/0/00/Flag_of_Palestine.svg" alt="Palestine Flag" width="100" height="60">

-----

<!-- TOC_START -->

# modern JavaScript Interview Questions <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" alt="JavaScript Logo" width="100" height="100">


| No. | Questions                                                                                                                                                                                                                                          |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [What is JavaScript?](#1-what-is-javascript)                                                                                                                                                                                                       |
| 2   | [What are the data types supported by JavaScript?](#2-what-are-the-data-types-supported-by-javascript)                                                                                                                                             |
| 3   | [What is the difference between `let`, `const`, and `var`?](#3-what-is-the-difference-between-let-const-and-var)                                                                                                                                   |
| 4   | [Explain how `==` and `===` differ.](#4-explain-how--and--differ)                                                                                                                                                                                  |
| 5   | [What is a closure?](#5-what-is-a-closure)                                                                                                                                                                                                         |
| 6   | [What is hoisting?](#6-what-is-hoisting)                                                                                                                                                                                                           |
| 7   | [Explain the concept of "this" in JavaScript.](#7-explain-the-concept-of-this-in-javascript)                                                                                                                                                       |
| 8   | [What are JavaScript prototypes?](#8-what-are-javascript-prototypes)                                                                                                                                                                               |
| 9   | [What is the difference between `null` and `undefined`?](#9-what-is-the-difference-between-null-and-undefined)                                                                                                                                     |
| 10  | [How does JavaScript handle asynchronous operations?](#10-how-does-javascript-handle-asynchronous-operations)                                                                                                                                      |
| 11  | [What is a promise?](#11-what-is-a-promise)                                                                                                                                                                                                        |
| 12  | [What are async/await functions?](#12-what-are-asyncawait-functions)                                                                                                                                                                               |
| 13  | [Explain event delegation in JavaScript.](#13-explain-event-delegation-in-javascript)                                                                                                                                                              |
| 14  | [What are JavaScript modules?](#14-what-are-javascript-modules)                                                                                                                                                                                    |
| 15  | [How can you prevent a function from being called multiple times?](#15-how-can-you-prevent-a-function-from-being-called-multiple-times)                                                                                                            |
| 16  | [What is the event loop?](#16-what-is-the-event-loop)                                                                                                                                                                                              |
| 17  | [What is the difference between `apply()` and `call()` methods?](#17-what-is-the-difference-between-apply-and-call-methods)                                                                                                                        |
| 18  | [What is `bind()` method used for?](#18-what-is-bind-method-used-for)                                                                                                                                                                              |
| 19  | [What is a JavaScript event loop?](#19-what-is-a-javascript-event-loop)                                                                                                                                                                            |
| 20  | [Explain the concept of "event bubbling" and "event capturing".](#20-explain-the-concept-of-event-bubbling-and-event-capturing)                                                                                                                    |
| 21  | [What is the difference between deep copy and shallow copy?](#21-what-is-the-difference-between-deep-copy-and-shallow-copy)                                                                                                                        |
| 22  | [What are generator functions?](#22-what-are-generator-functions)                                                                                                                                                                                  |
| 23  | [What is the `new` keyword used for?](#23-what-is-the-new-keyword-used-for)                                                                                                                                                                        |
| 24  | [How do JavaScript’s `setTimeout` and `setInterval` work?](#24-how-do-javascripts-settimeout-and-setinterval-work)                                                                                                                                 |
| 25  | [What is a `WeakMap` and how is it different from a `Map`?](#25-what-is-a-weakmap-and-how-is-it-different-from-a-map)                                                                                                                              |
| 26  | [What is a `Set` in JavaScript?](#26-what-is-a-set-in-javascript)                                                                                                                                                                                  |
| 27  | [What is `Object.create()` used for?](#27-what-is-objectcreate-used-for)                                                                                                                                                                           |
| 28  | [How does JavaScript’s garbage collection work?](#28-how-does-javascripts-garbage-collection-work)                                                                                                                                                 |
| 29  | [What are "decorators" in JavaScript?](#29-what-are-decorators-in-javascript)                                                                                                                                                                      |
| 30  | [Explain the difference between `prototype` and `__proto__`.](#30-explain-the-difference-between-prototype-and-proto)                                                                                                                              |
| 31  | [What is the purpose of `Object.assign()`?](#31-what-is-the-purpose-of-objectassign)                                                                                                                                                               |
| 32  | [What are "template literals"?](#32-what-are-template-literals)                                                                                                                                                                                    |
| 33  | [What is the `spread` operator?](#33-what-is-the-spread-operator)                                                                                                                                                                                  |
| 34  | [What is the `rest` parameter?](#34-what-is-the-rest-parameter)                                                                                                                                                                                    |
| 35  | [Explain the `for...of` loop.](#35-explain-the-forof-loop)                                                                                                                                                                                         |
| 36  | [What are `async` and `await` keywords used for?](#36-what-are-async-and-await-keywords-used-for)                                                                                                                                                  |
| 37  | [What is `Symbol` used for in JavaScript?](#37-what-is-symbol-used-for-in-javascript)                                                                                                                                                              |
| 38  | [How do you create a class in JavaScript?](#38-how-do-you-create-a-class-in-javascript)                                                                                                                                                            |
| 39  | [What is destructuring in JavaScript?](#39-what-is-destructuring-in-javascript)                                                                                                                                                                    |
| 40  | [What is the `Proxy` object?](#40-what-is-the-proxy-object)                                                                                                                                                                                        |
| 41  | [Program to find longest word in a given sentence](#41-program-to-find-longest-word-in-a-given-sentence)                                                                                                                                           |
| 42  | [How to check whether a string is palindrome or not?](#42-how-to-check-whether-a-string-is-palindrome-or-not)                                                                                                                                      |
| 43  | [Write a program to remove duplicates from an array](#43-write-a-program-to-remove-duplicates-from-an-array)                                                                                                                                       |
| 44  | [Program to find Reverse of a string without using built-in method](#44-program-to-find-reverse-of-a-string-without-using-built-in-method)                                                                                                         |
| 45  | [Find the max count of consecutive 1’s in an array](#45-find-the-max-count-of-consecutive-1s-in-an-array)                                                                                                                                          |
| 46  | [Find the factorial of given number](#46-find-the-factorial-of-given-number)                                                                                                                                                                       |
| 47  | [Given 2 arrays that are sorted, merge them and sort](#47-given-2-arrays-that-are-sorted-merge-them-and-sort)                                                                                                                                      |
| 48  | [Create a function to check if every value in arr1 has its corresponding value squared in arr2](#48-create-a-function-to-check-if-every-value-in-arr1-has-its-corresponding-value-squared-in-arr2)                                                 |
| 49  | [Given two strings, find if one string can be formed by rearranging the letters of the other string](#49-given-two-strings-find-if-one-string-can-be-formed-by-rearranging-the-letters-of-the-other-string)                                        |
| 50  | [Write logic to get unique objects from an array](#50-write-logic-to-get-unique-objects-from-an-array)                                                                                                                                             |
| 51  | [Write a JavaScript program to find the maximum number in an array](#51-write-a-javascript-program-to-find-the-maximum-number-in-an-array)                                                                                                         |
| 52  | [Write a JavaScript function that takes an array of numbers and returns a new array with only the even numbers](#52-write-a-javascript-function-that-takes-an-array-of-numbers-and-returns-a-new-array-with-only-the-even-numbers)                 |
| 53  | [Write a JavaScript function to check if a given number is prime](#53-write-a-javascript-function-to-check-if-a-given-number-is-prime)                                                                                                             |
| 54  | [Write a JavaScript program to find the largest element in a nested array](#54-write-a-javascript-program-to-find-the-largest-element-in-a-nested-array)                                                                                           |
| 55  | [Write a JavaScript function that returns the Fibonacci sequence up to a given number of terms](#55-write-a-javascript-function-that-returns-the-fibonacci-sequence-up-to-a-given-number-of-terms)                                                 |
| 56  | [Given a string, write a JavaScript function to count the occurrences of each character in the string](#56-given-a-string-write-a-javascript-function-to-count-the-occurrences-of-each-character-in-the-string)                                    |
| 57  | [Write a JavaScript function that sorts an array of numbers in ascending order](#57-write-a-javascript-function-that-sorts-an-array-of-numbers-in-ascending-order)                                                                                 |
| 58  | [Write a JavaScript function that sorts an array of numbers in descending order](#58-write-a-javascript-function-that-sorts-an-array-of-numbers-in-descending-order)                                                                               |
| 59  | [Write a JavaScript function that reverses the order of words in a sentence without using the built-in reverse() method](#59-write-a-javascript-function-that-reverses-the-order-of-words-in-a-sentence-without-using-the-built-in-reverse-method) |
| 60  | [Implement a JavaScript function that flattens a nested array into a single-dimensional array](#60-implement-a-javascript-function-that-flattens-a-nested-array-into-a-single-dimensional-array)                                                   |





# Modern React Interview Questions  <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" alt="React Icon" width="100" height="100">

| No. | Questions                                                                                                                                                 |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [What is React?](#1-what-is-react)                                                                                                                        |
| 2   | [What is useMemo?](#2-what-is-usememo)                                                                                                                    |
| 3   | [What are the features of React?](#3-what-are-the-features-of-react)                                                                                      |
| 4   | [What is JSX?](#4-what-is-jsx)                                                                                                                            |
| 5   | [What is DOM?](#5-what-is-dom)                                                                                                                            |
| 6   | [What is Virtual DOM?](#6-what-is-virtual-dom)                                                                                                            |
| 7   | [What is the component lifecycle of React class component?](#7-what-is-the-component-lifecycle-of-react-class-component)                                  |
| 8   | [What are fragments in React?](#8-what-are-fragments-in-react)                                                                                            |
| 9   | [What are props in React?](#9-what-are-props-in-react)                                                                                                    |
| 10  | [What are synthetic events in React?](#10-what-are-synthetic-events-in-react)                                                                             |
| 11  | [What is the difference between Package.json and Package.lock.json?](#11-what-is-the-difference-between-packagejson-and-packagelockjson)                  |
| 12  | [What are the differences between client-side and server-side rendering?](#12-what-are-the-differences-between-client-side-and-server-side-rendering)     |
| 13  | [What is state in React?](#13-what-is-state-in-react)                                                                                                     |
| 14  | [What are props?](#14-what-are-props)                                                                                                                     |
| 15  | [What are the differences between state and props in React?](#15-what-are-the-differences-between-state-and-props-in-react)                               |
| 16  | [What is props drilling?](#16-what-is-props-drilling)                                                                                                     |
| 17  | [What are the disadvantages of props drilling and how can we avoid it?](#17-what-are-the-disadvantages-of-props-drilling-and-how-can-we-avoid-it)         |
| 18  | [What are pure components in React?](#18-what-are-pure-components-in-react)                                                                               |
| 19  | [What are refs in React?](#19-what-are-refs-in-react)                                                                                                     |
| 20  | [What is meant by forward ref?](#20-what-is-meant-by-forward-ref)                                                                                         |
| 21  | [What are error boundaries?](#21-what-are-error-boundaries)                                                                                               |
| 22  | [What are higher-order components in React?](#22-what-are-higher-order-components-in-react)                                                               |
| 23  | [What are the differences between controlled and uncontrolled components?](#23-what-are-the-differences-between-controlled-and-uncontrolled-components)   |
| 24  | [What is useCallback?](#24-what-is-usecallback)                                                                                                           |
| 25  | [What are the differences between useMemo and useCallback?](#25-what-are-the-differences-between-usememo-and-usecallback)                                 |
| 26  | [What are keys in React?](#26-what-are-keys-in-react)                                                                                                     |
| 27  | [What is lazy loading in React?](#27-what-is-lazy-loading-in-react)                                                                                       |
| 28  | [What is suspense in React?](#28-what-is-suspense-in-react)                                                                                               |
| 29  | [What are custom hooks?](#29-what-are-custom-hooks)                                                                                                       |
| 30  | [What is the useReducer hook?](#30-what-is-the-usereducer-hook)                                                                                           |
| 31  | [What are portals in React?](#31-what-are-portals-in-react)                                                                                               |
| 32  | [What is context in React?](#32-what-is-context-in-react)                                                                                                 |
| 33  | [Practical question: Give an example of context API usage?](#33-practical-question-give-an-example-of-context-api-usage)                                  |
| 34  | [What is the purpose of the callback function as an argument of setState()?](#34-what-is-the-purpose-of-the-callback-function-as-an-argument-of-setstate) |
| 35  | [Practical question: Create a custom hook for increment/decrement counter?](#35-practical-question-create-a-custom-hook-for-increment-decrement-counter)  |
| 36  | [Which lifecycle hooks in class components are replaced with useEffect in functional components?](#36-which-lifecycle-hooks-are-replaced-by-useeffect)    |
| 37  | [What is strict mode in React?](#37-what-is-strict-mode-in-react)                                                                                         |
| 38  | [What are the different ways to pass data from a child component to a parent component in React?](#38-ways-to-pass-data-from-child-to-parent-in-react)    |
| 39  | [Practical question: How to send data from child to parent using callback functions?](#39-how-to-send-data-from-child-to-parent-using-callback-functions) |
| 40  | [Practical question: How to send the data from a child component to a parent using useRef?](#40-how-to-send-data-from-child-to-parent-using-useref)       |





<!-- TOC_END -->
---

### 1. What is JavaScript?

JavaScript is a versatile programming language primarily used for enhancing web pages to provide interactive content, such as forms, animations, and dynamic user experiences. It runs in the browser and is often used for both client-side and server-side scripting.

---

### 2. What are the data types supported by JavaScript?

JavaScript supports several data types, including:

- **Primitive types**: `string`, `number`, `boolean`, `null`, `undefined`, `symbol`, and `bigint`.
- **Non-primitive types**: `object`, including `Array`, `Function`, and `Date`.

---

### 3. What is the difference between `let`, `const`, and `var`?

The difference between `let`, `const`, and `var` is related to scope and reassignment:

- **`var`** is function-scoped, can be redeclared, and is hoisted to the top.
- **`let`** is block-scoped, can't be redeclared but can be reassigned.
- **`const`** is block-scoped, can't be redeclared or reassigned (though objects and arrays can still have their contents modified).

Example:
```javascript
var x = 1;
let y = 2;
const z = 3;
```



### 4. Explain how == and === differ.
- **`==`**: Checks for equality after type coercion. It converts the operands to the same type before making the comparison.
- **`===`**: Checks for strict equality, meaning both value and type must be the same.

Example:
```javascript
console.log(1 == '1');  // true (type coercion)
console.log(1 === '1'); // false (strict equality)
```



### 5. What is a closure?
A closure is a function that remembers and has access to variables from its outer scope, even after the outer function has finished executing.

Example:
```javascript
function outerFunction(outerVariable) {
  return function innerFunction(innerVariable) {
    console.log(outerVariable, innerVariable);
  };
}

const newFunction = outerFunction('outside');
newFunction('inside'); // outside inside
```




### 6. What is hoisting?
Hoisting is a JavaScript mechanism where variable and function declarations are moved to the top of their scope before code execution. Only declarations are hoisted, not initializations.

Example:
```javascript
console.log(a); // undefined
var a = 5;

hoistedFunction(); // "Hoisted!"
function hoistedFunction() {
  console.log("Hoisted!");
}
```




### 7. Explain the concept of "this" in JavaScript.
The value of this in JavaScript refers to the context in which a function is invoked. It can change depending on how a function is called, such as within a method, globally, or via call, apply, or bind.

Example:
```javascript
const obj = {
  name: 'Alice',
  greet() {
    console.log(`Hello, ${this.name}`);
  }
};
obj.greet(); // "Hello, Alice"
```


### 8. What are JavaScript prototypes?
A prototype is an object from which other objects inherit properties and methods. Every JavaScript object has a prototype, which allows for inheritance.

Example:
```javascript
function Person(name) {
  this.name = name;
}

Person.prototype.greet = function() {
  console.log(`Hello, my name is ${this.name}`);
};

const alice = new Person('Alice');
alice.greet(); // Hello, my name is Alice
```



### 9. What is the difference between null and undefined?
null: Represents an intentional absence of any object value. It must be assigned explicitly.
undefined: Represents a variable that has been declared but not yet assigned a value.

Example:
```javascript
let a;          // a is undefined
let b = null;   // b is explicitly set to null
```



### 10. How does JavaScript handle asynchronous operations?
JavaScript handles asynchronous operations using callback functions, promises, and async/await. These allow non-blocking operations, such as fetching data from an API or reading a file.

Example using a promise:
```javascript
fetch('https://api.example.com')
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error(error));
```

### 11. What is a promise?
A promise is an object representing the eventual completion or failure of an asynchronous operation. It has three states: pending, fulfilled, and rejected.

Example:
```javascript
let promise = new Promise((resolve, reject) => {
    // Asynchronous operation
    setTimeout(() => {
        resolve("Data received");
    }, 1000);
});

promise.then(data => console.log(data)); // Logs: Data received
```


### 12. What are async/await functions?

async and await are syntactic sugars for working with promises. An async function always returns a promise, and await pauses the execution until the promise is resolved.

Example:
```javascript
async function fetchData() {
    let data = await new Promise((resolve) => {
        setTimeout(() => resolve("Data received"), 1000);
    });
    console.log(data);
}

fetchData(); // Logs: Data received
```

### 13. Explain event delegation in JavaScript.

Event delegation involves attaching a single event listener to a parent element to manage events for its children. This approach leverages event bubbling to handle events for multiple child elements.

Example:

```javascript
document.querySelector("#parent").addEventListener("click", function (event) {
  if (event.target && event.target.matches("button")) {
    console.log("Button clicked:", event.target.textContent);
  }
});
```

### 14. What are JavaScript modules?

JavaScript modules allow you to split code into separate files, each with its own scope. Modules use export and import to share and use code.

Example:

**math.js**:

```javascript
export function add(x, y) {
  return x + y;
}
```

**main.js**:

```javascript
import { add } from "./math.js";
console.log(add(2, 3)); // Logs: 5
```

### 15. How can you prevent a function from being called multiple times?

Techniques include using flags, debouncing, and throttling.

Example:

```javascript
let isCalled = false;

function myFunction() {
  if (!isCalled) {
    isCalled = true;
    // Function logic here
  }
}
```

### 16. What is the event loop?

The event loop is a mechanism that allows JavaScript to handle asynchronous operations by continuously checking the call stack and message queue.

### 17. What is the difference between apply() and call() methods?

Both methods invoke a function with a specified this value. call() accepts arguments individually, while apply() accepts arguments as an array.

Example:

```javascript
function greet(greeting, name) {
  console.log(`${greeting}, ${name}!`);
}

greet.call(null, "Hello", "John"); // Hello, John!
greet.apply(null, ["Hello", "John"]); // Hello, John!
```

### 18. What is bind() method used for?

bind() creates a new function with a specified this value and initial arguments.

Example:

```javascript
function greet(greeting, name) {
  console.log(`${greeting}, ${name}!`);
}

let greetHello = greet.bind(null, "Hello");
greetHello("John"); // Hello, John!
```

### 19. What is a JavaScript event loop?

The event loop is the mechanism that allows JavaScript to perform non-blocking operations by handling asynchronous tasks and ensuring that the code executes in a single thread.

### 20. Explain the concept of "event bubbling" and "event capturing".

Event Bubbling: The event starts from the target element and bubbles up to the root.
Event Capturing: The event starts from the root and captures down to the target element.

Example:

```javascript
document.querySelector("#child").addEventListener(
  "click",
  function (event) {
    console.log("Child clicked");
  },
  true
); // true for capturing

document.querySelector("#parent").addEventListener("click", function (event) {
  console.log("Parent clicked");
});
```

### 21. What is the difference between deep copy and shallow copy?

Shallow Copy: Copies only the top-level properties. Nested objects are shared between the original and copied objects.

Deep Copy: Copies all levels of properties, creating independent nested objects.

Example:

```javascript
let original = { a: 1, b: { c: 2 } };
let shallowCopy = { ...original };
let deepCopy = JSON.parse(JSON.stringify(original));

shallowCopy.b.c = 3;
console.log(original.b.c); // 3 (shallow copy shares nested object)
console.log(deepCopy.b.c); // 2 (deep copy does not affect original)
```

### 22. What are generator functions?

Generator functions use the function\* syntax and return an iterator. They allow pausing and resuming execution, and yield values one at a time.

Example:

```javascript
function* generator() {
  yield 1;
  yield 2;
  yield 3;
}

let gen = generator();
console.log(gen.next().value); // 1
console.log(gen.next().value); // 2
```

### 23. What is the new keyword used for?

The new keyword creates an instance of a constructor function or class.

Example:

```javascript
function Person(name) {
  this.name = name;
}

let person = new Person("John");
console.log(person.name); // John
```

### 24. How do JavaScript’s setTimeout and setInterval work?

setTimeout(fn, delay): Executes fn once after delay milliseconds.
setInterval(fn, interval): Executes fn repeatedly every interval milliseconds.

Example:

```javascript
setTimeout(() => console.log("Executed once"), 1000);
setInterval(() => console.log("Executed repeatedly"), 1000);
```

### 25. What is a WeakMap and how is it different from a Map?

WeakMap is a collection of key-value pairs where keys are objects and are held weakly (i.e., if no other references to the key exist, the entry is garbage collected). Map holds keys and values strongly.

Example:

```javascript
let weakMap = new WeakMap();
let obj = {};
weakMap.set(obj, "value");
console.log(weakMap.get(obj)); // value
```

### 26. What is a Set in JavaScript?

A Set is a collection of unique values. It allows you to store and manage unique elements.

Example:

```javascript
let set = new Set([1, 2, 2, 3]);
console.log(set.has(2)); // true
console.log(set.size); // 3
```

### 27. What is Object.create() used for?

Object.create() creates a new object with the specified prototype object and properties.

Example:

```javascript
let proto = {
  greet() {
    console.log("Hello");
  },
};
let obj = Object.create(proto);
obj.greet(); // Hello
```

### 28. How does JavaScript’s garbage collection work?

JavaScript uses automatic garbage collection to manage memory. It identifies and frees memory that is no longer in use or reachable by the application.

### 29. What are "decorators" in JavaScript?

Decorators are a proposal for adding metadata and modifying classes and properties. They provide a way to annotate and modify class declarations and methods.

Example:

```javascript
function readonly(target, key, descriptor) {
  descriptor.writable = false;
  return descriptor;
}

class Example {
  @readonly
  name() {
    return "Name";
  }
}
```

### 30. Explain the difference between prototype and **proto**.

prototype: An object associated with a constructor function, used for inheritance.
**proto**: An internal property that refers to the prototype of the object's constructor.

Example:

```javascript
function Person(name) {
  this.name = name;
}

Person.prototype.sayHi = function () {
  console.log("Hi");
};

let john = new Person("John");
console.log(john.__proto__ === Person.prototype); // true
```

### 31. What is the purpose of Object.assign()?

Object.assign() copies the values of all enumerable properties from one or more source objects to a target object.

Example:

```javascript
let target = { a: 1 };
let source = { b: 2 };
Object.assign(target, source);
console.log(target); // { a: 1, b: 2 }
```

### 32. What are "template literals"?

Template literals are string literals allowing embedded expressions, multi-line strings, and interpolation.

Example:

```javascript
let name = "John";
let greeting = `Hello, ${name}!`;
console.log(greeting); // Hello, John!
```

### 33. What is the spread operator?

The spread operator (...) allows an iterable (e.g., array) to be expanded into individual elements.

Example:

```javascript
let arr = [1, 2, 3];
let newArr = [...arr, 4, 5];
console.log(newArr); // [1, 2,
```

### 34. What is the rest parameter?

The rest parameter (...) allows a function to accept an indefinite number of arguments as an array.

Example:

```javascript
function sum(...numbers) {
  return numbers.reduce((acc, num) => acc + num, 0);
}

console.log(sum(1, 2, 3, 4)); // 10
```

### 35. Explain the for...of loop.

The for...of loop iterates over iterable objects (e.g., arrays, strings) and returns the values of the items.

Example:

```javascript
let arr = [1, 2, 3];
for (let value of arr) {
  console.log(value);
}
// Logs: 1, 2, 3
```

### 36. What are async and await keywords used for?

async and await are used to work with promises more comfortably. async defines a function that returns a promise, and await pauses execution until the promise resolves.

Example:

```javascript
async function fetchData() {
  let data = await new Promise((resolve) => {
    setTimeout(() => resolve("Data received"), 1000);
  });
  console.log(data);
}

fetchData(); // Logs: Data received
```

### 37. What is Symbol used for in JavaScript?

Symbol is a primitive data type used to create unique identifiers for object properties. It ensures that property keys are unique and not susceptible to accidental overwrites.

Example:

```javascript
const uniqueKey = Symbol("key");
let obj = { [uniqueKey]: "value" };
console.log(obj[uniqueKey]); // value
```

### 38. How do you create a class in JavaScript?

Classes are created using the class keyword and can include a constructor and methods.

Example:

```javascript
class Person {
  constructor(name) {
    this.name = name;
  }

  greet() {
    console.log(`Hello, ${this.name}`);
  }
}

let john = new Person("John");
john.greet(); // Hello, John
```

### 39. What is destructuring in JavaScript?

Destructuring allows unpacking values from arrays or properties from objects into distinct variables.

Example:

**Array Destructuring**:

```javascript
let [a, b] = [1, 2];
console.log(a, b); // 1 2
```

**Object Destructuring**:

```javascript
let { x, y } = { x: 1, y: 2 };
console.log(x, y); // 1 2
```

### 40. What is the Proxy object?

The Proxy object enables creation of a handler object that can intercept and redefine fundamental operations for another object (e.g., property access, assignment).

Example:

```javascript
let target = {};
let handler = {
  get: function (target, prop, receiver) {
    return prop in target ? target[prop] : "default";
  },
};

let proxy = new Proxy(target, handler);
console.log(proxy.someProperty); // default
```

## 41. Program to find longest word in a given sentence

Example:
```javascript
function findLongestWord(sentence) {
    let words = sentence.split(' ');
    let longestWord = words.reduce((longest, current) => current.length > longest.length ? current : longest, '');
    return longestWord;
}
console.log(findLongestWord("The quick brown fox jumps over the lazy dog"));

```


## 42. How to check whether a string is palindrome or not?

Example:

```javascript
function isPalindrome(str) {
  let cleaned = str.replace(/[^A-Za-z0-9]/g, "").toLowerCase();
  let reversed = cleaned.split("").reverse().join("");
  return cleaned === reversed;
}
console.log(isPalindrome("A man, a plan, a canal, Panama")); // true
```

## 43. Write a program to remove duplicates from an array.

Example:

```javascript
function removeDuplicates(arr) {
  return [...new Set(arr)];
}
console.log(removeDuplicates([1, 2, 2, 3, 4, 4, 5])); // [1, 2, 3, 4, 5]
```

## 44. Program to find Reverse of a string without using built-in method.

Example:

```javascript
function reverseString(str) {
  let reversed = "";
  for (let i = str.length - 1; i >= 0; i--) {
    reversed += str[i];
  }
  return reversed;
}
console.log(reverseString("hello")); // "olleh"
```

## 45. Find the max count of consecutive 1’s in an array

Example:

```javascript
function maxConsecutiveOnes(arr) {
  let maxCount = 0;
  let currentCount = 0;
  for (let num of arr) {
    if (num === 1) {
      currentCount++;
      maxCount = Math.max(maxCount, currentCount);
    } else {
      currentCount = 0;
    }
  }
  return maxCount;
}
console.log(maxConsecutiveOnes([1, 1, 0, 1, 1, 1, 0, 1])); // 3
```

## 46. Find the factorial of given number

Example:

```javascript
function factorial(n) {
  if (n === 0) return 1;
  return n * factorial(n - 1);
}
console.log(factorial(5)); // 120
```

## 47. Given 2 arrays that are sorted, merge them and sort

Example:

```javascript
function mergeAndSort(arr1, arr2) {
  return [...arr1, ...arr2].sort((a, b) => a - b);
}
console.log(mergeAndSort([0, 3, 4, 31], [4, 6, 30])); // [0, 3, 4, 4, 6, 30, 31]
```

## 48. Create a function to check if every value in arr1 has its corresponding value squared in arr2

Example:

```javascript
function checkSquared(arr1, arr2) {
  if (arr1.length !== arr2.length) return false;
  let freq1 = {};
  let freq2 = {};

  arr1.forEach((num) => (freq1[num] = (freq1[num] || 0) + 1));
  arr2.forEach((num) => (freq2[num] = (freq2[num] || 0) + 1));

  return Object.keys(freq1).every((key) => freq2[key ** 2] === freq1[key]);
}
console.log(checkSquared([1, 2, 3], [1, 4, 9])); // true
```

## 49. Given two strings, find if one string can be formed by rearranging the letters of the other string

Example:

```javascript
function canForm(str1, str2) {
  if (str1.length !== str2.length) return false;
  let sortedStr1 = str1.split("").sort().join("");
  let sortedStr2 = str2.split("").sort().join("");
  return sortedStr1 === sortedStr2;
}
console.log(canForm("listen", "silent")); // true
```

## 50. Write logic to get unique objects from an array

Example:

```javascript
function getUniqueObjects(arr) {
  let seen = new Set();
  return arr.filter((obj) => {
    let key = JSON.stringify(obj);
    if (!seen.has(key)) {
      seen.add(key);
      return true;
    }
    return false;
  });
}
console.log(
  getUniqueObjects([
    { name: "sai" },
    { name: "Nang" },
    { name: "sai" },
    { name: "Nang" },
    { name: "111111" },
  ])
);
// [{name: "sai"}, {name: "Nang"}, {name: "111111"}]
```

## 51. Write a JavaScript program to find the maximum number in an array

Example:

```javascript
function findMax(arr) {
  return Math.max(...arr);
}
console.log(findMax([1, 2, 3, 4, 5])); // 5
```

## 52. Write a JavaScript function that takes an array of numbers and returns a new array with only the even numbers

Example:

```javascript
function filterEvenNumbers(arr) {
  return arr.filter((num) => num % 2 === 0);
}
console.log(filterEvenNumbers([1, 2, 3, 4, 5])); // [2, 4]
```

## 53. Write a JavaScript function to check if a given number is prime

  Example:

```javascript
function isPrime(num) {
  if (num <= 1) return false;
  for (let i = 2; i <= Math.sqrt(num); i++) {
    if (num % i === 0) return false;
  }
  return true;
}
console.log(isPrime(7)); // true
```

## 54. Write a JavaScript program to find the largest element in a nested array

  Example:

```javascript
function findLargestInNestedArray(arr) {
  let flattenArray = arr.flat(Infinity);
  return Math.max(...flattenArray);
}
console.log(
  findLargestInNestedArray([
    [3, 4, 58],
    [709, 8, 9, [10, 11]],
    [111, 2],
  ])
); // 709
```

## 55. Write a JavaScript function that returns the Fibonacci sequence up to a given number of terms

  Example:
  
```javascript
function fibonacci(n) {
  let sequence = [0, 1];
  while (sequence.length < n) {
    let nextTerm =
      sequence[sequence.length - 1] + sequence[sequence.length - 2];
    sequence.push(nextTerm);
  }
  return sequence;
}
console.log(fibonacci(5)); // [0, 1, 1, 2, 3]
```

## 56. Given a string, write a JavaScript function to count the occurrences of each character in the string

Example:

```javascript
function countOccurrences(str) {
  let occurrences = {};
  for (let char of str) {
    occurrences[char] = (occurrences[char] || 0) + 1;
  }
  return occurrences;
}
console.log(countOccurrences("hello")); // {h: 1, e: 1, l: 2, o: 1}
```

## 57. Write a JavaScript function that sorts an array of numbers in ascending order

Example:

```javascript
function sortAscending(arr) {
  return arr.sort((a, b) => a - b);
}
console.log(sortAscending([5, 3, 8, 1, 2])); // [1, 2, 3, 5, 8]
```

## 58. Write a JavaScript function that sorts an array of numbers in descending order

Example:

```javascript
function sortDescending(arr) {
  return arr.sort((a, b) => b - a);
}
console.log(sortDescending([5, 3, 8, 1, 2])); // [8, 5, 3, 2, 1]
```

## 59. Write a JavaScript function that reverses the order of words in a sentence without using the built-in reverse() method

Example:

```javascript
function reverseWords(sentence) {
  let words = sentence.split(" ");
  let reversedSentence = "";
  for (let i = words.length - 1; i >= 0; i--) {
    reversedSentence += words[i] + " ";
  }
  return reversedSentence.trim();
}
console.log(reverseWords("Hello world")); // "world Hello"
```

## 60. Implement a JavaScript function that flattens a nested array into a single-dimensional array

Example:

  ```javascript
        function flattenArray(arr) {
        return arr.flat(Infinity);

    }
    console.log(flattenArray([[1, 2, [3]], [4, [5, [6]]]])); // [1, 2, 3, 4, 5, 6]
```


-------------------------------------------------------------------------------------------------------------------------------------------

  # React Questions & Answers 

-----------------------------------------------------------------------------------------------------------------------------------------------



### 1. What is React

React is a JavaScript library for building user interfaces, specifically for single-page applications. It allows developers to create reusable UI components.

**Example:**

```jsx
import React from "react";

function App() {
  return <h1>Hello, World!</h1>;
}

export default App;
```

### 2. What is useMemo

useMemo is a React hook that memoizes the result of a computation to avoid expensive recalculations on every render unless its dependencies change.

**Example:**

```jsx
import React, { useMemo } from "react";

function Example({ number }) {
  const computedValue = useMemo(() => {
    return number * 2;
  }, [number]);

  return <div>{computedValue}</div>;
}
```

### 3. What are the features of React

- Component-based architecture
- Virtual DOM
- One-way data binding
- JSX (JavaScript XML)

**Example:**

```jsx
import React from "react";

function Header() {
  return <header>This is a header</header>;
}

function App() {
  return (
    <div>
      <Header />
      <p>This is the body</p>
    </div>
  );
}

export default App;
```

### 4. What is JSX

JSX is a syntax extension for JavaScript that allows you to write HTML elements in JavaScript.

**Example:**

```jsx
const element = <h1>Hello, World!</h1>;
```

### 5. What is DOM

The DOM (Document Object Model) represents the structure of a web document as a tree of objects.

Example (in the browser):

```html
<!DOCTYPE html>
<html>
  <body>
    <div id="app"></div>
    <script>
      document.getElementById("app").innerText = "Hello, World!";
    </script>
  </body>
</html>
```

### 6. What is Virtual DOM?

The Virtual DOM is an in-memory representation of the real DOM, used by React to optimize updates by re-rendering only the changed parts of the DOM.

**Example:**

```jsx
const element = <h1>Hello, World!</h1>;
ReactDOM.render(element, document.getElementById("root"));
```

### 7. What is the component life cycle of React class component

The lifecycle includes:

- Mounting: constructor(), render(), componentDidMount()
- Updating: componentDidUpdate()
- Unmounting: componentWillUnmount()

**Example:**

```jsx
class MyComponent extends React.Component {
  componentDidMount() {
    console.log("Component Mounted");
  }

  render() {
    return <div>Life Cycle</div>;
  }
}
```

### 8. What are fragments in React

Fragments let you group a list of children without adding extra nodes to the DOM.

**Example:**

```jsx
import React from "react";

function FragmentExample() {
  return (
    <>
      <h1>Title</h1>
      <p>Description</p>
    </>
  );
}
```

### 9. What are props in React

Props are read-only attributes passed from a parent component to a child component.

**Example:**

```jsx
function Greeting(props) {
  return <h1>Hello, {props.name}</h1>;
}
```

### 10. What are synthetic events in React

   Synthetic events are React's cross-browser wrapper around the browser's native events.

**Example:**

```jsx
function Button() {
  const handleClick = (event) => {
    console.log("Button clicked", event);
  };

  return <button onClick={handleClick}>Click me</button>;
}
```

### 11. What is the difference between package.json and package-lock.json

- package.json: Lists project dependencies.
- package-lock.json: Records the exact versions of installed dependencies.

### 12. What are the differences between client-side and server-side rendering

- Client-side rendering: The content is rendered in the browser using JavaScript.
- Server-side rendering: Content is rendered on the server and sent as a fully-rendered page.

### 13. What is state in ReactJS

   State is an object that holds dynamic data within a component. When the state changes, the component re-renders.

**Example:**

```jsx
import React, { useState } from "react";

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <button onClick={() => setCount(count + 1)}>Increment</button>
      <p>Count: {count}</p>
    </div>
  );
}
```

### 14. What are props

   Props are used to pass data from a parent component to a child component.

**Example:**

```jsx
function Child(props) {
  return <p>{props.message}</p>;
}

function Parent() {
  return <Child message="Hello from Parent" />;
}
```

### 15. What are the differences between state and props in React

- State: Local to a component, can be changed.
- Props: Passed from parent to child, read-only.

### 16. What is props drilling

- Props drilling is the process of passing props down through multiple levels of components, - even if intermediate components don't need the data.

### 17. What are the disadvantages of props drilling and how can we avoid it

- Disadvantages: Leads to tightly coupled components.
- Solution: Use React Context API or state management libraries like Redux.

### 18. What are Pure components in React

   Pure components in React are components that perform a shallow comparison of props and state to avoid unnecessary re-renders.

**Example:**

```jsx
class MyPureComponent extends React.PureComponent {
  render() {
    return <div>{this.props.name}</div>;
  }
}
```

### 19. What are Refs in React

   Refs provide a way to access the DOM elements or React components directly.

**Example:**

```jsx
import React, { useRef } from "react";

function InputComponent() {
  const inputRef = useRef();

  const focusInput = () => {
    inputRef.current.focus();
  };

  return (
    <div>
      <input ref={inputRef} />
      <button onClick={focusInput}>Focus Input</button>
    </div>
  );
}
```

### 20. What is meant by forward ref

   forwardRef is a technique to pass refs from a parent to a child component.

**Example:**

```jsx
const FancyInput = React.forwardRef((props, ref) => <input ref={ref} />);
```

### 21. What are Error boundaries

   Error boundaries catch JavaScript errors in child components and display a fallback UI.

**Example:**

```jsx
class ErrorBoundary extends React.Component {
  constructor(props) {
    super(props);
    this.state = { hasError: false };
  }

  componentDidCatch(error, info) {
    this.setState({ hasError: true });
  }

  render() {
    if (this.state.hasError) {
      return <h1>Something went wrong.</h1>;
    }

    return this.props.children;
  }
}
```

### 22. What are Higher Order Components in React

   A Higher Order Component (HOC) is a function that takes a component and returns a new component with added functionality.

**Example:**

```jsx
function withLogger(WrappedComponent) {
  return function (props) {
    console.log("Component rendered");
    return <WrappedComponent {...props} />;
  };
}
```

### 23. What are the differences between controlled and uncontrolled components

- Controlled components: Form data is handled by React state.
- Uncontrolled components: Form data is handled by the DOM.

### 24. What is useCallback

   useCallback is a hook that memoizes a function to prevent it from being recreated on every render unless its dependencies change.

**Example:**

```jsx
import React, { useCallback, useState } from "react";

function Counter() {
  const [count, setCount] = useState(0);

  const increment = useCallback(() => setCount(count + 1), [count]);

  return <button onClick={increment}>Increment</button>;
}
```

### 25. What are the differences between useMemo and useCallback

- useMemo: Memoizes the result of a computation.
- useCallback: Memoizes the function itself.

### 26. What are keys in React

   Keys help React identify which items have changed, been added, or removed.

**Example:**

```jsx
const list = ["Apple", "Banana", "Cherry"];
const items = list.map((item, index) => <li key={index}>{item}</li>);
```

### 27. What is lazy loading in React

   Lazy loading is the technique of loading components or resources only when they are needed.

**Example:**

```jsx
const LazyComponent = React.lazy(() => import("./LazyComponent"));

function App() {
  return (
    <React.Suspense fallback={<div>Loading...</div>}>
      <LazyComponent />
    </React.Suspense>
  );
}
```

### 28. What is suspense in React

   Suspense is a component that allows for delaying the rendering of a component until some condition (like data fetching) is met.

**Example:**

```jsx
<React.Suspense fallback={<div>Loading...</div>}>
  <LazyComponent />
</React.Suspense>
```

### 29. What are custom hooks

   Custom hooks are reusable functions that allow you to share logic between components.

**Example:**

```jsx
function useCounter(initialValue = 0) {
  const [count, setCount] = React.useState(initialValue);

  const increment = () => setCount(count + 1);
  const decrement = () => setCount(count - 1);

  return { count, increment, decrement };
}
```

### 30. What is the useReducer hook

   useReducer is a hook that is used to manage more complex state logic compared to useState.

**Example:**

```jsx
function reducer(state, action) {
  switch (action.type) {
    case "increment":
      return { count: state.count + 1 };
    case "decrement":
      return { count: state.count - 1 };
    default:
      return state;
  }
}

function Counter() {
  const [state, dispatch] = useReducer(reducer, { count: 0 });

  return (
    <>
      <button onClick={() => dispatch({ type: "decrement" })}>-</button>
      <span>{state.count}</span>
      <button onClick={() => dispatch({ type: "increment" })}>+</button>
    </>
  );
}
```

### 31. What are Portals in React

   Portals allow rendering components outside their parent DOM hierarchy.

**Example:**

```jsx
ReactDOM.createPortal(<Child />, document.getElementById("modal-root"));
```

### 32. What is context in React

   The Context API allows you to pass data through the component tree without passing props manually at every level.

**Example:**

```jsx
const ThemeContext = React.createContext("light");

function App() {
  return (
    <ThemeContext.Provider value="dark">
      <Toolbar />
    </ThemeContext.Provider>
  );
}

function Toolbar() {
  return <ThemedButton />;
}

function ThemedButton() {
  const theme = React.useContext(ThemeContext);
  return <button style={{ background: theme }}>Click me</button>;
}
```

### 33. Practical question: Give an example of Context API usage

- See the answer for the Context API example above.

### 34. What is the purpose of callback function as an argument of setState()

   The callback function in setState ensures that state updates are processed before executing further logic.

**Example:**

```jsx
this.setState({ count: this.state.count + 1 }, () => {
  console.log("State updated!");
});
```

### 35. Practical question Create a custom hook for increment/decrement counter

- See the example in the custom hook question above.

### 36. which lifecycle hooks are replaced by useeffectnents

   useEffect replaces componentDidMount, componentDidUpdate, and componentWillUnmount.

**Example:**

```jsx
useEffect(() => {
  console.log("Component mounted");
  return () => console.log("Component unmounted");
}, []);
```

### 37. What is Strict Mode in React

   Strict Mode is a tool that highlights potential problems in an application by identifying unsafe lifecycle methods or deprecated APIs.

**Example:**

```jsx
<React.StrictMode>
  <App />
</React.StrictMode>
```

### 38.  ways to pass data from child to parent in react

- Using a callback function.
- Using useRef.
- Context API.

### 39. how to send data from child to parent using callback functions

**Example:**

```jsx
function Parent() {
  const handleData = (data) => {
    console.log(data);
  };

  return <Child sendData={handleData} />;
}

function Child({ sendData }) {
  return (
    <button onClick={() => sendData("Hello from Child")}>Send Data</button>
  );
}
```

### 40. how to send data from child to parent using useref

**Example:**

```jsx
function Parent() {
  const childRef = React.useRef();

  const handleClick = () => {
    alert(childRef.current.value);
  };

  return (
    <div>
      <Child ref={childRef} />
      <button onClick={handleClick}>Get Child Value</button>
    </div>
  );
}

const Child = React.forwardRef((props, ref) => {
  return <input ref={ref} type="text" />;
});
```












