#Substratum
A simple system for creating columns with semantic, fluid classes

##Examples
Add the .column class to create a two-column layout:

	<div class="column"></div>
	<div class="column last"></div>

Extend .column w/ .narrow for three-column layouts:

	<div class="column narrow"></div>
	<div class="column narrow"></div>
	<div class="column narrow last"></div>

Create a 2/3 1/3 layout like so:

	<div class="column wide"></div>
	<div class="column narrow last"></div>

Or a 1/3 2/3 layout like this:

	<div class="column narrow"></div>
	<div class="column wide last"></div>

Sometimes you just want one column:

	<div class="column single"></div>

##To Do
* Incorporate line-height defaults to make it a simple grid framework.
* Decide on a CSS style guide for formatting and commenting code and use it.
