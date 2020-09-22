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




***
[Return to reading-notes Deployed Site](https://paneks19.github.io/reading-notes/)

[Return to reading-notes Mark Down](https://github.com/paneks19/reading-notes)
