Material Radio Checkbox
==========================


[Material Design Icons][] . Material Design Icons styled radio button and checkboxes.


**[Demo][]**

Use
------------

Make sure to include  **material-radio-checkbox.css** in your HTML, or add scss/less files [Sass](#using-sass) / [Less](#using-less).

Checkbox Example:
````html
<form role="form">
  ...
  <div class="checkbox">
	<input type="checkbox" id="checkbox1">
	<label for="checkbox1">
		Check me out
	</label>
  </div>
  ...
</form>
````


Radios
------------

Radiobutton Example:
````html
<form role="form">
  ...
  <div class="radio">
	  <input type="radio" name="radio2" id="radio3" value="option1">
	  <label for="radio3">
		  One
	  </label>
  </div>
  <div class="radio">
	  <input type="radio" name="radio2" id="radio4" value="option2" checked>
	  <label for="radio4">
		  Two
	  </label>
  </div>
  ...
</form>
````


Using [Sass][]
----------

````scss

@import "../material-radio-checkbox";

````


Using [Less][]
----------

````less

@import "../material-radio-checkbox";

````

[Material Design Icons]: https://google.github.io/material-design-icons/
[Sass]: http://sass-lang.com/
[Less]: http://lesscss.org/
