# What is Javascript?

- Javascript is a programming language that is used to make web pages interactive. It is a scripting language that is used to create and control dynamic website content, i.e. anything that moves, refreshes, or otherwise changes on your screen without requiring you to manually reload a web page.

- Javascript is a client-side programming language, which means it runs on your computer, in your browser. This is different from server-side languages like PHP, which run on the server.

- JavaScript is a dynamic, weakly typed programming language which is compiled at
  runtime. It can be executed as part of a webpage in a browser or directly on any
  machine (“host environment”)

- JavaScript was created to make webpages more dynamic (e.g. change content on a
  page directly from inside the browser). Originally, it was called LiveScript but due to
  the popularity of Java, it was renamed to JavaScript.

- JavaScript is a multi-paradigm language, which means it supports different

- programming approaches. It is prototype-based, object-oriented, imperative, and functional.

- JavaScript is totally independent from Java and has nothing in common with Java!

# How is Javascript Executed?

- JavaScript is executed in two different ways:

  - Client-side JavaScript (CSJS)
  - Server-side JavaScript (SSJS)

- Client-side JavaScript (CSJS)

  - CSJS is executed by the browser (client) and is used to create dynamic webpages.
  - CSJS is embedded directly into HTML pages by using the <script> tag.
  - CSJS is executed on the client’s machine, which means that the source code is
    visible to the user and can be modified.
  - CSJS is used to validate user input, create cookies, and display dynamic content.
  - CSJS is supported by all modern browsers.

- Server-side JavaScript (SSJS)
  - SSJS is executed by the server and is used to create dynamic webpages.
  - SSJS is embedded directly into HTML pages by using the <script> tag.
  - SSJS is executed on the server, which means that the source code is not visible to
    the user and cannot be modified.
  - SSJS is used to access databases, file systems, etc.
  - SSJS is supported by Node.js.

# JavaScript Engines

- JavaScript Engines are programs that execute JavaScript code. They are found in
- Web browsers (e.g. V8 in Chrome, SpiderMonkey in Firefox, etc.)
- Node.js
- Adobe Acrobat
- MongoDB
- CouchDB
- etc.

# What is Dynamic Typing and Weak Typing Mean?

- JavaScript is a dynamically typed language, which means that you don’t have to specify the data type of a variable when declaring it. The data type of a variable can change during the execution of a program and JavaScript takes care of it automatically.

| Feature              | Dynamic Typed Languages                              | Weakly Typed Languages                                 |
| -------------------- | ---------------------------------------------------- | ------------------------------------------------------ |
| Type Checking        | Performed at runtime                                 | Performed at compile-time or runtime                   |
| Type Flexibility     | Variables can change types during execution          | Variables can change types implicitly or explicitly    |
| Type Safety          | Potential for runtime type errors                    | Potential for implicit type conversions and errors     |
| Variable Declaration | Types can be omitted or inferred                     | Types are usually explicitly declared                  |
| Development Speed    | Faster development due to flexibility                | Slower development due to strictness                   |
| Error Detection      | Potential for late-stage errors                      | Potential for early-stage errors                       |
| Performance          | Generally slower due to runtime type checking        | Generally faster due to compile-time optimizations     |
| Code Readability     | May be less readable without explicit types          | May be more readable with explicit type annotations    |
| Interoperability     | Can easily integrate with external libraries         | May require explicit type conversions or wrappers      |
| Debugging            | May require more effort to trace type-related issues | May have clearer error messages related to type issues |
| Popular Examples     | JavaScript, Python, Ruby                             | C, C++, PHP                                            |


# a Brief Overview of The JavaScript History

- JavaScript was created by Brendan Eich in 1995 during his time at Netscape Communications. It was originally called Mocha, then LiveScript, and finally JavaScript. The name was changed to JavaScript because Netscape and Sun Microsystems wanted to take advantage of the popularity of Java.

| Year       | Milestone                                                                                                                                                                                                           |
|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1995       | JavaScript was created by Brendan Eich at Netscape Communications. Initially called LiveScript, it was designed as a scripting language for web browsers.                                                           |
| 1996       | JavaScript was renamed to JavaScript 1.0 and submitted to Ecma International for standardization,                                                                                                                   |
| 1996 (late)| ECMAScript 1, based on JavaScript 1.1, was released as the first official standard for the language.                                                                                                                |
| 1997 - 2005| Several versions of ECMAScript were released during this period, including ECMAScript 2 (1997), ECMAScript 3 (1999), and ECMAScript 4 (abandoned). These versions introduced various new features and improvements. |
| 2006       | ECMAScript 3.1, also known as ECMAScript 5, was released. It brought significant enhancements to the language, including strict mode, JSON support, and new array methods.                                          |
| 2011       | ECMAScript 5.1 was released as a minor update to ECMAScript 5. It fixed some inconsistencies and improved the specification.                                                                                        |


-----------------------

## Variables

- A variable is a container for storing data values. In JavaScript, we use the var keyword to declare variables, followed by the variable name.

## Var vs Let vs Const

| Feature        | `var`                          | `let`                          | `const`                          |
|----------------|--------------------------------|--------------------------------|----------------------------------|
| Scope          | Function scope                 | Block scope                    | Block scope                      |
| Hoisting       | Hoisted to the top             | Not hoisted                    | Not hoisted                      |
| Reassignment   | Can be reassigned              | Can be reassigned              | Cannot be reassigned             |
| Initialization | Can be declared without value  | Can be declared without value  | Must be assigned when declared   |

## Variables Naming Conventions

| Naming Convention      | Allowed                                              | Not Allowed / Not Recommended                           |
|------------------------|------------------------------------------------------|---------------------------------------------------------|
| Camel Case             | `myVariable`, `totalAmount`, `userName`              | `MyVariable`, `TotalAmount`, `USER_NAME`                |
| Pascal Case            | `MyVariable`, `TotalAmount`, `UserName`              | `myVariable`, `totalAmount`, `user_name`                |
| Snake Case             | `my_variable`, `total_amount`, `user_name`           | `My_Variable`, `Total_Amount`, `UserName`               |
| Hungarian Notation     | `strName`, `nCount`, `bIsVisible`                    | Not recommended due to decreased readability            |
| Underscore Prefix      | `_privateVariable`, `_internalFunction`              | Not recommended, often used for special purposes        |
| Single Character Names | `i`, `j`, `x`, `y`, `z`                              | Not recommended, lacks meaningful identifiers           |
| Abbreviations          | `num`, `btn`, `errMsg`                               | Use full words whenever possible                        |
| Meaningful Names       | `firstName`, `itemPrice`, `isLoggedIn`               | Generic names like `temp`, `data`, `value`              |
| Constants              | `MAX_SIZE`, `DEFAULT_COLOR`, `PI`                    | Regular variables written in all caps                   |

## Operators: Arithmetic, Assignment, Comparison, Logical, Bitwise, etc.

- JavaScript supports the following types of operators:

  - Arithmetic Operators
  - Assignment Operators
  - Comparison Operators
  - Logical Operators
  - Bitwise Operators
  - String Operators
  - Conditional (Ternary) Operator

## Arithmetic Operators

- Arithmetic operators are used to perform arithmetic between variables and/or values. JavaScript supports the following arithmetic operators:

| Operator | Description                                                                 |
|----------|-----------------------------------------------------------------------------|
| +        | Addition                                                                    |
| -        | Subtraction                                                                 |
| *        | Multiplication                                                              |
| /        | Division                                                                    |
| %        | Modulus (division remainder)                                                |
| ++       | Increment                                                                   |
| --       | Decrement                                                                   |
| **       | Exponentiation (ES2016)                                                     |

## Assignment Operators

- Assignment operators are used to assign values to variables. JavaScript supports the following assignment operators:

| Operator | Example | Same As |
|----------|---------|---------|
| =        | x = y   | x = y   |
| +=       | x += y  | x = x + y |
| -=       | x -= y  | x = x - y |
| *=       | x *= y  | x = x * y |
| /=       | x /= y  | x = x / y |
| %=       | x %= y  | x = x % y |
| **=      | x **= y | x = x ** y |

## Comparison Operators

- Comparison operators are used to compare two values and return true or false depending on the result of the comparison. JavaScript supports the following comparison operators:

| Operator | Description                                                                 |
|----------|-----------------------------------------------------------------------------|
| ==       | Equal                                                                       |
| ===      | Equal value and equal type                                                  |
| !=       | Not equal                                                                   |
| !==      | Not equal value or not equal type                                            |
| >        | Greater than                                                                |
| <        | Less than                                                                   |
| >=       | Greater than or equal                                                       |
| <=       | Less than or equal                                                          |
| ?        | Ternary operator                                                            |

## Logical Operators

- Logical operators are used to determine the logic between variables or values. JavaScript supports the following logical operators:

| Operator | Description                                                                 |
|----------|-----------------------------------------------------------------------------|
| &&       | Logical and                                                                 |
| \|\|     | Logical or                                                                  |
| !        | Logical not                                                                 |
| ||       | Logical or                                                                  |

## Bitwise Operators

- Bitwise operators are used to perform bitwise operations on 32-bit integers. JavaScript supports the following bitwise operators:

| Operator | Description                                                                 |
|----------|-----------------------------------------------------------------------------|
| &        | AND                                                                         |
| \|       | OR                                                                          |
| ~        | NOT                                                                         |
| ^        | XOR                                                                         |
| <<       | Left shift                                                                  |
| >>       | Right shift                                                                 |
| >>>      | Zero fill right shift                                                       |


## String Operators

- The + operator can also be used to concatenate (add) strings.

## Conditional (Ternary) Operator

- The conditional operator assigns a value to a variable based on a condition.

## Data Types

- JavaScript variables can hold many data types: numbers, strings, objects and more:

| Data Type  | Description                                              | Example                    |
|------------|----------------------------------------------------------|----------------------------|
| `undefined`| Represents an uninitialized or absent value              | `let x;`                   |
| `null`     | Represents the intentional absence of any object value   | `let y = null;`            |
| `boolean`  | Represents a logical entity, `true` or `false`           | `let isTrue = true;`       |
| `number`   | Represents numeric values                                | `let count = 10;`          |
| `string`   | Represents textual data                                  | `let name = "John";`       |
| `symbol`   | Represents unique, immutable values used as property keys | `let key = Symbol();`      |
| `object`   | Represents a collection of key-value pairs or complex data structures | `let person = { name: "John", age: 30 };` |
| `array`    | Represents an ordered list of values                     | `let numbers = [1, 2, 3];` |


## Functions: Declaration, Expression, Arrow, Anonymous, IIFE, etc.

- A JavaScript function is a block of code designed to perform a particular task. A JavaScript function is executed when "something" invokes it (calls it).

- A JavaScript function is defined with the `function` keyword, followed by a name, followed by parentheses `()`.

- Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

- The parentheses may include parameter names separated by commas: `(parameter1, parameter2, ...)`

- The code to be executed, by the function, is placed inside curly brackets: `{ code to be executed }`

- Function parameters are listed inside the parentheses `()` in the function definition.

- Function arguments are the values received by the function when it is invoked.

- Inside the function, the arguments (the parameters) behave as local variables.

- A function can be called multiple times to produce different results.

- A function can have one or more parameters, but it can also have no parameters at all.

- A function can return data as a result, but it can also return nothing as void.

- A function can be declared, assigned to a variable, passed as an argument to another function, or returned from another function.



## Introduction to Global & Local Scope

- In JavaScript there are two types of scope:

  - Local scope
  - Global scope

- JavaScript has function scope: Each function creates a new scope.
- Scope determines the accessibility (visibility) of these variables.
- Variables defined inside a function are not accessible (visible) from outside the function.
- Local variables have Function scope: They can only be accessed from within the function.
- Since local variables are only recognized inside their functions, variables with the same name can be used in different functions.

```js
const max = 100; // global variable
// code here can NOT use carName
function myFunction() {
  var carName = "Volvo";

  // code here CAN use carName
}

function globalFunction() {
  console.log(max);
} // 100
```






