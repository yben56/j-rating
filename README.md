J-Rating jquery Plugin
==============================

##Demo


##Dependencies
jquery-3.1.1 & Bootstrap v3.3.6

##Usage

```html
<script type="text/javascript" src="src/ezAutoSuggestion/ezAutoSuggestion.js"></script>
<link rel="stylesheet" href="src/ezAutoSuggestion/ezAutoSuggestion.css" />

Create a div and add an id into it. <div id="rating"></div>
```

```javascript
$("#rating").jRating();

You can change default stars, size, buttons's color, active's color and display text
$("#rating").jRating({
	stars: 7,
	size: "20px",
	buttons_color: "red",
	active_color: "purple",
	text: true
});
```

##License
This work is licensed under a [MIT License](http://opensource.org/licenses/MIT).

##Author
This Javascript plugin was written by Benjamin Wong benjamin-w@hotmail.com