# Code 201: Class 01 - Pre-class Reading Notes

***

## Read: 01 - Learning Markdown

### Mastering Markdown on GitHub

* Markdown is primarily plain text and allows the creator to stylize the text with minimal use of HTML tags. Special characters such as \* \# or \- indicate a style to be applied to the following item.
* Images are inserted with the format `![Alt text](image path)`
* Links can be created with the format `[Link Text](url)`
* Some common text emphasis options
  1. *Italics* `*text* or _text_`
  2. **Bold** `**text**` or `__text__`
  3. ~~Strike Through~~ `~~text~~`
  4. ~~***Combination***~~ `~~***text***~~`
* Header tags are indicated with `#` = `<H1>`, `##` = `<H2>`, and so on up to `######` for `<H6>`.
* Lists can be created using the following
  1. `*` = Unordered
  2. `-` = Unordered
  3. `+` = Unordered
  4. `1.` = Ordered
  
> To quote a line of text use `>`.

```md

To quote a block of text or code, use ``` "fences" before and after.

```

To create a task list use the following

```md

- [ ] Item (Incomplete)
- [x] Item (Complete)

```

To create a chart:
Letter|1|2|
---|---|---
A|A1|A2
B|B2|B3

Chart code

```md

Letter|1|2|
---|---|---
A|A1|A2
B|B2|B3

```

GitHub supports emoji :+1:!
Here is an [emoji cheat sheet](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax#using-emoji).

***

## Read: 02 - The Coder's Computer

### Choosing a text editor

#### A text editor is a piece of software located on your local machine or operated in a broser that allows the user to write and manage text.

Four primary features that make for a good text editor

- Code completion *allows you to begin typing and editor will display possilbe suggestions*
- Syntax highlighting *changes the color of text based on whether the text is an attribute, element, or copy*
- Variety of Themes *allows the user to change the overall appearance of the editor*
- Avalability of Extensions *allow the user to add "plugins" to improve coding efficiency.

Emmet is a shorthand language that is built into some text editors that allow the user to code in HTML and CSS much more quickly.

Preinstalled Text Editors (Typically very bare bones.)

+ Mac = Text Edit
+ PC = Notepad
+ Linux = Will depend on the particular distribution

3rd Party Tex Editors (Most provide some or all of the desirable features.)

+ NotePad++ *For Windows only*
+ TextWrangler/BB Edit *For Mac only. Text Wrangler has become BB Edit, free for 30 days then $50*
+ Visual Studio Code *Made by Microsoft for Windows, Mac, and Linux. Has Emmet built in.*
+ Atom *Created by GitHub for Windows, Mac, and Linux. All the necessary features.*
+ Brackets *All OS, but only HTML, CSS, and JavaScript. Has Live Preview which updates after every change.*
* Sublime Text *This is a full service text editor. It has a free version, but the full version costs $70.*

IDE = Integrated Development Environment *a suite of software including text editor, file manager, compiler, and debugger

### The Command Line

* The Terminal allows the user to control the comupter through text input. 
* It is possible to have multiple Terminals open at the same time, performing different functions.
* A typical command has the form `command arguments` example: `ls -l`. This would list the contents of the current directory in long form (one item per line).
* To open a Terminal
  1. Mac = Applications \--> Utilities \--> Terminal
     1. "Command + Space" will open Spotligth, then start typing Terminal
  2. Linux = Applications \--> System or Applications \--> Utilities
* Shell *Defines how the terminal looks and behaves. Most common is "bash"*
* Up and down arrows can be used to select previously used commands to save time

### Basic Navigation

* All directories and files are paths
* Paths provide location information for an item
  * Absolute Paths *provide a location that is not dependant upon the current directory. Commands using them will allways return the same result*
  * Relative Paths *provide a location that depends on the current directory, output of a command may change depending on the current directory*
  * Hierarchical Structure *top level is known as the __root__ directory and is denoted `/`*
* Shortcuts
  * `~` (tilde) *home directory*
  * `.` (dot) *current directory*
  * `..` (dotdot) *parent directory*
  * `Tab` Completion *pressing the "tab" key will invoke the auto complete*
  
### About Files

* Everything is a file
* Linux is not concerned with file extensions to determine file type
* Linux is case sensitive
* Spaces are used to seperate commands, so file names that have spaces should use quotes to combine terms or a `\` before the space to nullify it
* Hidden Files *any filename that starts with a `.` is a hidden file. To hide or unhide simply add or remove a `.` at the begining of a file name.* 
  
### Commands and their function:

* `ls` (Lower case L before the s) *Lists the contents of the current directory*
* `ls -a` *Lists the contents of the current directory including hidden files*
* `echo $SHELL` *Displays the current shell*
* `pwd` *Print Working Directory outputs the current directory*
* `cd` *Change Directory run by itself will return you to your home directory. With an argument takes you to the argument path location*
* `file` *Outputs the file type of a path*

***

## Read: 03 - Git Intro

Version Control *system that records changes and allows easy access to previous versions*

* Local Version Control *__LVC__ entails one database on the local hard disk that stores changes*
* Centralized Version Control *__CVC__ single server stores all of the files and versions which are accessed by multiple clients allowing for greater collaboration, read and write privileges can be controlled*
* Distributed Version Control *__DVC__ improves on the CVC concept by storing mirrored repositories on multiple servers, removing the single point of failure*

Git *a DVCS that saves system of snapshots of your project*

- primarily relies on locl operations
- all changes to any file is tracked
- makes it difficult to accidently lose data
- File states in git
  - committed *securely stored in a local database*
  - modified *changed, but not committed to the database*
  - staged *flagged a file's changed version ot be committed in the next snapshot*
  
Getting Git help in Terminal

```terminal

git help *command*
git *command* --help
man git-*command*

```

Cloning a repository *Git will automatically give the name "origin" to the server and the name "master" to your local branch*
`$ git clone (url)`

List of terminal commands

- `$ git status` *Returns the current branch as well as the status of working files*
- `$ git add filename` *Stages the filename*
- `$ git add *` *Stages all files in a repository*
- `$ git commit -m` "message here describing the changes" *Commits the file and includes a describing message*
- `$ git push origin master` *Pushes changes from the local "master" branch to the remote repository named "origin".
- `$ git stash` *Temporarily removes changes and hides them, giving you a clean working directory*
- `$ git stash apply` *Retrieves hidden changes*
- `$ git remote` *See the short names of all specified remote handles*
- `$ git remote -v` *Shows all the remote URLs next to their short names*

Remote repositories *versions of a project stored online or on network. Teams can push info to and pull info from remote repositories*

***

## Read: 04 HTML & CSS Textbook Chapter 18

### Process and Design

- When creating a website, create fictional visitors complete with a variety of target demographic information. Use them to drive design choices.
- What are the primary motivations and goals of users of your site?
- What information do your users need?
- How often a site should be updated may depend on content and frequency of user visits.
- Card sorting is a methode of determining page and content layout.
- Wireframe *simple sketch that covers the primary info and structure needed for each page*
- Good idea to show wireframe to client prior to showing design, this ensures that content and functionality drive the page build.

Visual Hierarchy *most users do not read entire web pages. Using contrast can help focus a users attention.*

- Size *larger elements grab attention*
- Color *differences between foreground and background color can draw attention*
- Style *changine the style of an element in relation to is adjacent items helps it to stand out*

Grouping and Similarity *visually grouping items of related content through similar element styles*

- Proximity *placing related elements close together*
- Closure *a real or imaginary box that can be drawn around related elements*
- Continuance *items in a line or continous curve are precieved as more related than those that are not*
- White Space *intentionally using gaps to deliniate different groups of elements*
- Color *background color placed behind related items*
- Borders *line drawn around related elements*

Navigation *a good design allows users to better find and understand your content*

- Concise *quick and easy to read, ideally no more than 8 links or options in a menu*
- Clear *predictable outcomes based on link descriptions*
- Selective *primary navigation should only focus on navigation not other items such as login*
- Context *good navigation indicates to the user where they are in relation to the site overall*
- Interactive *links should be physically easy to use and differenciate from other text on the screen*
- Consistent *keep the primary navigation structure the same throughout*

## Read: 04 HTML & CSS Textbook Chapter 1

### Structure

HTML (Hypertext Markup Language) *describes the structure of a webpage*

HTML Elements *usually made up of two tags inside angle brackets `<example></example>`

Attributes *provide more information and instruciton in a tag, consist of two parts: name and value seperated by "="*

- Example `<p lang="en-us">Paragraph in English</p>`
  - `lang` = name
  - `"en-us"` = attribute value

List of Tags

- `<body></body>` *everything in this element is shown in the browser window*
- `<head></head>` *contains information about the page*
- `<title></title>` *title above the window tab*

View Source *in browser allows you to see the code for the current page, this can be useful in figuring out how to achieve certain structures*

## Read: 04 HTML & CSS Textbook Chapter 17

### HTML 5 Layout

HTML 5 *introduced new tags that are more specific for the structure of the page*

Common Structural Tags

 - `<header>` *used at the top of a page or the top of a section to hold the descriptive info for that section*
 - `<footer>` *at the bottom of a page to contain info like copyright or at the bottom of a section*
 - `<nav>` *used to contain the major navigational blocks*
 - `<article>` *used to contain any section that could potentially stand alone*
 - `<aside>` *when used nested inside an article it should convery secondary information like a quote, when outside of an article acts as container for info relating to the entire page*
 - `<section>` *element groups related content to gether*
 - `<hgroup>` *used to contain a title and subtitle within an element*
 - `<figure>` *used to contain any content that is referenced from a main article, the article should still make sense even if the figure is moved to another location*
 - `<figurecaption>` *provides a text caption of the figure*
 - `<div>` *contains related elements*
 - `<a href="url">` *allows whole sections to be treated as a link if nested insde the `<a></a>`*

 Older browsers may need to be updated or have extra JavaScript added to function properly.

 ## Read: 04 HTML & CSS Textbook Chapter 8

### Extra Markup

- HTML 4
  - Released in 1997
  - Most elements from HTML 5 are available in 4
  - A few specific tags are no longer recomended although they still work

- XHTML 1.0
  - Released 2000
  - This was a re-write of HTML 4 to follow the rules of XML
  - More strict that 4

- HTML 5
  - Work in progress
  - Browser builders are implimenting now
  - May need to provide backwards compatibility for older browsers

Doctypes *tells the browser what kind of HTML it is using*

- HTML 5 = `<!DOCTYPE html>`
- HTML 4 = `<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3org/TR/html14/loose.dtd">`
- Transitional XHTML 1.0 = `<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">`
- Strict XHTML 1.0 = `<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">`
- XML Declaration = `<?xml version="1.0" ?>`

Comments in HTML
`<!--Comment-->` *allows coder to place notes in the code ignored by the computer*

ID Attribute *every html element can have an id attribute used to individually name it. 

- ID Attributes should start with a letter or an "_" not a number or other character
- It is a global attribute because it can be used on any element
- Example: `<p id="idname">`

Class Attribute *allows multiple elements to be given the same label

- Assigning a Class or id attribute does not alter the style unless a CCS style is specificially applied to the id or class
- Example: `<p class="exampleclassname">`

Block Elements *will always appear to start on a new line*

``` html

- <h1>
- <p>
- <ul>
- <li>

```

Inline Elements *always appear to continue on the same line as their neighboring elements*

``` html

- <a>
- <b>
- <em>
- <img>

```

Span *acts like an inline equivalent of the `<div>` tag.*

- Example = `<span class="classname">Text that is spanned</span>`

IFrames *short for inline frame, holds a seperate window within your window*

- Common example would be embedding a google map within a page
- Example = `<iframe width="desiredwidth" height="desiredheight" src="url"></iframe>`

Meta *provides information about your page*

- Lives inside the `<head>` element
- Not visible to users, but useful to search engines, creator info, time sensitivity
- Example: `<meta name="description" content="Descriptionofpage" />`
  - Possible Attributes
    - Description *description of page, helps search engines determine what the page is about, not more than 155 characters, may display on search engine results*
    - Keywords *list of comma seperated words that a user may search for to find your site, no longer has an appreciable effect on page rank*
    - Robots *indicates whether search engines should add this page to their search results or not*
      - `<meta name="robots" content="noindex" />` *do not add to search results
      - `<meta name="robots" content="nofollow" />` *add this page to search results but do not follow any links*
    - Author *defines the page author*
    - Pragma *prevents browser from caching the page*
    - Expires *indicates when the page should expire if cashed*

Escape characters allow the coder to add characters to the page that would otherwise be operands in html

- Example = `&copy` = copyright symbol

***

## Read: 5 Chapter 10

CSS (Cascading Style Sheets) *alows developer to set rules to specify how content and layout should appear*

- Every element should be treated as though it has a bouding box, each box and its contents can be controlled by CSS
- CSS associates rules with html elements

CSS Rule *governs how content of specified elements should be displayed*

- Rule contains two parts: selector and declaration
  - Example = `p {font-family: Arial;}`
  - `p` = Selector *indicates which elements rule applies to*
  - `font-family: Arial;` = Declaration *how the elements should be styled*
    - CSS Declaration sits inside `{}` and is made up of two parts: a property and a value
    - Property *indicates the aspects of an element that you want to control*
    - Value *specifies the setting to use for a chosen property*
    - Can specify more than one property in one declaration, seperated by a `;`

External CSS *Allows a single seperate file to contain all of the style information for a multipage website*

- `<link>` *element placed inthe html document in the `<head>` element telling the browswer where to find the CSS
- Example = `<link href="urlofcss" type="textorcss" rel="stylesheet" />`
  - `href` *indicates the path to the CSS file*
  - `type` *specifies type of doc being linked to text or css*
  - `rel` *specifies relationship between html page and file linked to, should be stylesheet when linking to CSS file*

Internal CSS *can use CSS in html page by placing them within a `<style>` element, usually inside a `<head>` element

- When building a site with more than one page, should use an external CSS file to keep consistant and for ease of updates/changes
- Example:

``` html

<head>
    <title>Using Internal CSS</title>
    <style type="text/css">
        body {
                font-family: arial;
                background-color: rgb(185,179,175);}
    </style>
</head>

```

CSS Selectors

Selector | Meaning | Example
--- | --- | ---
Universal Selector | applies to all elements in doc | `*{}`
Type Selector | matches element names | `h1, h2, h3 {}`
Class Selector | matches element whose class attribute has value specified after the `.` | `.example {}`
ID Selector | matches element whose id attribute has value specified after the `#` | `#example {}`
Child Selector | matches the element that is a direct child of another | `li>a {}`
Descendant Selector | matches element that is a descendant of another specified element | ` p a {}`
Adjacent Sibling Selector | matches and element that is the next sibling of another | `h1+p {}`
General Sibling Selector | matches element that is a sibling of another, does not have to be directly preceding element | `h1~p {}`

Cascading Rules

- Last Rule *if two selectors are identical the latter will take precedence*
- Specificity *more specific rules will apply over more genaric rules*
- Important *can add `!important` after any rule to indicate that it should be treated as more important than other rules that apply to the same element*
  - Example: `p b { color: blue !important:}`

Inheritance *style properties that are inheritable can be given to all children of an element by default*

- Some properties like font-family default to be inherited by children of an element
- Some properties like background-color are not inheritable
- Can force many properties to inherit by setting `inherit` in the value of the property

Online tools that allow developer to test CSS appearance in multiple virtual browsers and or OS

- BrowserCam.com
- BrowserLab.Adobe.com
- [BrowserShots.org](browsershots.org)
- [CrossBrowserTesting.com](crossbrowsertesting.com)

CSS Bug Fixes and Tools

- [PositionisEverything.net](positioniseverything.net)
- [QuirksMode.org](quirksmode.org)

## Read: 5 Chapter 11

Color *the `color:` property allows you to specify text color in an element*

- RGB Values *express colors in terms of how much red, green, and blue are used `rgb(100,100,90)`
- Hex Codes *express the color using six-digit code representing amount of red, green, and blue in a color preceeded by a `#`, example: `#ee3e80`*
- Color Names *there are 147 predefined named colors, example: `DarkCyan`*

CSS Comments *developer notes that will not effect the code*

- Place comments between `/*comment*/`

Background Color *background color is set to transparent by default, most browsers show white, but not always*

``` css

body {
    background_color: rgb(200,200,200):}

```

Online Color Picking Tool
[Color Scheme Designer](https://colorschemedesigner.com/csd-3.5/)

Opacity *allows developer to set the opacity of an element and its children, values from 0.0 to 1.0*

- To set opacity, indicate a color in `rgba`, example: `rgba(231,112,56,0.5)`

HSL Colors *defines a color in three terms: hue, saturation, and lightness*

- Hue *colloquial idea of color, often shown as a color wheel indicated by degrees 0-360*
- Saturation *amount of gray in a color, 100% is full saturation, 0% is a shade of gray*
- Lightness *amount of white or black in a color, 0% Lightness is black, 100% Lightness is white, 50% is normal. AKA Luminosity*
- HSLA *adds the alapha value for transparency from 0 to 1.0*

***

## Read: JavaScript and jQuery Pages 43-69

HTML, CSS, and JavaScript *the three languages of a website*

- HTML `<html>` *provides the structure and content of a web page*
- CSS `{css}` *styles the webpage and defines how the content is displayed*
- JS `javascript()` *controls how the page behaves*
- Attempt to maintain a seperate file for each layer as much as possible
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

The preceeding loop will write `0123456789` to the page.

- `for` *keyword indicating a `for` loop*
- `(var i = 0; i < 10; i++)` *Condition (Counter)*
- `docment.write(i);` *Code to execute during loop*

Loop Counter

- `var i = 0;` Initialization *creates a variable and sets it to 0
- `i < 10;` Condition *loop will continue to run until it reaches a specified number, may also use a variable that holds a number*
- `i++` Update *everytime the loop is run it adds one to the counter*

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

```console

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