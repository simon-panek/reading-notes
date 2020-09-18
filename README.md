***
# reading-notes
Reading Notes for Codefellows
***
## Reading Review Table of Contents

* Coding 102: Class 1 - [Learning Markdown](url)
* Coding 102: Class 2 - [The Coder's Computer](url)
* Coding 102: Class 3 - [Git Intro](url)
* Coding 102: Class 4 - 
* Coding 102: Class 5 - 
* Coding 102: Class 6 - 
* Coding 102: Class 7 - 
* Coding 102: Class 8 - 
* Coding 102: Class 9 - 
* Coding 102: Class 10 - 

***
## Profile

### To Do:
- [x] Growth Mindset
- [x] Self Reminders
- [x] Links to My Pages
- [x] \(Optional) Post my Profile Picture
- [ ] \(Optional) Leave a check box unchecked to test

<img src="/Simon%20Profile%20Pic.jpg" width=200>

###### Yet to figure out why this picture does not show up correctly in the deployed version. Possible issue with the theme?


## Growth Mindset
**Growth mindset** is the concept that intelligence, knowledge, and skill are *not* a fixed quantity and that with most things in life, a focused effort can lead to improvement.

### Self Reminders
1. Challenges are unavoidable, and an opportunity for improvement.
2. There was a time that I did not know anything that I know now.
   1. A few minutes ago I did not know how to make a link to [my slack profile](https://app.slack.com/client/T039KG69K/G01985S2L9M/user_profile/U01AURZ67QB). I do now, although I am guessing that this link may not provide the result for a user other than myslef, since it is taking me to my slack account. \(More to learn!) :exploding_head:
3. Helping others succeed is often a way to ~~suceed~~ succeed for oneself.

```
If I were posting code, it would look like this.
```

## This looks like *Tic-Tac-Toe*, but it does not allow for user input. 
X|O|O
---|---|---
O|O|X
X|X|X
###### Yet to figure out why this chart does not show up correctly in the deployed version. Possible issue with the theme?


#### My GitHub [Portfolio](https://github.com/paneks19)

##### My deployed site can be found [here.](https://paneks19.github.io/reading-notes/)

##### My rendered site can be found [here.](https://github.com/paneks19/reading-notes/blob/master/README.md)

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

```
To quote a block of text or code, use ``` "fences" before and after.
```

To create a task list use the following
```
- [ ] Item (Incomplete)
- [x] Item (Complete)
```

To create a chart:
Letter|1|2|
---|---|---
A|A1|A2
B|B2|B3

Chart code
```
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

Git
















