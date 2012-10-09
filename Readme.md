#Substratum
A simple system for creating columns with semantic, fluid classes

##Examples
Add the .column class to create a two-column layout:
	&lt;div class=&quot;column&quot;&gt;&lt;/div&gt;
	&lt;div class=&quot;column last&quot;&gt;&lt;/div&gt;

Extend .column w/ .narrow for three-column layouts:
	&lt;div class=&quot;column narrow&quot;&gt;&lt;/div&gt;
	&lt;div class=&quot;column narrow&quot;&gt;&lt;/div&gt;
	&lt;div class=&quot;column narrow last&quot;&gt;&lt;/div&gt;

Create a 2/3 1/3 layout like so:
	&lt;div class=&quot;column wide&quot;&gt;&lt;/div&gt;
	&lt;div class=&quot;column narrow last&quot;&gt;&lt;/div&gt;

Or a 1/3 2/3 layout like this:
	&lt;div class=&quot;column narrow&quot;&gt;&lt;/div&gt;
	&lt;div class=&quot;column wide last&quot;&gt;&lt;/div&gt;

##To Do
* Incorporate line-height defaults to make it a simple grid framework.
