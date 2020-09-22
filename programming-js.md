# Code 102: Class 07 - Programming with JavaScript
***
## Read: JavaScipt and JQuery Text pg 1-24

JavaScript *used in browsers to make websits more interactive*

- Access Content *can be used to select the contents of a specific element*
- Modify Content *can be used to change content in an element*
- Program Rules *create a set of steps for the brower to follow to access and modify content*
- React to Events *specify when a script should run*

Script *a seriese of instructions a computer can follow to achieve a goal*

- Writing a script
  1. Define the goal
  2. Design th script *split the goal into a series of tasks*
  3. Code each step

Vocabulary *words that computers understand*

Syntax *how teh words are put together to create instructions that computers can follow*

Computers solve problems proramattically, following a series of instrucitons, one step after another

## Read: JavaScipt and JQuery Text pg 74-79

Expressions evelauate into a singlge value

- First type are expressions that just assign a value to a variable
  - Example: `var color = 'beige';` *The value of color is now beige*
- The second type are expressions that  use two or more values to return a single value
  - Exampele: `var area = 3 * 2` *The value of area is now 6*

Operators allow programmers to create a single value from one or more values

- Assignment operators *assign a value to a variable
  - Example: `var color = 'beige';` *The value of color is now beige*
- Arithmetic operators *perform basic math*
  - Example: `area = 3 * 2` *The value of area is now 6*
- String Operators *combine two strings*
  - Example: `greeting = 'Hi ' + 'Molly';`
- Comparison Operators *compare two values and return true or false*
  - Example: `buy = 3 > 5;` *Value of buy is now false*
- Logical Operators *combine expressions and return true or false*
  - `buy = (5>3) && (2<4);` *The value of buy is now true*

Arithmetic Operators *JS contians the standard operators `+, -, /, *` which can be used with numbers as well as the following special operators*

- `++` *(Increment) adds one to the current number*
- `--` *(Decrement) subtracts one from the current number*
- `%` *(Modulus) devides two values and returns the remainder example: `10 % 3 = 1`*

String Operator *just one operator `+` used to join strings on either side*
 
- Concatenation *the joining of two or more strings to form one new string*

Mixing numbers and strings

- Quotes around a number (`#`) create a string, not a numberic number type. Arithmetic operators cannot be used on strings
  - Example: `'2' + '2' = '22'` *Adding strings concatenates them, it does not add.*
  - Example: `12 + 'Bob' = '12Bob'` *Adding a number to a string, creates a new concatenated string*
  - Example: `'seven' * 'nine' = NaN` *(Not a Number) attempting to use arethmetic operators on strings will return a value called NaN*

## Read: JavaScipt and JQuery Text pg 88-94

Functions *allow programmer to group a series of statements together to perform a specific task*

- Calling the function *the act of running the function, when and where it is desired*
- `{code block}` *Code blocks contain a series of related steps contained between two curly braces}*
- Parameters *pieces of information passed to a function*
- Return Value *the output of a function*

Declaring a Function *give it a name and then write its statements needed to achieve its taks inside the curly braces*

- Function *keyword that declares a function*
- Name *name the function (use camelCase) followed by `()`
- Statents *perform the tasks of the function between the `{}`
- Example: 

```javascript

function sayHello() {
    document.write('Hello!');
}

```

- `function` = Function Keyword
- `sayHello()` = Function Name
- `{documnet.write('Hello!');}` = Code Block

Calling a Function *can execute all of the statements between a functions curly braces with just one line of code in the location that programmer desires*

- Use the function name followed by `();`
- Example: `sayHello();`

Declaring functions that need information *give a function information by providing parameters*
- Parameters *act like variables inside the equation, placed inside the `()` after the function name*

```javascript

function getArea(width,height) {
    return width * height;
}

```

- `width, height` = Parameters *used like veriables inside a function*

Calling a Function that nees information *specify the values it should use in the `()` following the name, these values are called arguments*

- Example of arguments as values = `getArea(3,5);`
- Example of arguments as variables = 

```javascript

wallWidth = 3;
wallHeight = 5;
getArea(wallWidth,wallHeight);

```

Getting a single value out of a function *"returning a result"*

```javascript

function calculateArea(width, height) {
    var area = width * height;
    return area;
}
var wallOne = calculateArea(3,5);
var wallTwo = calculateArea(8,5);

```

- `wallOne` variable now holds 15
- `wallTwo` variable now holds 40

*Note: when the interpreter hits the return command it goes back to the statemnt that called it, subsiqent statements in the function would not be processed*

***
[Return to reading-notes Deployed Site](https://paneks19.github.io/reading-notes/)

[Return to reading-notes Mark Down](https://github.com/paneks19/reading-notes)
