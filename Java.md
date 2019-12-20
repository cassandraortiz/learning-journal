# JavaScript

Javascript is the programming language that puts dynamic and interactive experiences on the webpage. 

**Statements** are individual instructions or steps, each statement starts on a new line. Statements should end with a semicolon `;`
some statements uses curly brackets to place the code inside known as **code blocks**.  These statements do not require a semicolon.

**Comments** help you and others understand what your code is doing.  
 `/* multiple line comment`
 `// single line comment`

**Variables** are bits of stored information. 
```JavaScript
var x = 2;
var y = 3;
var z = x*y;
z = 6
```



it is not required to establish what type of variable you are declaring (i.e. Number, string, boolean)

### Data Types

***Numeric Data Type*** - handles all number `0.98992`

***String*** - text that consists of letters and other charachters `'Hi friend!`

***Boolean*** - true or false values only

Use both the single `' '` and `" "` double quotes to assign a string.  It has to be the same opening/closing, ` 'text"` is invalid.

***escaping*** is the use of a backwards slash `/` before any type of quete mark that appears within a string 
```Javascript
var a = 'Your mom said /"Hello!/"'
```


#### Shorthand for variables
all of the below are variations of how to assign variables:
```Javascript
var price = 5;
var quantity = 14;
var total = price * quantity;
```

```Javascript
var price, quantity, total;
price = 5;
quantity = 14;
total = price * quantity;
```

```Javascript
var price = 5, quantity = 4;
var total = price *quantity;
```

```Javascript
var el = document.getElementById('cost');
el.textContent = '$' + total;
```
*This is variable is holding a refernce to an element on the HTML page.*


## RULES FOR NAMING VARIABLES
### *ALWAYS FOLLOW THESE RULES*

1. Name MUST begin with a letter, dollar sign ($) or underscore(_)
2. Names can only contain: letters, numbers, dollar signs or underscors.  ***Never use dash (-) or dot (.)***
3. Can NOT use **keywords** or **reserved** words.  These are special words JavaScript uses to interpert or do something.
4. variables are ***case sensitive***, try not to use the same name with different cases - it's bad practice.
5. Use a name that describes the info of the variable
6. If name is more than one word, use a capital letter for the first letter of the second word: _firstName_

---

***Example in book; pages 46-49***
Notes about example.  
- on first attempt, it did not run the code.
- I had left off an ending semi-colon at the end of one of the lines
- next attempt, it did not run the greeting
- compared code with example
- _got frustrated_
- realized that the path my repository was deeper than example.
- in html; changed path to `../css/c01.css` did similar for js.

[HOME](https://cassandraortiz.github.io/learning-journal/)