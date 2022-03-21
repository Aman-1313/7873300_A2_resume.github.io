# Host A Resume In Few Simple Steps   
## Purpose 
Host a portfoilio or a resume online using lightweight markup language, static site generator and a distributed version control. The following instructions aim to provide simple yet practical steps to host and format a resume online.

## Prerequisites
- A Markdown formatted Resume
- A Github account

## Instructions
Hosting a resume or a portfolio online can be very helpful to get a new job interview. The following instructions assume little or no technical knowledge for writing and hosting static websites. First we will create our resume using a lightweight markup language. Then we will format it using a static site generator. Subsequently we will explore how to host the resume using distributed version control systems.
1. **Create your resume using _Markdown_**  
    - Gather all the information necessary for your resume.
    - Choose a lightweight markup language editor of your choice, some example include [StackEdit](https://stackedit.io), [Atom](https://atom.io), [Dillinger](https://dillinger.io).
    - Edit and preview your resume using the editor in Markdown format.
    - Save your resume with a .md extension.
2. **Create _Github_ directory to host your resume**
    - Go to https://github.com in your web browser.
    - Create a new Github account if you don't have one already.
    - Create a new directory named username.github.io, where username is your username on GitHub.
3. **Add necessary files to your Github directory**
    - Add your resume Markdown file to the new directory.
    - Rename your resume file to index.md.
    - Create a new file named \_config.yml in your Github directory.
    - Create a new Readme.md file in your Github directory.
    - Describe the content of your directory in the Readme.md file.
4. **Format your resume using _Jekyll_**
    - Choose a theme for your resume from the list of [Jekyll themes](https://jekyllthemes.io/jekyll-documentation-themes).
    - Add the chosen Jekyll theme in the \_config.yml in your Github directory.
> Your \_config.yml file should look something like this:
```yml
theme: jekyll-theme-minimal
title: "My Resume"
```
5. **View and finalize your Resume website**
    - Check your resume website at https://username.github.io in your browser.
    - Try new Jekyll themes to change the website format.  
![](https://media.giphy.com/media/o4WcF5PHKKVcBZZwzE/giphy.gif).   

By following the given instructions carefully you now have succesfully hosted your resume online at https://username.github.io.  

  

## Key Principles 
Inspired by  _Andrew Etter’s_ Modern Technical Writing, here are some key principles and relative practical steps for hosting a great static website or a resume:
#### 1. Use a lightweight markup language: 
- Traditional languages used to write a website content like XML and HTML can be very time consuming and difficult to learn because of their specialized tags and sytax.
-  A lightweight markup language like **Markdown** provide a human readable syntax and is easily converted into HTML, which makes it easier for technical writers to contribute content to an online website.

HTML code 
```HTML
<h1 id="my-resume">My Resume</h1>
<h2 id="experience-">Experience:</h2>
<ul>
<li>first job</li>
<li>second job</li>
<li>third job </li>
</ul>
<p><a href="https://github.com/Aman-1313/Aman-1313.github.io/">https://github.com/Aman-1313/Aman-1313.github.io/</a></p>
```
Markdown code 
```
# My Resume
## Experience:
- first job
- second job
- third job 

<https://github.com/Aman-1313/Aman-1313.github.io/>
```
Both of the code-blocks above provide the exact same result but Markdown is clearly more *Readable* and *Efficient* compared to HTML. This difference becomes even more evident when working on large projects.

>**Related Steps:**
- Choose a lightweight markup language editor of your choice, some example include [StackEdit](https://stackedit.io), [Atom](https://atom.io), [Dillinger](https://dillinger.io).
- Edit and preview your resume using the editor in Markdown format.

#### 2. Format a document with a static site generator:
- Static sites are a fast, simple, and secure source of creating technical documention. 
- Using Lightweight Markup *Content* and a *Theme*(HTML, CSS) __static site generators__ can help add complex functionalities to our documentation website.
>**Related Steps:**
  - Choose a theme for your resume from the list of [Jekyll themes](https://jekyllthemes.io/jekyll-documentation-themes).
  - Add the chosen Jekyll theme in the \_config.yml in your Github directory.

#### 3. Host documents on a Distributed Version Control System:
-  Distributed Version Control Systems can be a great source of hosting static websites or technical documentations.
-  They allow users to work on their documentation offline
-  Each update/commit applied to the documentation is stored in the history that alows the user to keep track of progress.
-  They also allow different users to make changes on same documentation.
>**Related Steps:**
 - Create a new Github account if you don't have one already.
 - Create a new directory named username.github.io, where username is your username on GitHub.
 - Check your resume website at  https://username.github.io in your browser.

## More Resources
https://www.markdownguide.org/getting-started   
https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS  
https://docs.github.com/en/pages  
https://jekyllrb.com/docs/  

## Authors and Acknowledgements
Johnson Makumator-Jones, Hong Gao, Adam Kroeker, Cain Stoeke

## FAQs
1. Why is Markdown better than a word processor?
>  Markdown was created primarily to format information that is to be published online. Unlike traditional word processors, Markdown files can easily be coverted into HTML to be published online.
2. Why is my resume not showing up?
>  A newly deployed Github hosted website can possibly take up to 30 minutes to go online. If your resume does not show up at first, check back after few minutes to see your changes.

