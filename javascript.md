# Code 102: Class 06 - JavaScript

***

## Read: JavaScript and jQuery Pages 43-69

HTML, CSS, and JavaScript *the three languages of a website*

- HTML `<html>` *provides the structure and content of a web page*
- CSS `{css}` *styles the webpage and defines how the content is displayed*
- JS `javascript()` *controls how the page behaves*
- Attempt to maintain a separate file for each layer as much as possible
- Progressive Enhancement *popular approach to building web pages, each layer improves on the one before it*

JavaScript *plain text language so it does not require any additional tools to start*

[Link to Do Along project pages 46-49](https://github.com/paneks19/reading06-doalong)

Objects and Methods

- Example: *"calling a method of an object"*

`document.write('Good afternoon!');`

- `document` = Object *the `document` object represents the entire page*
- `.` = Member Operator
- `write('Good afternoon!')` = Method *allows new content to be written into the page where the `<script>` element sits*
- `'Good afternoon!'` = Parameters *whenever a method requires some info to work, data is given inside the parentheses*

JavaScript runs where it is found in the html, location maters.

Chrome Developer Tools Shortcuts

- View Source = `opt + cmd + U`
- Developer Tools = `opt + cmd + I`
- Inspect Elements = `opt + cmd + C`
- JavaScript Console =`opt + cmd + J`

Script *set of step by step instrucitons that a computer can follow, each should end with a `;`*

- JS is case sensitive
- `{}` indicate the begining and ending of a code block
- Statements *instructions, each one should begin on a new line and end with a `;`*
- Multiple statements can be grouped together between `{}` to form a singular related *code block*
- `/*comment*/` Format for a multiline comment
- `//comment` Format for a single line comment
- Variable *location where scripts store data*

Variables

- Must declare a variable before being able to use it
  - Example = `var quantity;`
  - `var` = Variable Keyword
  - `quantity;` = Variable Name *sometimes called an identifier*
    - If more than one word, typically written in camelCase: `oneTwoThreeFour`
- Assign a value
  - Example = `quantity = 3;`
  - `quantity` = Variable name
  - `=` = Assignment operator
  - `3` = Variable value

Data Types

Numeric Data Types | String Data Types | Boolean Data Types
--- | --- | ---
Example = `0.75` | Example = `'Hi, Ivy!'` | Example = `true`
For tasks involving counting or sums | Enclosed in a pair of single or double quotes used for working with text | True / False

Strings must always be surrounded by quotes either `"string"` or `'string'` but not a combination. It must also be on one line.

6 Rules for naming variables

1. must begin with a letter, dollar sign `$`, or underscore `_`
2. no dashes `-`, or dots `.` are allowed in a name
3. no **keywords** or **reserved words** are allowed
4. names are case sensitive
5. create a name that represents the information it stores
6. use camelCase for names with more than one word

### How do computers work? Video Notes

Computers take in information, stores info, processes it, and outputs calculation resutls.

- Input *data outside the computer that is put into the computer*
- Storage *data kept in the computer*
- Processing *running of algorithyms on stored data*
- Output *providing the results to the user*

Data and Binary

- Bit is the smallest amount of information it stores either a 1 or a 0
- Binary system *only have two digits: 0 and 1*
- Text in binary *each letter is assigned a number which is then represented by multiple bits*

Circuits and Logic

- All computer calculations are the result of many small and simple calculations performe useing logic in the hardware circuits

Memory, CPU, Input, and Output

- Computers take input from the world, place it in memory, use the CPU to analyze or modify it, return it to memory, and output back to the user

Hardware and Software

- Hardware are the physical components that make up computer
- Software is the code that controls the hardware
- CPU *central processing unit* 
  - Master chip of the system, has smaller dediated hardware inside for specific task, but its primary job is to determine which components to use when depending on the task at hand
- Operating system *master software of the system*
  - Program that controls all other programs and apportions inputs, resources, and outputs


***
[Return to reading-notes Deployed Site](https://paneks19.github.io/reading-notes/)

[Return to reading-notes Mark Down](https://github.com/paneks19/reading-notes)
