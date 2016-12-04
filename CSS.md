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
