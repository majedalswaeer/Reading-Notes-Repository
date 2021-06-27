##  WHAT IS AN OBJECT?
### -Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names. example below:

```
var hote l = { 
name: 'Quay', 
rooms: 40, 
booked : 25, 
checkAvailability: function() { 
return this.rooms - this.booked; 
} 
} ; 
JAVASCRIPT 
var el Name = document .getElementByld('hotelName'); 
elName.textContent =hotel .name; 
var elRooms = document.getElementByid{'rooms'); 
elRooms.textContent = hotel .checkAvailability(); 
```
## DOM 
```

<html> 
<body> 
<di v id="page"> 
<hl id="header">List</hl> 
<h2>Buy groceries</h2> 
<ul > 
<li id="one" class="hot"><em>fresh</em> figs</li> 
<li id="two" class="hot">pine nuts</l i> 
<l i id="three" class="hot">honey</l i > 
<l i id="four">balsamic vinegar</l i> 
</ ul > 
<script src="js/l i st.js "></scri pt> 
</ div> 
</ body> 
</ html 

```
### As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes. 
1- THE DOCUMENT NODE : Above, you can see the HTML code for a shopping list, and on the right hand page is its DOM tree. Every element, attribute, and piece of text in the HTML is represented by its own DOM node.At the top of the tree a document node is added; it represents the entire page 
2-ELEMENT NODES : HTML elements describe the structure of an HTML page. (The <h l > - <h6> elements describe what parts are headings; the <p> tags indicate where paragraphs of text start and finish; and so on.)
### Accessing and updating the DOM tree involves two steps: 
1: Locate the node that represents the element you want to work with. 
2: Use its text content, child elements, and attributes. 
### ACCESSING ELEMENTS
### DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.
### METHOD THAT RETURN A SINGLE ELEMENT NODE:
*getElementByld('id')
### METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST): 
1- getEl ementsByClassName('class ')
2- getEl ementsByTagName( 'tagName')
3- querySelectorAll ( 'css selector')




