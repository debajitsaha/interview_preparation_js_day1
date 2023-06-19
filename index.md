## Q1. Difference between “ == “ and “ === “ operators.
    " == "is comapare the  value and "===" is compare the value and datatype also
 Example:- let a = 20;
let b = "20";

console.log(typeof(a));
console.log(typeof(b));

console.log(a == b); 
console.log(a === b);
### OUTPUT:
number
string
true
false
## Q2. What are the differences between var, let and const?

### var - 
    1. Redeclare and reinitilized
    2. Global scope and Function Scope
    3. Hoisting
    4. Used before introduce ES6
Example:var x = 10;
var x = 20; 
x = 30;

### let
    1. not Redeclare and reinitilized
    2. no Hoisting
    3. Block scope, Global Scope
    4. TDZ
    5. introduce in ES6
### const
    1. not Redeclare and Not reinitilized 
    2. no Hoisting
    3. Block scope, Global Scope
    4. TDZ
    5. introduce in ES6

## Type of Scope
1. Global Scope
2. Function Scope
3. Block Scope

## Q3. Hoisting - Hoisting is the js mechanism where var and function declaration are moved to top of their scope before code execution.
    1. function Hoisting
    2. var keyword Hoisting
## Q4. What is a Temporal Dead Zone (TDZ)?
    - when trying to acceess a variable before it's decleration with let and const keyword.
    - introduce to imporve the code quality by detecting & preventing to use variable.
## Q5. What is meant by first class functions?
    - Assign a function to a variable is first class function.
## Q6 . Pure Function - A pure function in JavaScript is a function that returns the same result if the same arguments(input) are passed in the function.
---
## Q7. Execution Context

    - This is for Synchronous JavaScript
    1. Global Execution Context
    2. Function Execution context
    3. Memory Allocation
    4. Code Execution 
    5. Call Stack
    - Asynchronous JavaScript
    1. Event Loop
    2. Callback queue
    3. Call Stack