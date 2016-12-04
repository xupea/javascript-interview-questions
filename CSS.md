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

