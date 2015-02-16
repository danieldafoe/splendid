#Splendid.css
<p>Created by <a href="http://danieldafoe.com">Daniel Dafoe</a></p>
<p>Inspired by <a href="https://github.com/IanLunn/Hover">Hover.css</a> by Ian Lunn 
<p>Splendid.css is a small CSS library of hover effecrs to give your HTML buttons a little more life.</p>
<h2>License</h2>
<p>MIT Licensed; so about as free as a penny you find on the ground.</p>
<h2>Basics</h2>
<p>
	To begin using Splendid.css, you're going to want to download the <code>.zip</code> file from <a href="https://github.com/danieldafoe/splendid" target="_blank">here</a>. This file will include
	 a <code>.scss</code> file (for the fellow SASS lovers), a normal <code>.css</code> stylesheet, as well as a <code>.min.css</code> - a minified, production-ready version.
</p>
<strong>So is it working yet?</strong>
<p>
	Gadzooks! Slow down there. To begin, include this line inbetween the <code>&lt;head&gt;</code> tags
	of your HTML file:<br/>
	<code>&lt;link href="your-css-folder/splendid.css" rel="stylesheet"/&gt;</code>
</p>
<p>
	Next, you'll want to make sure that either the <code>splendid.css</code> or <code>splendid.min.css</code> file is indeed in that directory path. The <code>splendid.scss</code> file is for advanced users only. If you are familiar with SASS (<a href="http://sass-lang.com" target="_blank">website</a>) and want to improve upon the original stylesheet, then this file is for you.
</p>
<h2>Getting Started</h2>
<p>
	To start using Splendid.css, you'll want to start by attaching one of the many classes to one of your <code>&lt;button&gt;</code> or <code>&lt;a&gt;</code> elements.
</p>
<p>
	The first class you'll want to add is <code>.spl-btn</code>. This is the class that adds the right look and feel of a Splendid button. You can overwrite these CSS rules to fit your own idea of what a button should look like, but if you prefer to keep your hands clean, then use this.
</p>
<h2>Hover Effects</h2>
<p>
	Using the hover effects that you've seen on the home page is as easy as adding a class to your element that already has the <code>.spl-btn</code> class. To figure out what the class name is of the hover effect you want, simply check out the text within the button that you hovered over. The name you see is the class you'll want to append to your element in order to get that effect.
</p>
<p>
<code>&lt;a href="" class="spl-btn spl-btn-royal spl-lines-full"&gt;spl-lines-full&lt;/a&gt;</code>
</p>
<p>
	The code above is the exact code that was used to generate a button. As you can see, Splendid.css even comes with a colour preset for your convenience. <code>.spl-btn-royal</code> was the colour used in the example. The effect that was used is the last class on the element, <code>.spl-lines-full</code>. That's the class that does the heavy lifting. 
</p>
<p>
	If you don't want to use the preset colour for your own buttons, you don't have to &#8212; but you'll need to override the <code>.spl-btn</code> class with your desired <code>background-color</code>. Further, you may need to change the CSS <code>color</code> style of your button's text, or, in some cases, a <code>border-color</code>.
</p>
<h2>Questions</h2>
<p>
	Please direct any comments or questions you have via <a href="https://twitter.com/danieldafoe">twitter</a> or <a href="mailto:hello@danieldafoe.com" target="blank">email</a>.
</p>
<strong>
	Fin.
</strong>


