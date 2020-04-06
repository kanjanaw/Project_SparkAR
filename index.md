
<!DOCTYPE html>

<html>

<head>

<title>จองที่นั่ง</title>

<meta charset="utf-8">

<meta name="viewport" content="width=device-width, initial-scale=1">


<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
```

```html
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
```

<link href="https://fonts.googleapis.com/css?family=Kanit&display=swap" rel="stylesheet">

</head>

<style>

body{

background-image: linear-gradient(120deg, #fdfbfb 0%, #ebedee 100%);

background-size: cover;

background-repeat: repeat;

background-attachment: fixed;

font-family: 'Kanit', sans-serif;

}

.dot {

height: 4vh;

width: 4vh;

background-color: #5cb85c;

border-radius: 50%;

margin: 0.2vh;

display: inline-block;

}

.dot > * {

background-color: transparent;

}

.sqr {

height: 5.5vh;

width: 9vh;

background-color: transparent;

border: #6c757d;

border-style: solid;

border-width: 1px;

border-radius: 5px;

color:#343a40;

margin-top: 0.8vh;

margin-bottom: 0.8vh;

display: inline-block;

}

.space {

margin:5vh;

}

.obj-center{

text-align: center;

margin: auto;

padding: 1vh;

}

.text {

background-image: linear-gradient(transparent 0%, currentColor 30%, currentColor 70%, transparent 90%);

-webkit-background-clip: text;

background-clip: text;

background-attachment: fixed;

}

.text > * {

color: transparent;

}

.text-fgreen {

color: #5cb85c;

background-image: linear-gradient(transparent 0%, currentColor 30%, currentColor 70%, transparent 90%);

-webkit-background-clip: text;

background-clip: text;

background-attachment: fixed;

}

.text-fgreen > * {

color: transparent;

}

.text-fred {

color: #d9534f;

background-image: linear-gradient(transparent 0%, currentColor 30%, currentColor 70%, transparent 90%);

-webkit-background-clip: text;

background-clip: text;

background-attachment: fixed;

}

.text-fred > * {

color: transparent;

}

</style>

<body>

<!-- Navbar menu !-->

<div class="row">

<div class="col-md-12">

<nav class="navbar navbar-expand-sm bg-transparent navbar-light fixed-top">

<!-- Brand/logo -->

<a class="navbar-brand" href="#"><h3>Logo</h3></a>

<ul class="navbar-nav mr-auto mt-2 mt-lg-0"></ul>

<!-- Button -->

<ul class="navbar-nav justify-content-end my-2 my-sm-0">

<a class="btn btn-outline-dark" href="qrcode_scanner.html" role="button">QRCODE SCANNER</a>

</ul>

</nav>

</div>

</div>

<!--Jumbotron-->

<div class="row">

<div class="col-md-12 text-center" style="padding-top: 20vh; padding-bottom: 10vh;">

<div class="text">

<h1>ที่นั่งโซนอาหาร</h1>

</div>

<div class="row">

<div class="col-md-2 col-2"></div>

<div class="col-md-4 col-4 text-fgreen">

<span class="dot"></span><h6>ที่นั่งว่าง</h6>

</div>

<div class="col-md-4 col-4 text-fred">

<span class="dot" style="background-color: #d9534f;"></span><h6>ที่นั่งไม่ว่าง</h6>

</div>

<div class="col-md-2 col-2"></div>

</div>

</div>

</div>

<!-- Table Preview!-->

<div class="container">

<div class="row" style="text-align: center;">

<!-- Table Row A-->

<div class="col-3">

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<span class="sqr obj-center">A1</span>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<div class="space"></div>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<span class="sqr obj-center">A2</span>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<div class="space"></div>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<span class="sqr obj-center">A3</span>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

</div>

<!-- Table Row ฺฺB-->

<div class="col-3">

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<span class="sqr obj-center">B1</span>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<div class="space"></div>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<span class="sqr obj-center">B2</span>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<div class="space"></div>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<span class="sqr obj-center">B3</span>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

</div>

<!-- Table Row C-->

<div class="col-3">

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<span class="sqr obj-center">C1</span>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<div class="space"></div>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<span class="sqr obj-center">C2</span>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<div class="space"></div>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<span class="sqr obj-center">C3</span>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

</div>

<!-- Table Row D-->

<div class="col-3">

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<span class="sqr obj-center">D1</span>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<div class="space"></div>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<span class="sqr obj-center">D2</span>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<div class="space"></div>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

<span class="sqr obj-center">D3</span>

<div class="row">

<div class="obj-center">

<span class="dot"></span>

<span class="dot"></span>

</div>

</div>

</div>

</div>

</div>

</div>

<!-- foot -->

<div class="container" style="margin: 100px"></div>

</body>

</html>

-   © 2020 GitHub, Inc.
-   [Terms](https://github.com/site/terms)
-   [Privacy](https://github.com/site/privacy)
-   [Security](https://github.com/security)
-   [Status](https://githubstatus.com/)
-   [Help](https://help.github.com/)

[](https://github.com/ "GitHub")

-   [Contact GitHub](https://github.com/contact)
-   [Pricing](https://github.com/pricing)
-   [API](https://developer.github.com/)
-   [Training](https://training.github.com/)
-   [Blog](https://github.blog/)
-   [About](https://github.com/about)
