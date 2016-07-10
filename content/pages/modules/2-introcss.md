#Module 2: Introduction to CSS

Welcome to Module 2!  In this module, we'll introduce ourselves to CSS.

##Learning Objectives

1. Understand how to write a CSS rule
2. Understand how to style text and images
3. Understand how to use CSS for layout


##Rundown

- [2.1. CSS Selectors](#21-css-selectors)
- [2.2. Color, text, images](#22-color-text-images)
- [2.3. Boxes](#23-boxes)
- [2.4. Layout](#24-layout)

##Time permitting...

- [Responsive Design and CSS Frameworks](#responsive)
- [Resources](#resources)

<hr height="10px">
##<a id="21-css-selectors">2.1. Introducing CSS </a>

###View

- Slides: [Introducing CSS](https://docs.google.com/presentation/d/1rI8-I3JHOsacf1ZNr_JXSFFniqZHERvy7I3sC-BAG1E/edit?usp=sharing)

###Exercise/s

1. [Writing CSS rules](https://docs.google.com/presentation/d/1rI8-I3JHOsacf1ZNr_JXSFFniqZHERvy7I3sC-BAG1E/edit#slide=id.g1155caacb6_0_697)

	Let’s practice writing CSS rules. If you’re not sure how, search online using: [https://developer.mozilla.org/en-US/docs/Web/CSS/Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

	Example: Give all images a solid border of 1px

	```css
	img {
		border: 1px solid;  
	}
	```

	- Underline every link in purple
	- Make every paragraph Arial or, if not available, san-serif
	- Make every paragraph italicized, with 16px bold text and san-serif font
	- Underline every visited link in green
	- Make every element with class “standout” 25px and orange

2. [Add CSS to your portfolio project
](https://docs.google.com/presentation/d/1rI8-I3JHOsacf1ZNr_JXSFFniqZHERvy7I3sC-BAG1E/edit#slide=id.g1155caacb6_0_825)

	- For your landing page/portfolio, create a stylesheet in the same directory as your html pages 
	- Add a link in the ```<head>``` of each html page to connect the stylesheet
	- In Sublime, if you do not already have a css file for your project - open a new file and save it in your directory as styles.css
	- If you do have a css file, open it in Sublime
	- Add the following:

		```css
		body {
			text-align: center; 
		}

		```

	- Connect your CSS file to your index.html page in the <head> tag

		```html
		<link rel="stylesheet" type="text/css" href="styles.css">
		```

	- Time permitting, try writing a CSS selector for your project


<hr height="10px">
##<a id="22-color-text-images">2.2. Color, text, images</a>

###View

- Slides: [CSS: color, text, images](https://docs.google.com/presentation/d/1N53LrCD6j2dn_lOqVoqCPebX5Zm-ugo73NrzNMo6btI/edit?usp=sharing)

###Exercise/s

1. Coding challenge: [Add some color](https://docs.google.com/presentation/d/1N53LrCD6j2dn_lOqVoqCPebX5Zm-ugo73NrzNMo6btI/edit#slide=id.g154639d184_0_17)

	- Download code: [https://github.com/barnard-pcp-intro-web-dev/css-colors-text-images](https://github.com/barnard-pcp-intro-web-dev/css-colors-text-images)
	- Give the text between a ```<h1>``` tag a foreground color
	- Give the text between a ```<a>``` tag a background color. 

2. Coding challenge: [Change typeface and font size](https://docs.google.com/presentation/d/1N53LrCD6j2dn_lOqVoqCPebX5Zm-ugo73NrzNMo6btI/edit#slide=id.g154639d184_0_82)

	- Use code from previous coding challenge.
	- Change the typeface of the ```<h1>``` text
	- Change the font size of the ```<p>``` text


3. Coding challenge: [Change text styling](https://docs.google.com/presentation/d/1N53LrCD6j2dn_lOqVoqCPebX5Zm-ugo73NrzNMo6btI/edit#slide=id.g154639d184_0_104)

	- Use code from previous coding challenge.
	- Add bold, italics, capitals, and underlines to text

4. Coding challenge: [Add alignment and spacing](https://docs.google.com/presentation/d/1N53LrCD6j2dn_lOqVoqCPebX5Zm-ugo73NrzNMo6btI/edit#slide=id.g154639d184_0_125)

	- Use code from previous coding challenge.
	- Add CSS rules for
		- line height
		- letter and word spacing
		- text alignment

5. Coding challenge: [Add CSS to your landing page/portfolio project](https://docs.google.com/presentation/d/1N53LrCD6j2dn_lOqVoqCPebX5Zm-ugo73NrzNMo6btI/edit#slide=id.g1155b8410e_0_466)

	- Add a background image to the body
	- Using the CSS properties you just learned, add at least 5 CSS rules -- e.g. color, size, or font of text

	- Keep styling - add more CSS rules to make it your own!

<hr height="10px">
##<a id="23-boxes">2.3. Boxes</a>

###View
- Slides: [CSS - Boxes](https://docs.google.com/presentation/d/1lCQFdT9hYy8ZJKyWF3jN7_IF0-SO2zXdfHwWwzzYYWk/edit?usp=sharing)

###Exercise/s

1. Activity: [Are you sure everything is a box?](https://docs.google.com/presentation/d/1lCQFdT9hYy8ZJKyWF3jN7_IF0-SO2zXdfHwWwzzYYWk/edit#slide=id.g1155dbd7bd_0_33)

	- Go to: [http://bit.ly/3-1-shapes](http://bit.ly/3-1-shapes) 
	- Use the inspector to explore the page. Expand the DOM tree in the Elements tab
	- Hover over reach div of class “row”. What do you notice in the browser?
	- Hover over each div with a class of “surprise”. What happens on the page?
	- Edit the CSS in the browser. Change width, height, and border-radius. What happens?

2. Activity: [Box model - pair up and practice!](https://docs.google.com/presentation/d/1lCQFdT9hYy8ZJKyWF3jN7_IF0-SO2zXdfHwWwzzYYWk/edit#slide=id.g1155dbd7bd_0_99)

	- Download code: [https://github.com/barnard-pcp-intro-web-dev/css-boxes](https://github.com/barnard-pcp-intro-web-dev/css-boxes) 
	- Experiment with widths, heights, margins, borders, contents. Use colors for different borders, background images, or font styles. 
	- Extra!: Try experimenting with size and overflow. 

3. Activity: [Boxifying design](https://docs.google.com/presentation/d/1lCQFdT9hYy8ZJKyWF3jN7_IF0-SO2zXdfHwWwzzYYWk/edit#slide=id.g1155dbd7bd_0_147)

	- Go to: [http://assignments.udacity-extras.appspot.com/courses/html-css/img/mock4-portfolio-2.pdf](http://assignments.udacity-extras.appspot.com/courses/html-css/img/mock4-portfolio-2.pdf) 
	- How many boxes would you need to recreate this design?
	- Draw it out in your notebook.
	- Finished?  Try to boxify the design of other samples: [http://assignments.udacity-extras.appspot.com/courses/html-css/index.html](http://assignments.udacity-extras.appspot.com/courses/html-css/index.html) 


<hr height="10px">
##<a id="24-layout">2.4. Layout - positioning content with ```position``` and ```float```</a>

###View

- Slides: [CSS Layout - Positioning Content](https://docs.google.com/presentation/d/1ItHXO7LH2q5l_jZWxQY7v4kgrE57QYKVQxkLuj6qxoA/edit?usp=sharing)

###Exercise/s

1. Coding challenge: [Let's position!](https://docs.google.com/presentation/d/1ItHXO7LH2q5l_jZWxQY7v4kgrE57QYKVQxkLuj6qxoA/edit#slide=id.g1155d75cc6_0_117)

	- Download the code: https://github.com/barnard-pcp-intro-web-dev/css-positioning 
	- Position each of the img elements appropriately. 
		- The sheep should be around the bottom left
		- The cow should be on the horizon
		- The dude should be dancing in the middle
		- The tree should be on the front right
		- The sun should be around the upper right.
	- As a bonus, position a picture of your face on top of the dude, and watch yourself have a farm party!

2. Coding challenge: [Explore floats!](https://docs.google.com/presentation/d/1ItHXO7LH2q5l_jZWxQY7v4kgrE57QYKVQxkLuj6qxoA/edit#slide=id.g1155d75cc6_1_14)

	- 

3. Coding challenge: [Practice floats again!](https://docs.google.com/presentation/d/1ItHXO7LH2q5l_jZWxQY7v4kgrE57QYKVQxkLuj6qxoA/edit#slide=id.g1155d75cc6_1_37)

	- 

4. Coding challenge: [Practice positionining with floats and clear](https://docs.google.com/presentation/d/1ItHXO7LH2q5l_jZWxQY7v4kgrE57QYKVQxkLuj6qxoA/edit#slide=id.g1155d75cc6_1_49)

	- Pair with a partner to recreate [this page layout](https://docs.google.com/presentation/d/1ItHXO7LH2q5l_jZWxQY7v4kgrE57QYKVQxkLuj6qxoA/edit#slide=id.g1155d75cc6_1_49). 
	- Get starter code at: [https://github.com/barnard-pcp-intro-web-dev/css-positioning](https://github.com/barnard-pcp-intro-web-dev/css-positioning) 
	- Hint: start by drawing/defining your boxes, then layout the boxes


<hr height="10px">


##<a id="responsive">Responsive Design and CSS Frameworks</a>

###View 

- Slides: [Responsive Design](https://docs.google.com/presentation/d/1gQiJHxh-Mrsba3nelcNRhyXXI8U0nExQ_ny94qTJJWw/edit?usp=sharing)
- Slides [CSS Frameworks: Bootstrap](https://docs.google.com/presentation/d/1WQ6tC5wQccCHZ7M4JIp-8_GnFhslN6ormCh1yFcNh_M/edit?usp=sharing)

<hr height="10px">

##<a id="resources">Resources</a>

- Readings
	- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
	- CSS Selectors
		- [CSS Tricks - How CSS Selectors Work](https://css-tricks.com/how-css-selectors-work/)
		- [Selectutorial](http://css.maxdesign.com.au/selectutorial/rule.htm)
	- Positioning Content
		- [Learn CSS Positioning in Ten Steps](http://www.barelyfitz.com/screencast/html-training/css/positioning/)
		- [CSS Positioning](http://www.brainjar.com/css/positioning/default.asp)
		- [CSS Tricks - All About Floats](https://css-tricks.com/all-about-floats/)
		- [Floatutorial](http://css.maxdesign.com.au/floatutorial/)
	- [CSS Tricks - The Box Model](https://css-tricks.com/the-css-box-model/)
	- Responsive Design
		- [Shay Howe: Responsive Web Design](http://learn.shayhowe.com/advanced-html-css/responsive-web-design/)
		- [Skillcrush - Responsive Design](http://skillcrush.com/2012/05/08/responsive-design/)
		- [Responsive Web Design](http://alistapart.com/article/responsive-web-design)
		- [This is Responsive](http://bradfrost.github.io/this-is-responsive/index.html) - A collection of patterns and modules for responsive designs
	- Flexible Layouts
		- [Flexible Math](http://responsv.com/flexible-math/)
- Presentations & Videos
	- CSS Selectors - [slides](http://www.teaching-materials.org/htmlcss-1day/css-selectors/slides.html#slide1) & [video](https://www.youtube.com/watch?v=wQXvat7IHmk)
	- [Udacity - HTML-CSS-DOM](https://www.youtube.com/watch?t=152&v=tSv2KIF7uE4)
	- [Udacity: Boxes, Grids, and Rules](https://www.youtube.com/watch?v=fvtm9lK-JM0)
	- [Don't Fear Starting from Scratch Part 2: CSS](http://www.dontfeartheinternet.com/css/don%E2%80%99t-fear-starting-from-scratch-2)

