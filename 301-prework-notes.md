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

***

[Return to reading-notes Deployed Site](https://paneks19.github.io/reading-notes/)

[Return to reading-notes Mark Down](https://github.com/paneks19/reading-notes)
