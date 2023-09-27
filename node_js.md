**Advanced JavaScript Concepts Evaluation Test**

**Instructions:** Select the most appropriate option for each question. Each question is worth one point.

**Section 1: Core JavaScript Concepts**

1. What will be the output of the following code?

```javascript
console.log(typeof null);
```

   a) "undefined"
   b) "null"
   c) "object"
   d) "string"

2. Given the code:

```javascript
let x = 5;
let y = '10';
console.log(x + y);
```

   What will be the output?

   a) 15
   b) "510"
   c) "15"
   d) NaN

3. Which of the following is not a valid JavaScript operator?

   a) +
   b) --
   c) **
   d) <>

4. What does the "hoisting" concept in JavaScript refer to?

   a) The process of converting a function into an object
   b) The automatic movement of variable and function declarations to the top of their containing scope during compilation
   c) The process of compressing JavaScript files for faster loading
   d) The way JavaScript handles errors in the code

**Section 2: Object-Oriented Programming (OOPs) Concepts**

5. In OOP, what is encapsulation?

   a) The process of making methods private
   b) The process of bundling data and methods that operate on that data into a single unit
   c) The process of inheriting properties and methods from one class to another
   d) The process of creating objects from a class

6. What is the main advantage of using inheritance in OOP?

   a) Reducing code duplication and promoting code reusability
   b) Enforcing encapsulation
   c) Simplifying complex data structures
   d) Ensuring strong typing

7. Which OOP principle is violated when a subclass cannot provide a complete implementation of a method declared in its superclass?

   a) Abstraction
   b) Inheritance
   c) Polymorphism
   d) Encapsulation

8. What is the purpose of the "this" keyword in JavaScript?

   a) To reference the current object or instance
   b) To declare a variable
   c) To create a new object
   d) To access a global variable

**Section 3: Algorithmic & Functional Understanding**

9. What is the time complexity of a binary search algorithm?

   a) O(1)
   b) O(n)
   c) O(log n)
   d) O(n log n)

10. Which higher-order function in JavaScript is used to apply a function against an accumulator and each element in an array to reduce it to a single value?

   a) forEach
   b) map
   c) filter
   d) reduce

11. What is a closure in JavaScript?

   a) A way to hide data from external access
   b) A function that has access to variables from its outer function even after the outer function has finished executing
   c) A type of loop used for iteration
   d) A JavaScript data type

12. What does the "callback hell" refer to in JavaScript?

   a) A situation where multiple asynchronous operations are nested inside each other, leading to unreadable and hard-to-maintain code
   b) A naming convention for variables in JavaScript
   c) A debugging technique for handling errors
   d) A design pattern for organizing code

**Section 4: Program Outputs**

For the following questions, consider the code provided and determine the output.

13. What will be the output of the following code?

```javascript
let x = 10;

function foo() {
  console.log(x);
}

function bar() {
  let x = 20;
  foo();
}

bar();
```

   a) 10
   b) 20
   c) undefined
   d) ReferenceError

14. What will be the output of the following code?

```javascript
const arr = [1, 2, 3];

for (let i = 0; i < arr.length; i++) {
  setTimeout(() => console.log(arr[i]), 1000);
}
```

   a) 1 2 3
   b) undefined undefined undefined
   c) 3 3 3
   d) 1 1 1

15. What will be the output of the following code?

```javascript
const arr = [1, 2, 3];

function processArray(arr) {
  arr.forEach(function (num) {
    console.log(num);
  });
  arr[0] = 10;
}

processArray(arr);
console.log(arr[0]);
```

   a) 1 2 3 10
   b) 10 2 3 10
   c) 10 2 3 1
   d) 1 2 3 1

16. What will be the output of the following code?

```javascript
const x = 1;
const y = '1';

console.log(x == y);
console.log(x === y);
```

   a) true false
   b) true true
   c) false false
   d) false true

**Section 5: Program Outputs**

17. What will be the output of the following code?

```javascript
function greet(name) {
  console.log(`Hello, ${name}!`);
}

const sayHello = greet;
sayHello("Alice");
```

   a) "Hello, Alice!"
   b) "Hello, undefined!"
   c) ReferenceError
   d) TypeError

18. What will be the output of the following code?

```javascript
function add(x, y) {
  return x + y;
}

const result = add(5);
console.log(result);
```

   a) 5
   b) NaN
   c) undefined
   d) ReferenceError

19. What will be the output of the following code?

```javascript
const numbers = [1, 2, 3, 4];
const sum = numbers.reduce((acc, current) => acc + current, 0);
console.log(sum);
```

   a) 10
   b) [1, 2, 3, 4]
   c) 0
   d) 1234

20. What will be the output of the following code?

```javascript
const foo = () => console.log("Hello from foo");
const bar = () => console.log("Hello from bar");

setTimeout(foo, 0);
console.log("End of script");
bar();
```

   a) "Hello from foo" "Hello from bar" "End of script"
   b) "Hello from foo" "End of script" "Hello from bar"
   c) "End of script" "Hello from foo" "Hello from bar"
   d) "End of script" "Hello from foo"
