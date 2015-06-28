#Project 1 - Build a Landing Page

For Project 1, you will create your own landing page!

![Landing Page Sample](https://raw.githubusercontent.com/fma2/pcp-intro-web-development/master/resources/images/2Aproject1-landingpage1.png)

Once it is submitted, [here is the rubric]() on which it will be graded.

##Part 1 - HTML 

####First step: directory structure

- Keep all the files for your site in the same directory/folder
HTML Files, CSS Files, Images, Scripts, etc.
- Create a directory and name it: landing
- Open the directory in Sublime Text

####Next, create your first HTML page

- Open a new page in Sublime Text
- Add structure: `<!DOCTYPE HTML>`, `<html>`, `<head>`, `<title>`, and `<body>`.
- Save it as index.html in your landing directory
- Open index.html in Chrome

![Basic Structure](https://raw.githubusercontent.com/fma2/pcp-intro-web-development/master/resources/images/2A1htmldocstructure-codesnippet1.png)

####Add more content

- In the body section of your landing page, add a few sentences with some text about you.

![Basic Structure with some content](https://raw.githubusercontent.com/fma2/pcp-intro-web-development/master/resources/images/2A2htmlelements-codesnippet1.png)

####Add even more: tags, elements, and attributes

Scenario: Your top choice for college loves that you can code and wants to see some of your work. 

Make the landing page you started all about you.  Think about what you can include, and add content (see the next slide for details)!

Questions to consider: What is your background?  What are your accomplishments? What are your hobbies?  What else are you proud of?

- Add:
	- Header element containing an image element
	- Input element for the email submission
	- Content about you using at least 6 different elements. For example, use `<p>` to introduce yourself.
		- Elements that will not count for the 6: `<head>`, `<body>`, `<html>`, `<header>`, and `<input>`.
	- Content reviews the following information about you:
		- Your name and picture, a little bit about who you are, your contact details (Twitter handle, email, etc.), recent work, and your skills


##Part 2 - CSS

####Create and link a stylesheet

- In Sublime, if you do not already have a css file for your project - open a new file and save it in your directory as styles.css
- If you do have a css file, open it in Sublime
- Add the following: 

	```css
	body{
  	text-align: center; }
  ```

- Connect your CSS file to your index.html page in the `<head>` tag: 

```html
<link rel=”stylesheet” href=”styles.css”>
```

####Add more styling

- Add 
	- A background image to the body 
	- Header image:
		- use border-radius to get the rounded image effect
		- use height and width to resize the image (try starting with 200px)
	- 10 total CSS rules
	- Use ID in at least one CSS rule
	- Use class in at least one CSS rule 



