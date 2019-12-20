## Comparison Operations

You can evaluate situations by comparing one value to what you would expect it to be.  The result will be a Boolean `true` or `false`.


Operator | Compares two values to see if... | Example
-------- | ----------- | -------
== | they are the same | `"Hello" == "Goodbye"` returns _false_  : `"Hello" == "Hello"` returns _true_
!= | they are _NOT_ the same | `"Hello" != "Goodbye"` returns _true_  : `"Hello" == "Hello"` returns _false_
=== |  _both_ data type and value are the same | `"55" === 55` returns _false_  : `55 === 55` returns _true_
!== |  _both_ data type and value are _NOT_ the same | `"Hello" != "Goodbye"` returns _true_  : `"Hello" == "Hello"` returns _false_
\> | left value is greater than the right value | `89 > 63` _true_  :  `63 > 89` _false_
\>= | left value is greater than OR Equal to the right value | `89 >= 63` _true_  :  `63 >= 63` _true_  :  `63 >= 89` _false_  
< | left value is less than the right value | `89 < 63` _false_  :  `63 > 89` _true_
<= | left value is less than OR Equal to the right value | `89 <= 63` _false_  :  `63 <= 89` _true_  :  `63 <= 63` _true_


## Logical Operations

You can compare the results of more than one value.  The result will be a Boolean `true` or `false`.


Operator | What does it Test? | Example
-------- | ----------- | -------
&& | (AND) test multiple values - ALL values need to be _true_ for result to be _true_ | (`_true_`,`_true_`) = `_true_` : (`_true_`,`_false_`) = `_false_` : (`_false_`,`_true_`) = `_false_` : (`_false_`,`_false_`) = `_false_`
\|\| | (OR) test multiple values - ANY value needs to be _true_ for result to be _true_ | (`_true_`,`_true_`) = `_true_` : (`_true_`,`_false_`) = `_true_` : (`_false_`,`_true_`) = `_true_` : (`_false_`,`_false_`) = `_false_`
! | (NOT) takes a single boolean value and inverts it | !_true_ = `_false_` : !_false_ = `_true_`

---

# The wonderful world of Loops!

A Loop is exactly what it sounds like, the code will keep going around and around until a condition is met. 

**break** causes termination of the loop and goto the next statement outside the loop.

**continue** continue with the current code and check the condition again.


#### REMEMBER: Browser stops what its doing when it reaches a loop, and will continue until that condition is met!  

be careful not to get into a **infinite loop**, where it will never give you a _false_ result to continue.

### For Loops

For loops will continue through an array of items, with a specific starting/stopping values.  These values are stored as variables and will loop through in given incremints until the stopping value is met. 

```JavaScript
var drinks = ['vodka', 'rum', 'tequila'];
var arrayLength = drinks.length; 
var roundNumber = 0;
var msg = '';

for(var x=0; x < drinks;x++){
    roundNumber = (x+1);
    msg += 'He had: ' + roundNumber + 'drinks ';
    msg += drinks[x] + '<br />';
}
document.getElementById('answer').innerHTML = msg;
```

Result: 
```Javascript
Round 1: He had: 1 drinks
Round 2: He had: 2 drinks
Round 3: He had: 3 drinks
```


### While Loops

While loops will continue through a loop until a certain criteria is meet. 

```JavaScript
var p = 1;
var msg = '';

while(p<10){
    msg += p + ' x 5 = ' + (p*5) + '</br>';
    i++;
}
document.getElementById('answer').innerHTML = msg;
```

Result: 
```Javascript
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
