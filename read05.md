## Images
### images can be used to set the tone for a site in less time than it takes to read a description.so if you have a page that shows several images (such as product photographs or members of ateam) then putting them on a simple, consistent background helps them look better as a group. example below :
``` 
<img src="images/quokka.jpg" alt="A family of 
 quokka" title="The quokka is an Australian 
 marsupial that is similar in size to the 
 domestic cat." />

 ```
 
### You will also often see an <img>element use two other attributes that specify its size:heightThis specifies the height of the image in pixels.widthThis specifies the width of the image in pixels like :
```
<img src="images/quokka.jpg" alt="A family of 
 quokka" width="600" height="450" />

 ```
 ## colors
 ### The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways: 
 1-rgb values: These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
 2-hex codes: These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash sign. For example: #ee3e80
 3-color namesThere are 147 predefined color names that are recognized by browsers. For example: DarkCyan

 ### background-color
 ### CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names. ex below :

 ```
 body {
background-color: rgb(200,200,200);}
h1 {
background-color: DarkCyan;}
h2 {
background-color: #ee3e80;}
p {
background-color: white;}
```
## Texts
### Specifying Typefaces font-family:
### The font-family property allows you to specify the typeface that should be used forany text inside the element(s) to which a CSS rule applies.The value of this property is the name of the typeface you want to use. ex below:
```
body {
 font-family: Georgia, Times, serif;}
 h1, h2 {
 font-family: Arial, Verdana, sans-serif;}
 .credits {
 font-family: "Courier New", Courier, 
 monospace;}

 ```
 ### Size of Type font-size: The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font. The most common are:
1- pixels: Pixels are commonly used because they allow web designers very precise control over how much space their text takes up. The number of pixels is followed by the letters px.
2- percentages: The default size of text in browsers is 16px. So a size of 75% would be the equivalent of 12px, and 200% would be 32px
### Example:

```
body {
font-family: Arial, Verdana, sans-serif;
font-size: 12px;}
h1 {
font-size: 200%;}
h2 {
font-size: 1.3em;}

```

