#### Arrays
An array stores a list of values within its variabled
- the values of the list are stored inside square brackets`[]`
- each value is seperated by a comma
- values do not need to be the same data type

**array literal** _*Preferred Method_

``` Javascript
var colors = ['white','blue','pink'];
```

**array constructor** 

_Note:_values are stored in parethesis (not squared brackets)_

``` Javascript
var colors = new Array('white',
                        'blue',
                        'pink');
```
-
##### Accessing Items

- Values in an array are accessed as index, 0 being the first.

INDEX | VALUE
----- | -----
0 | white
1 | blue
2 | pink

```javascript
var itemtwo
itemtwo = colors[2];
```
- find the number of items in an array
```javascript
var numColors
numColors = colors.length
```

Truthy/Falsey
console - in browser, can lookup the values of those variables
cohesion - changes number into a string (edited) 