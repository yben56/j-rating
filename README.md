J-Rating jquery Plugin
==============================

##Demo
https://yben56.github.io/j-rating/

##Dependencies
jquery-3.1.1 & Bootstrap v3.3.6

##Usage

```html
//html
<link href="src/j-rating/j-rating.css" type="text/css" rel="stylesheet" />
<script src="src/j-rating/j-rating.js"></script>

Create a div, add an id and place inside of form. <form><div id="rating"></div></form>
```
```javascript
//javascript
$("#rating").jRating();

You can change default stars, size, buttons's color, active's color and display text
$("#rating").jRating({
	stars: 7,
	size: "20px",
	buttons_color: "red",
	active_color: "purple",
	text: true
});

//If you wish to use this inside of user's edit page, simple pass {rating: 'user's rating value'} into it
```

```php
//backend(php)
(backend will receive a radio button post or get)
$_POST['j-rating']
```
##License
This work is licensed under a [MIT License](http://opensource.org/licenses/MIT).

##Author
This Javascript plugin was written by Benjamin Wong benjamin-w@hotmail.com
