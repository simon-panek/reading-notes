# Code 102: Class 2 - The Coder's Computer
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
[Return to reading-notes](https://github.com/paneks19/reading-notes)
