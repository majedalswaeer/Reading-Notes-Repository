# Images
## Controlling Sizes
### -You can control the size of an image using the width and height properties in CSS, just like you can for any other box, example below:

```
<img src="images/magnolia-large.jpg"
 class="large" alt="Magnolia" /> 
<img src="images/magnolia-medium.jpg"
 class="medium" alt="Magnolia" /> 
<img src="images/magnolia-small.jpg"
 class="small" alt="Magnolia" />

```


``` 
CSS

img.large { 
width: 500px; 
height: 500px;} 
img.medium { 
width: 250px; 
height: 250px;}
img.small { 
width: 100px; 
height: 100px;}

```

## Aligining Images
### -The float property is added to the class that was created to represent the size of the image (such as the small class in our example).
### -New classes are created with names such as align-left or align-right to align the images to the left or right of the page. addition to classes that indicate the size of the image, example below:

```
<p><img src="images/magnolia-medium.jpg" 
 alt="Magnolia" class="align-left medium" />
 <b><i>Magnolia</i></b> is a large genus that 
 contains over 200 flowering plant species...</p>
<p><img src="images/magnolia-medium.jpg" 
 alt="Magnolia" class="align-right medium" />
Some magnolias, such as <i>Magnolia stellata</i>
 and <i>Magnolia soulangeana</i>, flower quite 
 early in the spring before the leaves open...</p>

```

```
CSS
img.align-left {
float: left;
margin-right: 10px;}
img.align-right {
float: right;
margin-left: 10px;}
img.medium {
width: 250px;
height: 250px;}

```
### -BACKGROUNG background-imageproperty allows you to place an image behind any HTML element. This could be the entire page or just part of the page. By default, a background image will repeat to fill the entire box.

## Search Engine Optimization (SEO)
### -Search engine optimization (or SEO) is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers.
### On-Page Techniques: On-page techniques are the methods you can use on your web pages to improve their rating in search engines
### Off-Page Techniques: Getting other sites to link to you is just as important as on-page techniques. Search engines help determine how to rank your site by looking at the number of other sites that link to yours

