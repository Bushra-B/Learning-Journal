# HTML, CSS and Javascript
----------------------------
**The three languages that are used to create web pages using the *progressive enhancement* approach are: HTML, CSS and Javascript**
- each language form a *layer* with a different purpose
    - HTML forms the content layer which gives the page structure
    - CSS forms the presentation layer 
    - Javascript forms the behavior layer

- a js code can be added in an html code between <script></script> tags, but it's better to keep the js code in a separate file

## Basic JS intro:
1. Statements
**A series of instructions that a computer can follow one-by-one is called a *script*,
While an individual instruction/step is called a *statement***
- statements should end with a semicolon
----
2. Comments
 **Comments are used to explain what your code does and to make it easier to understand**
 - for a single-line comment: use `//comment`
 - for a multi-line comment:  use `/*comment*/`
-----
3. Variables
**Information use in a script are stored in *variables***
- the information stored in a variable can change each time the script runs (that's why they're called variables)
- variables must be *declared* befor they are used, which means they must be created and given a name, declaration is done as:
`var variable-name;`, where var is the *keyword* for a variable
-----
4. Data Types
**JS has three data types, which are:**
- Numbers: for numeric data
- Strings: for letters and charecters, anything between (" ") is a string
- Booleans: have ine value, True or False
-----
5. Naming Variables Rules
**In JS, there are six rules for naming a variable, which are:**
- a name *MUST NOT* start with a number, it must start with a letter, ($) or ( _ )
- a name *MUST NOT* contain a ( - ) or  a ( . )
- you can't use a *keyword* or a *reserved word*
- all variables are *case sensetive*
- use a name that describes the information it stores
- use *camel case* if the variable name has more than one word
