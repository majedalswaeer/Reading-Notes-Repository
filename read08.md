## Layouts
### - to create creative layout we will use the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property. such as : Normal flow, Relative Positioning, Absolute positioningScreen Sizes: Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.Screen Resolution: Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens. example below:

```
<!-- HTML FILE -->
<body>
<div id="header">
 <h1>Logo</h1>
 <div id="nav">
 <ul>
 <li><a href="">Home</a></li>
 <li><a href="">Products</a></li>
 <li><a href="">Services</a></li>
 <li><a href="">About</a></li>
 <li><a href="">Contact</a></li>
 </ul>
 </div>
</div>
<div id="content">
 <div id="feature">
 <p>Feature</p>
 </div>
 <div class="article column1">
 <p>Column One</p>
 </div>
 <div class="article column2">
 <p>Column Two</p>
 </div>
 <div class="article column3">
 <p>Column Three</p>
 </div>
</div>
<div id="footer">
 <p>&copy; Copyright 2011</p>
</div>
</body>

```

```
<!-- CSS FILE -->
body {
width: 90%;
margin: 0 auto;}
#content {overflow: auto;}
#nav, #feature, #footer {
margin: 1%;}
.column1, .column2, .column3 {
width: 31.3%;
float: left;
margin: 1%;}
.column3 {margin-right: 0%;}
li {
display: inline;
padding: 0.5em;}
#nav, #footer {
background-color: #efefef;
padding: 0.5em 0;}
#feature, .article {
height: 10em;
margin-bottom: 1em;
background-color: #efefef;}

```

### -Page Sizes: Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens)
### -Fixed Width Layouts: Fixed width layout designs do not change size as the or decreases the size of their  window. Measurements tend to be given in pixels.
### -Liquid Layouts: Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages
### CSS Frameworks: CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids,styling forms, creating rinter-friendly versions of pages and so on. You can include the CSS framework code in your projects rather than writing the CSS from scratch.
