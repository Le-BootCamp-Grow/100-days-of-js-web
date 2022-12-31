# 100 days of JavaScript web development

## Day 1: Introduction to JavaScript and the web development ecosystem

Welcome to the first day of our 100 days of JavaScript web developer bootcamp! Today, we will be covering the basics of JavaScript and the web development ecosystem. We will start by setting up a development environment, then move on to understanding the role of JavaScript in web development. Finally, we will cover the basic syntax and data types in JavaScript.

### Setting up a development environment

Before we can start coding in JavaScript, we need to set up a development environment. This includes installing a text editor and a web browser. A text editor is a program that allows us to write and edit code. Some popular options include Sublime Text, Atom, and Visual Studio Code. A web browser is a program that allows us to view and interact with web pages. Some popular options include Google Chrome, Mozilla Firefox, and Safari.

Once you have a text editor and web browser installed, you are ready to start coding in JavaScript!

To set up your development environment, you will need to install a text editor and a web browser. In this lesson, we will be using Visual Studio Code (VS Code) as our text editor and Google Chrome as our web browser.

Follow these steps to install and set up VS Code:

1.  Go to the VS Code website: https://code.visualstudio.com/
2.  Click on the "Download" button for your operating system (Windows, macOS, or Linux).
3.  Once the download is complete, open the downloaded file and follow the prompts to install VS Code.
4.  Once the installation is complete, open VS Code by double-clicking the icon on your desktop or in your start menu.

Follow these steps to install and set up Google Chrome:

1.  Go to the Google Chrome website: https://www.google.com/chrome/
2.  Click on the "Download Chrome" button.
3.  Once the download is complete, open the downloaded file and follow the prompts to install Google Chrome.
4.  Once the installation is complete, open Google Chrome by double-clicking the icon on your desktop or in your start menu.

You are now ready to start coding in JavaScript! 

To create a new file in VS Code, click on the "File" menu and then select "New File". You can then type your code into the editor and save the file by clicking on the "File" menu and selecting "Save". To view the results of your code, open the saved file in Google Chrome by dragging and dropping it into the browser window. Don't worry if you can't find your way around this yet. You'll get familiar with things as we go through the program.

### Understanding the role of JavaScript in web development

JavaScript is a programming language that is primarily used for building interactive web applications. It is often used in conjunction with HTML and CSS to create dynamic, interactive web pages.

JavaScript is typically run in the user's web browser, which means that it can be used to create interactive elements on a web page such as drop-down menus, pop-up windows, and responsive forms. It is also used to add functionality to web pages, such as the ability to validate form input, create animations, and send and receive data from a server.

As a programming language, JavaScript allows developers to build interactive and dynamic websites and web applications. It is an essential tool for front-end web development, as it enables developers to create interactive and responsive elements on a web page.

JavaScript is also used for back-end development, using technologies such as Node.js. This allows developers to use JavaScript to build server-side applications and APIs (Application Programming Interfaces), which can be accessed by client-side applications such as web and mobile apps.

JavaScript has a large and active community of developers, with many libraries and frameworks available to help developers build web applications more efficiently. Some popular libraries and frameworks include React, Angular, and Vue.js.

In addition to its use in web development, JavaScript can also be used to build desktop and mobile applications using technologies such as Electron and Cordova.

Overall, JavaScript plays a crucial role in the development of modern web and mobile applications, and is an essential skill for any web developer to master.

### Basic syntax and data types in JavaScript:

Now that we have a basic understanding of the role of JavaScript in web development, let's take a look at the basic syntax and data types in the language.

JavaScript uses a C-style syntax, which means that it uses curly braces to enclose blocks of code and semicolons to mark the end of a statement.

JavaScript has a number of data types, including strings, numbers, booleans, and objects.

Strings are used to represent text and are enclosed in single or double quotes. For example:

```JavaScript
let name = "Charlie";
let message = 'Hello, world!';
```

Numbers can be integers or floating point values. For example:

```JavaScript
let age = 35;
let temperature = 72.5
let pi = 3.14159;
```

Booleans represent true or false values. For example:

```JavaScript
let isValid = true;
let isOld = false;
let isExpired = false;
```
Objects are collections of key-value pairs and are used to store complex data. For example:

```JavaScript
let person = {
  name: "John",
  age: 35,
  isMale: true
};
```

Let's look more into what coding in JavaScript looks like.

Here is an example of a simple function in JavaScript:

```Javascript
function greet(name) {
  console.log("Hello, " + name + "! Nice to meet you!");
}

greet("Paula"); // Output: "Hello, Paula! Nice to meet you!"
```

In this example, the greet function takes in a single parameter, name, and logs a greeting message to the console. The function is then called with the argument "Paula", which results in the output "Hello, Paula! Nice to meet you!".

Here are some examples of working with strings in JavaScript:

```Javascript
let firstName = "Mickey";
let lastName = "Mouse";

console.log(firstName + " " + lastName); // Output: "Mickey Mouse"

console.log(firstName.length); // Output: 6

console.log(lastName.toUpperCase()); // Output: "MOUSE"

console.log(firstName.startsWith("M")); // Output: true

let welcome = "Welcome to the 100 days of JavaScript developer bootcamp."
let welcomeNote = "Hi, Mr" + firstName + " " + lastName.toUpperCase() + "! " + welcome

console.log (welcomeNote); 
//Output: Hi, Mr Mickey MOUSE! Welcome to the 100 days of JavaScript developer bootcamp.
```

In this example, we declare two variables at first, `firstName` and `lastName`, and assign them string values. We then use string concatenation to combine the two variables and log the result to the console. We also use the `length` property to get the length of the `firstName` string, the `toUpperCase` method to convert the string to uppercase, and the `startsWith` method to check if the string starts with a particular letter. 

Further on, we declare two variables, `welcome` and `welcomeNote`. We assign a string value representing a welcome greeting to the first? Then we create a complete welcome note with the letter by using string concatenation to combine the three variables previously declared. In the end, we log the result to the console.

Here are some examples of working with numbers in JavaScript:

```JavaScript
let x = 5;
let y = 2.5;

console.log(x + y); // Output: 7.5

console.log(x - y); // Output: 2.5

console.log(x * y); // Output: 12.5

console.log(x / y); // Output: 2

let pi  = 3.14159;
let r = y;
let areaOfCircle = pi * r * r;

console.log(areaOfCircle); //19.6349375
```

In this example, we declare two variables, `x` and `y`, and assign them numeric values. We then use arithmetic operators to perform basic calculations with these variables and log the results to the console. Further on, we declare three new variables, `pi`, `r` and `areaOfCircle`. We assign `r` the value of `y` and assign `areaOfCircle` the formula for finding the area of a circle using arithmetic operators to perform basic calculations with variables `pi` and `r`. Then we log the end result to the console.

Here are some examples of working with objects in JavaScript:

```Javascript
let person = {
  firstName: "Mickey",
  lastName: "Mouse",
  age: 35,
  isMale: true
};

console.log(person.firstName); // Output: "Mickey"

console.log(person["lastName"]); // Output: "Mouse"

person.age = 36;

console.log(person.age); // Output: 36

delete person.isMale;

console.log(person.isMale); // Output: undefined
```

In this example, we declare a variable `person` and assign it an object value with four properties: `firstName`, `lastName`, `age`, and `isMale`. We access the properties of the object using dot notation (e.g. `person.firstName`) or bracket notation (e.g. `person["lastName"]`). We can also modify the properties of the object by assigning them new values (e.g. `person.age = 36`) or delete them using the delete operator (e.g. `delete person.isMale`).

That concludes our introduction to JavaScript and the web development ecosystem. In the next lesson, we will dive deeper into the language and start learning about its fundamental concepts such as variables and controlstructures.

> Remember to play around with the code samples provided to get a better understanding of these concepts.