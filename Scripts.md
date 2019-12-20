## Scripting

Scripting is a series of instructions that a computer follows.

Examples: Recipes, Handbooks, Manuals

### Writing a script

1. Define the Goal - What are you trying to achieve?
2. Design the Script - Split the goals into series of tasks. (Flow Charts)
3. Code Each Step - write into programming language for the computer to follow

_REMEMBER the exercise:_ Write the steps to put on a jacket. 

---

### Think like a Computer.

**Vocabulary** - words the computer understands

**Syntax** - they way you put the words together to create instruction for the computer


Computers solve problems **programmatically** - follow series of instructions. 


Using Flow Charts will help you work out the tasks in dfferent situations.  - this step can put into a picture all the steps the computer will need to follow, and the way you can block out the syntax steps. 

**Expressions** - evaluate into results a single value.  

1. expressions that assign a value to a variable
```javascript
var drink = 'martini';
```

2. expressions that use two or more values to return a single value
```javascript
var BAC = 0.2 * 4;
```

**Operators*** - create single value form one or more values.  Different types:

1. Assignment operators - assign a value to a variable
2. Arithmetic operators - perform basic math - order of operations (P-E-M-D-A-S)
3. String operators = combine two strings
4. Comparison operators - compares two values and returns TRUE or FALSE
5. Logical operators - Combine expressions and return TRUE or FALSE

---

### Functions

Let you group a series of statements toghether to perform the tasks.  You are able to reuse functions multipe time throught  your code. 

**Calling** a function, when you ask computer to perform the function.  This call is placed in your code block, at the point where you want to execute the task. 

At that point, the computer will read the code.  Sometimes we will need to provide information to the function, which is called **parameters**.  If you wish that the function provide information back, this will need a **return value**.  

```javascript
function byeFelicia(){
    document.write('Bye Felicia!');
}
```

```javascript
function getBAC(drinks){
    var bac = drinks * 0.02;
    return bac;
}
```
```javascript
getBAC(6);

bac=0.12
}
```
**arguements are the actual values passed into the parameters of the function (i.e. 6)


- in our hmtl we will need to establish our javascript file - in the Head, before we call our function in our code block

[HOME](https://cassandraortiz.github.io/learning-journal/)