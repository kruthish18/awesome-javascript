# awesome-javascript-concepts

## 📚 Table of Contents

1. [Introduction to JavaScript](#1-introduction-to-javascript)
2. [Syntax](#2-syntax)
3. [Variables](#3-variables)
4. [If Conditions](#4-if-conditions)
5. [Loops](#5-loops)
6. [Functions](#6-functions)

---

## 1. Introduction to JavaScript

### What is JavaScript?
JavaScript is a programming language used primarily to create interactive effects within web browsers.

### Why Learn JavaScript?
- Runs in all modern browsers
- Core language for web development (HTML + CSS + JS)
- Powers frontend frameworks like React, Angular, Vue
- Can be used on the server (Node.js)

---

## 2. Syntax

### Statements & Semicolons
JavaScript code is made up of **statements**. Each statement performs an action and ends with a semicolon (`;`), although semicolons are optional.

```js
let x = 5;
let y = 10;
console.log(x + y);
```

### Case Sensitivity

JavaScript is case-sensitive:
```js
let name = "Kruthi";
let Name = "Hegde"; // Different variable!
```

### Comments

Single-line:
```js
// This is a comment
```

Multi-line:
```js
/* This is
   a multi-line comment */
```

## 3. Variables

### Declaring Variables

Use let, const, or var:

```
let age = 25;
const name = "Kruthi";
var city = "Boston";
```

### var vs let vs const

| Keyword | Scope | Reassignable | Hoisted |
| --- | --- | --- | --- |
| var | Function | ✅ Yes | ✅ Yes |
| let | Block | ✅ Yes | ❌ No |
| const | Block | ❌ No | ❌ No |


4\. If Conditions
-----------------

### Basic If Statement

```
if (true) {
  console.log("This runs");
}
```

### if...else

```
let age = 18;
if (age>=18) {
   console.log("Adult");
}
else {
console.log("Minor");
}
```

### if...else if...else

```
let score = 85;
if (score > 90) {
  console.log("Excellent");
} else if (score > 70) {
  console.log("Good");
} else {
  console.log("Needs Improvement");
}
```

---

5\. Loops
---------

### for loop

```
for (let i = 0; i < 5; i++) {
  console.log(i);
}
```

### while loop

```
let i = 0;
while (i < 5) {
  console.log(i);
  i++;
}
```

### do...while loop

```
let i = 0;
do {
  console.log(i);
  i++;
} while (i < 5);
```

### for...of

```
const fruits = ["apple", "banana", "cherry"];
for (let fruit of fruits) {
  console.log(fruit);
}
```

---

6\. Functions
-------------

### Function Declaration

```
function greet(name) {
  return `Hello, ${name}!`;
}
console.log(greet("Kruthi"));
```

### Function Expression

```
const greet = function(name) {
  return `Hello, ${name}!`;
};
```

### Arrow Functions

```
const greet = (name) => `Hello, ${name}!`;
```

### Parameters & Return Values

-   Functions can take any number of parameters

-   They return a value using `return`
