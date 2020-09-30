# Code 102: Class 08 - Operators and Loops
***
## Read: JavaScript and JQuery Text pg 150 - 151

Comparison operators *can compare one value in the script to its expected value and result boolean*

- `==` Is Equal To *compares two values (numbers, strings, or booleans) to see if they are the same*
  - `'ABC' == 'DEF'` returns `false`
  - `'ABC' == 'ABC'` returns `true`
- `!=` Is Not Equal To *compares two values to see if they are not equal*
  - `'abc' != 'def'` returns `true`
  - `'abc' != 'abc'` returns `false`
- `===` Strict Equal To *compares two values to see if both their value and data type are the same*
  - `'3' === 3` returns `false` *not same data type*
  - `'3' === '3'` returns `true`
- `!==` Strict Not Equal To *compares two value to confirm that both the data type and value are not the same*
  - `'3' !== 3` returns `true` *not the same data type or value*
  - `'3' !== '3'` returns `false` *same data type and value*
- `>` Greater Than *checks to see if the number on the left is greater than the one on the right*
  - `4 > 3` returns `true`
  - `3 > 4` returns `false`
- `<` Less Than *checks to see if the number on the left is less than the one on the right*
  - `4 < 3` returns `false`
  - `3 < 4` returns `true`
- `>=` Greater Than or Equal TO *checks if the number on the left is greater than or equal to the number on the right*
  - `4 >= 3` returns `true`
  - `3 >= 4` returns `false`
  - `3 >= 3` returns `true`
- `<=` Less Than or Equal TO *checks if the number on the left is less than or equal to the number on the right*
  - `4 <= 3` returns `false`
  - `3 <= 4` returns `true`
  - `3 <= 3` returns `true`

## Read: JavaScript and JQuery Text pg 156 - 157

Logical Operators

- `&&` Logical And *tests more than one condition*
  - `((5 < 2) && (2 >= 3))` returns `false`
- `||` Logical Or *tests for at least one condition being true*
  - `((5 < 2) || (2 >= 3))` returns `false`
  - `((5 < 2) && (2 <= 3))` returns `true`
- `!` Logical Not *inverts a single boolean value*
  - `!(2 < 1)` returns `true`

Short Circuit Evaluation *logical evaluations evaluate from left to right and will stop as soon as they are satisfied of the result*

- `false && anything` returns `false` without evaluating `anything` *because both values cannot be true*
- `true || anything` returns `true` without evaluating `anything` *at least one of the values is true*

## Read: JavaScript and JQuery Text pg 156 - 157

Loops *check a condition, if it returns true a code block will run then will check again, if still true, code block will run again, until no longer true*

- `For` *good for running a loop a specified number of times, uses a counter as a condition*
- `While` *good for running loops that when you don\'t know how many times it should run*
- `Do While` *similar to the `while` loop, but will always run the statements in the curly braces at least once even if the condition evaluates to false*

```javascript

for (var i = 0; i < 10; i++) {
    document.write(i);
}

```

The preceding loop will write `0123456789` to the page.

- `for` *keyword indicating a `for` loop*
- `(var i = 0; i < 10; i++)` *Condition (Counter)*
- `document.write(i);` *Code to execute during loop*

Loop Counter

- `var i = 0;` Initialization *creates a variable and sets it to 0
- `i < 10;` Condition *loop will continue to run until it reaches a specified number, may also use a variable that holds a number*
- `i++` Update *every time the loop is run it adds one to the counter*

## Read: JavaScript and JQuery Text pg 176

While Loop *will continue as long as the condition in the `()` is `true`*

```js

var i = 1; //set counter to 1
var msg = ' '; // message

//store 5 times table in a variable
while (i < 10) {
    msg += i + ' x 5 = ' + (i * 5) + '<br />;
    i++;
}

document.getElementByID('answer').innerHTML = msg;

```

Loop returns the following:

``` 

1 x 5 = 5
2 x 5 = 10
3 x 5 = 15
4 x 5 = 20
5 x 5 = 25
6 x 5 = 30
7 x 5 = 35
8 x 5 = 40
9 x 5 = 45

```

***
[Return to reading-notes Deployed Site](https://paneks19.github.io/reading-notes/)

[Return to reading-notes Mark Down](https://github.com/paneks19/reading-notes)
