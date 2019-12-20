# Designing with CSS

**CSS** - ***Cascading Selector Sheets***

Remember our Sitemap we designed?  All those boxes within boxes and so on.  Well, now its time to design those boxes ***Elements*** and make them look pretty!

### Understanding the different Elements

ELEMENT | WHAT TO KNOW | EXAMPLES
------- | ------------ | --------
BLOCK | look like they start on a new line | \<h1>, \<h6>, \<p>, \<div>
INLINE | flow within the text and do not start on a new line | \<b>, \<i>, \<img>, \<em>, \<span>

---

### A CSS rule contains 2 parts: 

` p {font-family: Arial;}`

**Selector** - indicates which HTML element the rule applies to.  You can have multiple elements seperated by commas ` html, body {color: red;}`

**Declarations** - indicate how the elements should be styled.  Declarations are seperated by `;` Declarations also have 2 parts:

  - **properties** - indicate the aspect of the element you want to change

  - **values** - specify the settings you want to use

---

### Types of Selectors

Selector | Meaning | Example
---------| ------- | -------
Universal | applies to all elements | `* {}`
Type Selector | mathes element name | `h1, h2, h3 {}`
Class Selector | matches class attribute | `.note{}`  `p.note{}` targets only \<p>elements with that class
ID Selector | matches the id attributes | `#introduction {}`
Child Selector | direct child of another | `li>a {}` targets any \<a> element that are children of \<li>
Descendant Selector | descendent of another specified element (not just direct child) | `p a {}` targets and \<a> element that site inside the \<p> element
Adjacent Sibling Selector | the next sibling of another | `h1+p {}` targets the first \<p> after any \<h1> (but not others)
General Sibling Selector | Sibling of another, does not have to be directly preceding | `h1~p {}` If you had 2 \<p> elements that are siblings of \<h1> element, it applies to both

---

## WORKING WITH COLORS 

There are three different ways you can identify colors:
 - RGB Values - `rgb(102,205,170)`
 - Hex Colors - `#66cdaa`
 - Color Names - `MediumAquaMarine`

 Additionally there are two ways that you can adjust the opacity of that color:
 ` opacity: 50%`
 ` rgba(102,205,170,0.5)`

