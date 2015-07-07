#Writing Links - Cheat Sheet

[adapted from htmlandcssbook.com]

##LINKING TO EXTERNAL CSS

```html
<link rel="stylesheet" type="text/css" href="styles.css">
<!-- make sure the href attribute specifies the correct path to the CSS file -->
```

##LINKING TO OTHER SITES

When you link to a different website, the value of the `href` attribute will be the ful web address for the site, which is known as an **absolute** URL.

```html
<a href="http://www.google.com">Google</a>
```

##LINKING TO OTHER PAGES ON THE SAME SITE

When you are linking to other pages within the same site, you do not need to specifiy the domain name in the URL.  You can use a shorthand known as a **relative** URL.

If all the pages of the site are in the same folder, then the value of the `href` attribute is just the name of the file.  

If you have different pages of the site in different folders, then you can use a slightly more complete syntax to indicate where the page is in relation to the current page.

For the example below, consider this directory

```
examplearts [directory]
	|_ index.html
	|_ images [directory]
 		|_ logo.gif
 	|_ movies [directory]
 		|_ cinema [directory]
 			|_ index.html
 			|_ listings.html
 			|_ reviews.html
		|_ dvd [directory]
			|_ index.html
			|_ reviews.html
	|_ music [directory]
		|_ index.html
		|_ listings.html
		|_ reviews.html
	|_ theater [directory]
		|_ index.html
		|_ listings.html
		|_ reviews.html
 
```
| RELATIVE LINK TYPE | EXAMPLE |
|-------------------|--------|
|**SAME FOLDER**<br>To link to a file in the same folder, just use the file name. (Nothing else is needed)||
|**CHILD FOLDER**<br>For a child folder, use the name of the child folder, followed by a forward slash, then the file name||
|**GRANDCHILD FOLDER**<br>Use the name of the child folder, followed by a forward slash, then the name of the grandchild folder, followed by another forward slash, then the file name.||
|**PARENT FOLDER**<br>Use `../` to indicate the folder above the current one, then follow it with the file name.||
|**GRANDPARENT FOLDER**<br>Repeat the `../` to indicate that you want to go up two folders (rather than one), then follow it with the file name.||

