#Writing Links - Cheat Sheet

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




