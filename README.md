# Host A Resume In Few Simple Steps   
## Purpose 
Host a portfoilio or a resume online using lightweight markup language, static site generator and a distributed version control. The following instructions aim to provide simple yet practical steps to host and format a resume online.

## Prerequisites
- A Markdown formatted Resume
- A Github account

## Instructions
1. **Create your resume in a _lightweight markup language_**  
    - Gather all the information necessary for your resume.
    - Write your resume in Markdown file format.
    - Choose a Markdown editor of your choice some example include [StackEdit](https://stackedit.io), [Atom](https://atom.io), [Dillinger](https://dillinger.io).
  

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
- Choose a lightweight markup language. In this example we will use a _Markdown_ format to write our resume.
- Choose a Markdown editor of your choice, some example include [StackEdit](https://stackedit.io), [Atom](https://atom.io), [Dillinger](https://dillinger.io).
- Write your resume using the chosen Markdown editor.
- Save your file named as index.md. 

#### 2. Format a document with a static site generator:
- Static sites are a fast, simple, and secure source of creating technical documention. 
- Using Lightweight Markup *Content* and a *Theme*(HTML, CSS) __static site generators__ can help add complex functionalities to our documentation website.
>**Related Steps:**
- Choose a static site generator of your choice. In this example we will use "Jekyll".
- Create a file named \_config.yml.
- Choose a Jekyll theme to be applied on your resume.  

Your \_config.yml file should look something like this:
```yml
theme: jekyll-theme-minimal
title: "My Resume"
```

#### 3. Host documents on a Distributed Version Control System:
-  Distributed Version Control Systems can be a great source of hosting static websites or technical documentations.
-  They allow users to work on their documentation offline
-  Each update/commit applied to the documentation is stored in the history that alows the user to keep track of progress.
-  They also allow different users to make changes on same documentation.
>**Related Steps:**
- Create an account on a distributed version control system. In this example we will use Github.
- Create repository named username.github.io, where username is your username on GitHub.
- Add index.md and \_config.yml to your new Github repository.
- Create a Readme.md file to describe the content of your directory.
- Wait a few minutes after the initial commit and then go to "https://username.github.io" in your browser.

This is what your Github repository looks like once you add all the necessary files.
![](https://github.com/Aman-1313/Aman-1313.github.io/blob/5bf3457acacc7378fa951fcff77d21cd978174d4/ezgif.com-gif-maker.gif)
![](https://github.com/Aman-1313/Aman-1313.github.io/blob/79941696f019ffb8f0e757894071ebc5ee57e605/ezgif.com-video-to-gif.gif)
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

