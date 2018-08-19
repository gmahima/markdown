
```html
<!DOCTYPE html>
<html>
<head>
	<title>Getting Started with CSS Layout</title>
	<link href='https://fonts.googleapis.com/css?family=Varela+Round' rel='stylesheet' type='text/css'>
	<link rel="stylesheet" href="page.css">
	<link rel="stylesheet" href="style.css">
</head>
	<body>
	<div class="container">
		<footer class="clearfix">
			<img class="logo" src="city-logo.svg" alt="logo">
			<ul class="footer-nav">
				<li><a href="#">Ice cream</a></li>
				<li><a href="#">Donuts</a></li>
				<li><a href="#">Tea</a></li>
				<li><a href="#">Coffee</a></li>
			</ul>
			<p class="copyright clearfix">&copy;2015 The Best City.</p>
		</footer>
	</div>
	</body>
</html>
```

```css
.footer-nav,
.footer-nav li{
  float: left;
}
.logo {
float: right;}

.copyright {
border: 10px solid black;
clear: both;}

.clearfix::after {
  content: "";
  display: table;
  clear: both;
}
```
