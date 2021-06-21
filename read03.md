## List types(HTML BOOK p62-73):
* Ordered lists: are lists where each item in the list is numbered, example below:
```
<ol>
<li>Chop potatoes into quarters</li>
<li>Simmer in salted water for 15-20
 minutes until tender</li>
<li>Heat milk, butter and nutmeg</li>
<li>Drain potatoes and mash</li>
<li>Mix in the milk mixture</li>
</ol>
```
* Unordered lists: are lists that begin with a bullet point, example below:

```
<ul>
<li>1kg King Edward potatoes</li>
<li>100ml milk</li>
<li>50g salted butter</li>
<li>Freshly grated nutmeg</li>
<li>Salt and pepper to taste</li>
</ul>
```
* Definition lists: are made up of a set of terms along with the definitions for each of those terms. example below:
```
<dl>
<dt>Sashimi</dt>
<dd>Sliced raw fish that is served with 
 condiments such as shredded daikon radish or 
 ginger root, wasabi and soy sauce</dd>
<dt>Scale</dt>
<dd>A device used to accurately measure the 
 weight of ingredients</dd>
<dd>A technique by which the scales are removed 
 from the skin of a fish</dd>
<dt>Scamorze</dt>
<dt>Scamorzo</dt>
```

## Boxes Dimensions(HTML p300-329)
### To set your own dimensions for a box you can use the height and width properties. The most popular ways to specify the size of a box are to use pixels, percentages, or ems. using like below:
```div.box {
height: 300px;
width: 300px;
background-color: #bbbbaa;}
p {
height: 75%;
width: 75%;
background-color: #0088dd;}
```
```td.description {
min-width: 450px;
max-width: 650px;
text-align: left;
padding: 5px;
margin: 0px;}
```
### also we can overflowing our text as follow:
```p.one {
overflow: hidden;}
p.two {
overflow: scroll;}
```
### adjust borders and padding as below:
```
p.one {border-style: solid;}
p.two {border-style: dotted;}
p.three {border-style: dashed;}
p.four {border-style: double;}
p.five {border-style: groove;}
p.six {border-style: ridge;}
p.seven {border-style: inset;}
p.eight {border-style: outset;}
```
```
p {
width: 275px;
border: 2px solid #0088dd;}
p.example {
padding: 10px;}

```
***
***
## Basic JavaScript Instructions
### ARRAYS: An array is a special type of variable. It doesn't just store one value; it stores a list of values. example below:
```
var colors; 
colors ['white', 'black', ' custom']; 
var el document.getElementByld('col ors'); 
el . textContent = col ors[O];  

```
## EXPRESSIONS
### -An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions. 
### EXPRESSIONS Types:
* EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE, like : **var color = 'beige';**
* EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE , like : **var area = 3 * 2;**

## Decisions and Loops(switch and if)
### if ... e1se statement allows you to provide two sets of code:
 1. one set if the condition evaluates to true 
 2. another set if the condition is false
### SWITCH STATEMENTS: A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value. 






