#Homework - Week 2

In the assignments below, you will review additional resources that cover what we did in class.  **Submit your assignments by 9 AM on the the due date listed via the Google Drive link, doc, or folder provided to you**.  

For general questions, reach out to classmates - pcp-htmlcss-summer2015@googlegroups.com.  
Please let me know if you have any issues - barnardpcp@farheen.nyc.


###By Tuesday, June 30th

- Finish Project 1 - see directions [here](https://github.com/fma2/pcp-intro-web-development/blob/master/assignments/project1.md).


###By Thursday, July 2nd

####Review:

- Watch - [Don’t Fear Starting From Scratch - Part 2 CSS](http://www.dontfeartheinternet.com/css/don%E2%80%99t-fear-starting-from-scratch-2) (11:03)
- Read - [Getting to Know CSS](http://learn.shayhowe.com/html-css/getting-to-know-css/)

####Practice:

#####Layout Drill - Left Hand Navigation (adapted from [DBC](www.devbootcamp.com))

We're going to learn some fundamentals about webpage layout. You'll have a HTML file to work with and your job is to change the CSS and only *some* of the CSS to achieve the desired layout.

Download [this folder](https://drive.google.com/file/d/0B2oPzQ6clzPRZGx5VjJ0UEdTWVk/view?usp=sharing) which contains a basic HTML file (index.html) that models a blog post, including:

- A page header
- A navigation bar
- The blog post content
- A footer

It also contains a CSS file.  

If you're not familiar with floating in CSS, you might need to take time to read these resources:

- [A Step-by-Step Float Tutorial](http://css.maxdesign.com.au/floatutorial/)
- [Simple 2 column CSS layout](http://www.456bereastreet.com/lab/developing_with_web_standards/csslayout/2-col/)

CSS is fun and really powerful. It takes a bit to get a handle on selectors and their cascading interaction, but the engineers who master it are treated with awe and reverence.

The styles.css file is missing a few rules.  Specifically, it's missing `float`, `clear`, and padding properties for some selectors.  Modify the styles.css file by adding these properties so the blog post looks like the this:

![Blog post](https://camo.githubusercontent.com/787ea8fd6fa5beadb161d3275a64ef00b4762871/687474703a2f2f662e636c2e6c792f6974656d732f336a30573351304d304f3258324e3136306a31332f53637265656e25323053686f74253230323031332d30322d31362532306174253230372e31322e3138253230504d2e706e67)

Don't change the CSS that is already on the styles.css file--just add `float`, `clear`, and padding properties as needed.  

The entire page is 720px wide; don't change that. The entire .content area should be 600px wide, including any padding and borders. The h2 which includes the blog post title should be flush against the top of the content area.

The left-hand navigation should be 120px wide including any padding and borders. The list items should not have any bullets and the navigation elements should be flush against the left-hand side of the page.

The footer text should align with the start of the content text and there should be 20px of space between the footer text and both the bottom of the content area and the bottom of the page.

Upload your completed folder (with the index.html and styles.css files within it) to your PCP Intro to Web Development Google Drive folder.  

#####Create a Cheat Sheet.

- For this assignment, you’ll create a cheat sheet for HTML/CSS.  In the Google doc file for this homework assignment, you will find a table with the title "______'s HTML and CSS Cheat sheet".  Fill it out completely.  It's recommended you print out a hard copy for yourself and/or save your cheat sheet somewhere easily accessible.

###By Monday, July 6th

####Review:

- Review CSS layout - complete the ["Learn CSS Layout" tutorial](http://learnlayout.com/)
- **Review with a browser-based coding program**.  There are numerous browser-based programs (e.g., Codecademy, Dash) to learn how to code. While they are somewhat lacking as learning tools, they’re excellent for review. You will be going through Codecademy CSS as a refresher. To do the assignment:
	
	- Go to [http://www.codecademy.com/](http://www.codecademy.com/) and create an account 
	- Then, go to [http://www.codecademy.com/en/tracks/web](http://www.codecademy.com/en/tracks/web)
	- You will complete 3 lessons starting with Introduction to CSS. The lessons to complete are: (1) Introduction to CSS, (2) CSS Classes and IDs, (3) CSS Element Positioning (Note: you can start with the HTML lessons for additional review, but only the CSS ones are required)  
	- The last lesson is a project to build a resume. Do this lesson in codecademy, then: 
		- Create a new local directory called resume
		- Create two files: index.html and stylesheet.css and copy/paste the content from codecademy into those files 

####Practice:

#####Create a page using a grid

Read about grid-based design: [Grid-Based Layout 101](http://www.sitepoint.com/grid-based-layouts-101/).

Get inspired by some examples of grid-based layouts: [Grid Layout websites](http://www.siteinspire.com/websites?categories=101).

You are going to recreate the page [here](https://drive.google.com/file/d/0B1MYP7sU_C0vZkxCOGxSSVBZcXc/view) using the grid based CSS framework we created.  The focus of this assignment is to use the grid framework; if your time is limited, don't worry as much about colors and details not mentioned in the directions below.  

- Set up your project 
	- Use the Command Line to create a directory called grid-portfolio 
	- In the directory, create an index.html file, and a styles.css file 

- Link your html and CSS files
	- In your index.html file, add the code:  `<h1> Framework Demo </h1>`
	- In your styles.css file, add CSS to make all text on the page blue 
	- Open index.html in your browser, and verify the text in blue 

- Set up default content
	- Get the html content of the page by copying/pasting the HTML from here: http://jsbin.com/nutoka/2/edit. A few things to notice:
		- I’ve currently included placeholder images from the website placehold.it. Placehold.it is a great resource for getting image placeholders when building a site. It allows you to focus on the layout. You simply put your image size after the url then get a great placeholder image
	- Get the CSS for the grid by copying/pasting the CSS from: http://jsbin.com/sogoci/10/edit?html,css,output. This gives you a grid framework
	
- Set up your boxes, and basic layout
	- Using a pen/pencil, draw out the boxes of your web page, and determine which CSS classes from your framework to use
		- For example, for the large image that is 960x350 pixels, I would use the classes “row” and “column 12”
	- Once you have drawn out on paper how you want to arrange your page, go ahead and write the code in your HTML file to add the appropriate classes 
	- Add additional CSS classes (margins, paddings, etc.) to make your page look similar to the mock up

- Fonts!
	- Using google fonts (http://www.google.com/fonts), find a font that mimics the mockup 

- Final push
	- Run your code through the validator at http://validator.w3.org/ and fix any issues 
	- If you want, update images 
	- Upload your grid-portfolio directory to your PCP Intro to Web Development folder


