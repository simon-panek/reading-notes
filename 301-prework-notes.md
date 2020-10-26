# Code 301: Pre-work Readings

***

### [Can I use: Arrow Functions](https://caniuse.com/?search=arrow%20functions)

## Read: # [MDN Arrow Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

- Compact alternative to a traditional function expression
- No binding to `this` or `super` & should not be used as a method
- No arguments or `new.target` keywords
- Cannot be used as a constructor
- Example:
  - Traditional

  ```JavaScript

  function (a) {
    return a + 100;
  }

  ```

  - Arrow Function

  ```JavaScript

  a => a + 100;

  ```

- Traditional 2

  ```JavaScript

  function (a, b) {
    return a + b + 100;
  }

  ```

  - Arrow Function 2

  ```JavaScript

  (a, b) => a + b + 100;

  ```

- Traditional 3

  ```JavaScript

  let a = 4;
  let b = 2;
  function (a) {
    return a + b + 100;
  }

  ```

  - Arrow Function 3

  ```JavaScript

  let a = 4;
  let b = 2;
  a => a + b + 100;

  ```

- Traditional 4

  ```JavaScript

  function (a, b) {
    let chuck = 42;
    return a + b + chuck;
  }

  ```

- Arrow Function 4

  ```JavaScript

  (a, b) => {
    let chuck = 42;
    return a + b + chuck;
  }

  ```

- Traditional 5

  ```JavaScript

  function bob (a) {
    return a + 100;
  }

  ```

- Arrow Function 5

  ```JavaScript

  let bob = a => a + 100;

  ```

- Basic syntax: parameter => expression
  - (parameter1, parameter2) => expression

## Read: [JavaScript Arrow Functions ES6 - Wes Bos](https://wesbos.com/arrow-functions)

- Arrow function benefits: concise syntax, implicit returns, do not rebind value of `this`
- Operand `=>` called a "fat arrow"
- Arrow functions are all anonymous and do not have names
- Can assign a variable the value of an arrow function

## Read: Let and Const

### [Let MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let)

### [Can I use: let](https://caniuse.com/let)

- let *declares variables that are limited to the scope of a block statement, or expression*
  - Only initialized to a value when a parser evaluates it
  - Does not create properties of the `window` object when declared globally
    - Example:

    ```JavaScript

        var x = 'global';
        let y = 'global';
        console.log(this.x); // "global"
        console.log(this.y); // undefined

    ```

### [Const MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const)

### [Can I use: let](https://caniuse.com/const)

- Constants *block scoped, can't be changed through reassignment and can't be redeclared*
- Global constants do not be come properties of the `window` object
- Must assign value at time of declaration
- `const` declaration creates a read-only reference to a variable
- Cannot share a name with a a function or a variable in the same scope
- Can be declared with upper or lower case, convention is to use all-uppercase letters

### Video: [Var, Let and Const](https://www.youtube.com/watch?v=sjyJBL5fkp8)

- Constants minimize mutable state!

### Read: [JavaScript ES6+: var, let, or const?](https://medium.com/javascript-scene/javascript-es6-var-let-or-const-ba58b8dcde75)

- `typeof` does not work with `let` or `const`

### Read: [let vs const ES6 - Wes Bos](https://wesbos.com/let-vs-const)

- Whenever you are inside of a set of curly braces you are in block scope
- `const` cannot be assigned a new value after declaration, but if it is an object its properties can be updated

***

[Return to reading-notes Deployed Site](https://simon-panek.github.io/reading-notes/)

[Return to reading-notes Mark Down](https://github.com/simon-panek/reading-notes)