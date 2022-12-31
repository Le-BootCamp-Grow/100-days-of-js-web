# 100 days of JavaScript web development

## Day 2: Variables and control structures

Declaring and assigning variables in JavaScript allows us to store data in memory so that we can use it in our code. There are a few different ways to declare variables in JavaScript, which we will cover in this section.

### Declaring variables

In JavaScript, we can use the `var` keyword to declare a variable. For example:

```Javascript
var myVariable;
```

We can also assign a value to the variable at the same time as declaring it:

```Javascript
var myVariable = 'hello';
var myAge = 19;
```

In addition to `var`, there are two other ways to declare variables in JavaScript: `let` and `const`. The difference between `let` and `var` is that let is block-scoped, meaning that it is only accessible within the block of code in which it is defined. `const` is similar to `let`, but the value of a `const` variable cannot be reassigned.

Here's an example using `let`:

```Javascript
let myVariable = 'hello';
let digit = 1234;
let coefficient = 'c';
```

And here's an example using `const`:

```Javascript
const myVariable = 'hello';
const MAX_VALUE = 9999;
```

It's generally a good idea to use const whenever possible, and only use let when you need to reassign a value to a variable.

### Assigning variables
Once we have declared a variable, we can assign a new value to it using the assignment operator `=`. For example:

```Javascript
let myVariable = 'Hello';
myVariable = 'Hello world';
```

In this example, we first assign the value 'Hello' to the `myVariable` variable. Then, we reassign the value 'Hello world' to `myVariable`.

We can also use variables to store the result of an expression. For example:

```Javascript
let x = 5;
let y = 6;
let z = x + y;
let squareOfZ = z * z;
```

In this example, `z` will be assigned the value 11 (5 + 6), and `squareOfZ` will be assigned the calue of 121 (11 * 11).

### Naming variables

It's important to choose descriptive and meaningful names for your variables. This will make your code easier to read and understand. There are a few rules to follow when naming variables in JavaScript:

- Variable names can only contain letters, digits, and underscores. They cannot start with a digit.
- Variable names are case-sensitive.
- Variable names cannot be the same as a JavaScript keyword.

Here are some examples of valid variable names:

```Javascript
let myVariable;
let my_variable;
let myVariable123;
```

And here are some examples of invalid variable names:

```Javascript
let 123myVariable; // cannot start with a digit
let my-variable; // cannot contain hyphens
let while; // cannot be a JavaScript keyword
```


Now that we've covered declaring and assigning variables in JavaScript, let's move on to debugging control structures.

### Debugging control structures

Control structures are blocks of code that allow us to control the flow of our program. They allow us to execute different sections of code depending on certain conditions, or to repeat a section of code multiple times.

The three most common control structures in JavaScript are `if-else` statements, `for` loops, and `while` loops.

### `if-else` statements

`if-else` statements allow us to execute different sections of code depending on whether a certain condition is true or false.

Here's an example of an `if-else` statement:

```Javascript
let x = 5;

if (x > 10) {
  console.log('x is greater than 10');
} else {
  console.log('x is not greater than 10');
}
```

In this example, the condition `x > 10` is checked. If it is true, the code in the first block `(console.log('x is greater than 10'))` will be executed. If it is false, the code in the second block `(console.log('x is not greater than 10'))` will be executed instead.

We can also include additional `else if` clauses to check for multiple conditions:

```Javascript
let x = 5;

if (x > 10) {
  console.log('x is greater than 10');
} else if (x < 5) {
  console.log('x is less than 5');
} else {
  console.log('x is between 5 and 10');
}
```

In this example, the condition `x > 10` is checked first. If it is true, the first block of code is executed. If it is false, the condition `x < 5` is checked. If this is true, the second block of code is executed. If both conditions are false, the code in the final else block is executed.

### `for` loops

`for` loops allow us to repeat a block of code a specific number of times. They have the following structure:

```Javascript
for (initialization; condition; increment) {
  // code to be executed
}
```

The initialization statement is executed before the loop starts. It is usually used to declare and initialize a counter variable. The condition is checked before each iteration of the loop. If the condition is true, the code in the loop is executed. If the condition is false, the loop is stopped. The increment statement is executed after each iteration of the loop. It is usually used to update the counter variable.

Here's an example of a `for` loop that counts from 1 to 10:

```Javascript
for (let i = 1; i <= 10; i++) {
  console.log(i);
}
```

In this example, the variable `i` is initialized to 1. The condition `i <= 10` is checked before each iteration of the loop. If it is true, the code in the loop is executed `(console.log(i))`. After each iteration, `i` is incremented by 1. This continues until `i` is greater than 10, at which point the loop is stopped.

### `while` loops

`while` loops are similar to for loops, but they do not have a fixed number of iterations. They have the following structure:

```Javascript
while (condition) {
  // code to be executed
}
```

The condition is checked before each iteration of the loop. If the condition is true, the code in the loop is executed. If the condition is false, the loop is stopped.

It's important to make sure that the condition will eventually become false, otherwise the loop will run indefinitely (this is known as an infinite loop).

Here's an example of a `while` loop that counts from 1 to 10:

```Javascript
let i = 1;

while (i <= 10) {
  console.log(i);
  i++;
}
```

In this example, the variable `i` is initialized to 1. The condition `i <= 10` is checked before each iteration of the loop. If it is true, the code in the loop is executed (`console.log(i)`) and `i` is incremented by 1. This continues until `i` is greater than 10, at which point the loop is stopped.

### Debugging techniques in JavaScript

Debugging is the process of identifying and fixing errors in your code. JavaScript provides a number of tools and techniques to help you debug your code.

`console.log()`

One of the most basic and useful debugging techniques is to use the `console.log()` function to print out the values of variables and expressions. This allows you to see what's happening at different points in your code and can help you identify where errors are occurring.

For example:


```Javascript
let x = 50;
let y = 100;
let z = x + y;

console.log(z); // prints 15
```

### The JavaScript console

The JavaScript console is a command-line interface provided by most modern web browsers. It allows you to execute JavaScript code and see the output in real-time.

To open the JavaScript console in most browsers, you can use the keyboard shortcut `Ctrl + Shift + J` (on Windows) or `Cmd + Option + J` (on macOS).

In the console, you can enter JavaScript code and press **Enter** to execute it. You can also use the console.log() function to print out the values of variables and expressions.

### Debugging tools

Most modern web browsers also provide built-in debugging tools that allow you to inspect the HTML and JavaScript of a web page and set breakpoints in your code. These tools can be accessed through the browser's developer console.

Most modern web browsers also provide built-in debugging tools that allow you to inspect the HTML and JavaScript of a web page and set breakpoints in your code. These tools can be accessed through the browser's developer console.

To open the developer console in most browsers, you can use the keyboard shortcut `Ctrl + Shift + I` (on Windows) or `Cmd + Option + I` (on macOS).

These tools allow you to inspect the HTML and JavaScript of a web page, view the values of variables and expressions, and set breakpoints in your code. When a breakpoint is reached, the execution of your code is paused, allowing you to examine the state of your variables and see what's happening at that point in your code.

### Debugging strategies

When debugging your code, it's important to approach the problem systematically and carefully. Here are a few strategies that can help:

-   Start by identifying the error message. This can give you a clue as to what's going wrong.
-   Use console.log() statements to print out the values of variables and expressions at different points in your code
-   Use the debugging tools provided by your browser to inspect the HTML and JavaScript of your web page and set breakpoints in your code.
-   Break your code down into smaller pieces and test each piece individually to narrow down the location of the error.
-   Read through your code carefully and look for typos, syntax errors, or logical errors.
-   Don't be afraid to ask for help or seek advice from other developers.
-   Debugging can be a challenging but rewarding process, and it's an important skill for any developer to have. With practice and patience, you'll get better at identifying and fixing errors in your code.