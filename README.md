Material Radio Checkbox
==========================


[Material Design Icons][] . Material Design Icons styled radio button and checkboxes.


Install
--------
bower install material-radio-checkbox

Use
------------

Make sure to include  **material-radio-checkbox.css** in your HTML, or add scss/less files [Sass](#using-sass) / [Less](#using-less).

Checkbox Example:
````html
<form role="form">
  ...
	<label class="checkbox">
		<input type="checkbox" />
		Check me out
	</label>
  ...
</form>
````


Radios
------------

Radiobutton Example:
````html
<form role="form">
  ...
  <label class="radio">
	  <input type="radio" name="radio2" value="option1">
	  One
  </div>
  <label class="radio">
	  <input type="radio" name="radio2" value="option2" checked>
	  Two
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
