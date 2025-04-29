## 📘 JavaScript Cheatsheet

```javascript
// let
// Declares a block-scoped variable that can be reassigned.
let count = 1;
count = 2;

// const
// Declares a block-scoped constant that cannot be reassigned.
const PI = 3.14;

// array
// A data structure used to store multiple values in a single variable, indexed by position.
const colors = ["red", "green", "blue"];

// function
// A reusable block of code that performs a specific task and can return a value.
function greet(name) {
  return "Hello, " + name;
}

// for loop
for (let i = 0; i < 3; i++) {
  console.log(i);
}

// while loop
let i = 0;
while (i < 3) {
  console.log(i);
  i++;
}

// if statement
let score = 80;
if (score > 70) {
  console.log("Passed");
}

// push
colors.push("yellow");

// shift
let firstColor = colors.shift();

// unshift
colors.unshift("purple");
