#4: Special Topics

Welcome to Unit 4!  In this unit, we'll explore a few special topics in web development.

Use the links below to jump to a section of this page.

- [4.1: Wordpress](#41-wordpress)
- [4.2: JavaScript and jQuery](#42-js)
- [4.3: Version Control](#43-version)
- [4.4: Git and Github](#44-github)
- [Resources](#resources)

<br>
<hr height="10px">
##<a id="41-wordpress">4.1: Wordpress</a>

####4.1a: What is Wordpress?

- Read: [4.1 - Wordpress](https://docs.google.com/presentation/d/1gy88GUrvnSyOOispnwoyiarN76IjbEqT6uXqOAXlRmk/edit?usp=sharing)

<br>
<hr height="10px">
##<a id="42-js">4.2: JavaScript and jQuery</a>

####4.2a: JavaScript & jQuery

- Read: [4.2 - JavaScript & jQuery](https://docs.google.com/presentation/d/1Iqyz77BacsWmd9PDsXdz-2kmEHJDQBVHp5GkUC07RcE/edit?usp=sharing)

<br>
<hr height="10px">
##<a id="43-version">4.3: Version Control</a>

####4.3a: What is version control, and why use it?

- Read: [What is version control, and why care?](https://docs.google.com/presentation/d/1qQRKIdsQXsPeiYSez-0VvPAwEJScv3lUauTYg9PxLfM/edit?usp=sharing)
- Watch: [What is Version Control?](http://git-scm.com/video/what-is-version-control)

<br>
<hr height="10px">
##<a id="44-github">4.4: Git and Github</a>

####4.4a: Let's Git going

+ Read [Git & Github](https://docs.google.com/presentation/d/1mN8AtAtMOl-06arrcWszp_G7bgXEr-Zohk3hJoeCsOc/edit?usp=sharing)

####4.5a: Hosting with Github Pages

######Get your site hosted

We want you to share your final project on a publicly available URL. To do this, you would normally use a web host. Read more about webhosting [here](http://www.w3schools.com/website/web_host_intro.asp). For most of your projects, you’ll want to start with an affordable shared host like [hostgator](http://www.hostgator.com/shared) or [1-on-1](https://www.1and1.com/web-hosting#hosting-system). 

Github also provides free hosting through [github pages](https://pages.github.com/). Setup is quick and easy! To set up github pages for an existing repository:

**1**: Go to the repository home on github, i.e., github.com/[yourUsername]/[yourRepositoryName]2. 

![github home](https://raw.githubusercontent.com/fma2/pcp-intro-web-development/master/images/git-repo-home.png)

**2**: Click the branch: master dropdown

![github dropdown](https://raw.githubusercontent.com/fma2/pcp-intro-web-development/master/images/git-branch-dropdown.png)

**3**: In the input box that reads “Find or create a branch…” type the words “gh-pages” and click enter4. 

![github gh-pages](https://raw.githubusercontent.com/fma2/pcp-intro-web-development/master/images/git-repo-gh-pages.png)

**4**: That’s it! Your site should be available at: **[yourUsername].github.io/[yourRepositoryName]**

######Pushing changes to github pages

To host your site, github creates a new branch called “gh-pages”. A branch is a snapshot of your website.  So far, we’ve only been working in one branch, the master branch. Now, your project has two branches so you have to keep them both up to date with changes. To do so:

- Make changes locally on your master branch
	- Before starting work, make sure you are on the master branch. To verify this, run `git status` and you should see a note that reads “On branch master”. If you don’t see this, then run the command `git checkout master` to switch to your master branch
	- Make any edits you want, and when you ready, add the files (`git add .`), commit (`git commit -m “some message”`) and push changes to your master on github (`git push`)

- Merge the changes you made to your gh-pages branch 
	- Switch to your gh-pages branch by running `git checkout gh-pages`
		- If you get an error that says “pathspec ‘gh-pages’ did not match any file(s) known to git), then run `git fetch`
			- You only need to do this once. This fetches all the changes from your github repository and copies it to your local. In essence, we want to make sure a copy of the gh-pages branch, which you created on github, also exists locally. If we made changes to your gh-pages in class, You DONT need to do this step
	- Verify you are on the gh-pages branch by running `git status`. You should see a note that says “On branch gh-pages”
	- Merge your changes by running `git merge master` 
	- Push changes by running `git push `
	- That’s it! Refresh your live page on github (you may need to do it a few times) and your changes should be live 

Anytime you want to make a change, follow the steps again, starting with master, committing, pushing, then merging changes to gh-pages

 


<br>
<hr height="10px">

##<a id="resources">Resources</a>


