
## What is New in HTML5?

### 1. The DOCTYPE declaration and The character encoding (charset) declaration

### 2. New Elements: 

```
New semantic elements like <header>, <footer>, <article>, and <section>.
New attributes of form elements like number, date, time, calendar, and range.
New graphic elements: <svg> and <canvas>.
New multimedia elements: <audio> and <video>.
```

### 3. New HTML5 API's
```
HTML Geolocation
HTML Drag and Drop
HTML Local Storage
HTML Application Cache
HTML Web Workers
HTML SSE
```

## What is New in CSS3?

1. Rounded Corners : border-radius
2. Border Images : border-image
3. Multi-column Layout : The CSS3 multi-column layout allows easy definition of multiple columns of text - just like in newspapers
4. Box Sizing : box-sizing
5. Flexible Box: Use of flexbox ensures that elements behave predictably when the page layout must accommodate different screen sizes and different display devices
6. Media Queries :
```
@media not|only mediatype and (expressions) {
    CSS-Code;
}
```

## ES6
[logo]: https://github.com/xupea/javascript-interview-questions/blob/master/Screen%20Shot%202017-08-02%20at%2011.50.40%20PM.png?raw=true "Logo Title Text 2"


## Responsive Web Design

Responsive Web Design makes your web page look good on all devices (desktops, tablets, and phones).

Responsive Web Design is about using CSS and HTML to resize, hide, shrink, enlarge, or move the content to make it look good on any screen

Bootstrap

## Less
Less is a CSS pre-processor, meaning that it extends the CSS language, adding features that allow variables, mixins, functions and many other techniques that allow you to make CSS that is more maintainable, themeable and extendable.

## Grunt
In one word: automation. The less work you have to do when performing repetitive tasks like minification, compilation, unit testing, linting, etc, the easier your job becomes. After you've configured it through a Gruntfile, a task runner can do most of that mundane work for you—and your team—with basically zero effort.

## Gulp
Automate and enhance your workflow

By preferring code over configuration, node best practices, and a minimal API surface - gulp makes things simple like never before.

Using the power of node streams, gulp gives you fast builds that don't write intermediary files to disk.

By enforcing strict guidelines, we ensure our plugins stay simple and work as expected.

## Webpack2
Webpack is a module bundler for modern JavaScript applications. When webpack processes your application, it recursively builds a dependency graph that includes every module your application needs, then packages all of those modules into a small number of bundles - often only one - to be loaded by the browser.

Responsive Web Design:

Step1:
```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
Step2:
```
<!--[if lt IE 9]>
<script src="http://css3-mediaqueries-js.googlecode.com/svn/trunk/css3-mediaqueries.js"></script>
<![endif]-->
```
Step3:

No absolute width
```
width: xx%;
```
Step4:
No absolute font-size
```
body {
  font: normal 100% Helvetica, Arial, sans-serif;
}
h1 {
  font-size: 1.5em; 
}
```
step5:

fluid grid
```
.main {
  float: right;
  width: 70%; 
}
.leftBar {
  float: left;
  width: 25%;
}
```
step6:

Media query
```
<link rel="stylesheet" type="text/css"
　　　　media="screen and (min-width: 400px) and (max-device-width: 600px)"
　　　　href="smallScreen.css" />
```


