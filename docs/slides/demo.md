<!-- .slide: data-state="layout-title"  -->

# Getting Started with GitHub Actions 

<br>

## by Adil Shehzad 

<p>Learn how to automate, customize, and execute your software development workflows right in your GitHub repository with GitHub Actions.</p>
<p class="no-fragment btn-group" role="group" aria-label="Basic example">
<a class="btn btn-lg btn-warning text-dark" href="https://github.com/adilshehzad786/Getting-Started-with-GitHub-Actions" target="_blank">Github Repo</a>
<a class="btn btn-lg btn-light text-dark" href="https://githubactionsbyadil.netlify.app/" target="_blank">Demo</a>
</p>

<p class="no-fragment small mt-4"><span class="badge bg-light text-dark mr-1 ml-2">&larr; &rarr;</span> navigate
<span class="badge bg-light text-dark mr-1 ml-2">t</span>toolbar
<span class="badge bg-light text-dark mr-1 ml-2">m</span>menu
<span class="badge bg-light text-dark mr-1 ml-2">esc</span>overview</p>

---
<!-- .slide: data-state="layout-mostly-image" data-width="300" data-height="300" data-background-image="images/Adil Shehzad.png" -->

# About Me

</small>

- GitHub Campus Expert  <a class="btn btn-success btn-lg text-white fab fa-github-alt" href="https://linktr.ee/adilshehzad786"> </a>
- GitHub Streamer at GitHub <a class="btn btn-success btn-lg text-white fab fa-github-alt" href="https://linktr.ee/adilshehzad786"> </a>
- Software Developer at Grey Software CA

<a class="btn btn-danger btn-lg text-white fab fa fa-tree" href="https://linktr.ee/adilshehzad786"></a> <a class="btn btn-primary btn-lg text-white fab fa-linkedin-in" href="https://www.linkedin.com/in/adilshehzad7/"></a> <a class="btn btn-success btn-lg text-white fab fa-github-alt" href="https://github.com/adilshehzad786"></a>

---

# Understanding the GitHub flow

<br>

GitHub flow is a lightweight, branch-based workflow that supports teams and projects where deployments are made regularly.
[GitHub flow Graph](https://guides.github.com/introduction/flow/)

<!-- .element class="fragment" style="font-size: .8em" -->

<ul class="list-group mt-3">
  <li class="list-group-item fragment fade-right">
  <i class="twa twa-raising-hands"></i> Create a branch </li>
  <li class="list-group-item fragment fade-right">
  <i class="twa twa-raising-hands"></i> Open a Pull Request</li>
  <li class="list-group-item fragment fade-right">
  <i class="twa twa-raising-hands"></i> Deploy </li>
  <li class="list-group-item fragment fade-right">
    <i class="twa twa-raising-hands"></i> Merge
  </li>
  
  
</ul>

---

# Demo : Understanding the GitHub flow

---

<!-- .slide: data-state="layout-title" data-transition="zoom" class="bg-dark"-->

# What are GitHub Actions ?

<p>Automate, customize, and execute your software development 
workflows right in your repository with GitHub Actions. 
You can discover, create, and share actions to perform any job you'd like,
including CI/CD, and combine actions in a completely customized workflow. </p>

---

# GitHub Actions Workflow

<iframe width="560" height="315" src="https://www.youtube.com/embed/cP0I9w2coGU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---
# Demo : Hello World GitHub Action Workflow

<iframe 
    width="100%"
    height="350"    
    src="data:text/html;charset=utf-8,
    <head><base target='_blank' /></head>
    <body><script src='https://gist.github.com/adilshehzad786/c84e7d4807b87c72a3d0f33ff47e7999.js'></script>
    </body>">
---
## Navigating Workflow 
---

<!-- .slide: data-state="layout-circles" -->

# Github Events

- name
- on
- env
- jobs
- steps

---
# name

<iframe 
    width="100%"
    height="350"    
    src="data:text/html;charset=utf-8,
    <head><base target='_blank' /></head>
    <body><script src='https://gist.github.com/nashmaniac/4b8d7b563c346b0ee09dd65bb959ebbf.js'></script>
    </body>">
---
# on

<iframe 
    width="100%"
    height="350"    
    src="data:text/html;charset=utf-8,
    <head><base target='_blank' /></head>
    <body><script src='https://gist.github.com/nashmaniac/55e32caa36c3e43f65bc353363c7d7ac.js'></script>
    </body>">
---

# env

<iframe 
    width="100%"
    height="350"    
    src="data:text/html;charset=utf-8,
    <head><base target='_blank' /></head>
    <body><script src='https://gist.github.com/nashmaniac/38e5026294074ca69f536bd168c4f959.js'></script>
    </body>">
---

# jobs

<iframe 
    width="100%"
    height="350"    
    src="data:text/html;charset=utf-8,
    <head><base target='_blank' /></head>
    <body><script src='https://gist.github.com/nashmaniac/3772cebeec07b3b8ee3f4b82071d17bd.js'></script>
    </body>">


---

---

# steps

<iframe 
    width="100%"
    height="350"    
    src="data:text/html;charset=utf-8,
    <head><base target='_blank' /></head>
    <body><script src='https://gist.github.com/nashmaniac/0b2d2884bfde8282167d4ff53646a0dd.js'></script>
    </body>">

    
---

# GitHub Secrets

<iframe 
    width="100%"
    height="350"    
    src="data:text/html;charset=utf-8,
    <head><base target='_blank' /></head>
    <body><script src='https://gist.github.com/adilshehzad786/969ffbe7fed0ea06d5519fb426534f2e.js'></script>
    </body>">
---
## Demo : GitHub Events & GitHub Secrets

---

# Overview # 1

<!-- .slide: data-state="layout-quote" class="bg-dark" -->

<blockquote class="animate__animated animate__backInDown">
 <i class="fa fa-quote-left text-secondary " aria-hidden="true"></i>
 Actions are your reusable units of code 
 <i class="fa fa-quote-right text-secondary" aria-hidden="true"></i> 
</blockquote>

---
# Overview # 2

<!-- .slide: data-state="layout-quote" class="bg-dark" -->

<blockquote class="animate__animated animate__backInDown">
 <i class="fa fa-quote-left text-secondary " aria-hidden="true"></i>
 You can use Action from the marketplace or create your own 
 <i class="fa fa-quote-right text-secondary" aria-hidden="true"></i> 
</blockquote>

---
# Overview # 3

<!-- .slide: data-state="layout-quote" class="bg-dark" -->

<blockquote class="animate__animated animate__backInDown">
 <i class="fa fa-quote-left text-secondary " aria-hidden="true"></i>
 Create custom CI workflow that automates building and testing our code
 <i class="fa fa-quote-right text-secondary" aria-hidden="true"></i> 
</blockquote>

---

# Overview # 4

<!-- .slide: data-state="layout-quote" class="bg-dark" -->

<blockquote class="animate__animated animate__backInDown">
 <i class="fa fa-quote-left text-secondary " aria-hidden="true"></i>
 Create custom CD workflow to automatically deploy our 
 code to any cloud self-hosted service or platform from our repo
 <i class="fa fa-quote-right text-secondary" aria-hidden="true"></i> 
</blockquote>

---

# Become a GitHub Actions Hero

<a class="btn btn-success btn-lg text-white fab fa-github-alt" href="https://github-actions-hero.now.sh/" target="_blank"> </a>



---

# What is Continuous integration

<p>Continuous Integration is a development practice where developers 
integrate code into a shared repository frequently where each integration 
is verified by an automated build and automated test. </p>

---
# Demo : Continuous integration

<iframe 
    width="100%"
    height="350"    
    src="data:text/html;charset=utf-8,
    <head><base target='_blank' /></head>
    <body><script src='https://gist.github.com/adilshehzad786/55132e4cb5ee879921333edc024de717.js'></script>
    </body>">

---

## Multiple Jobs 

<iframe 
    width="100%"
    height="350"    
    src="data:text/html;charset=utf-8,
    <head><base target='_blank' /></head>
    <body><script src='https://gist.github.com/adilshehzad786/e72cf0df261dbc64d6ae481983157ce3.js'></script>
    </body>">

---
# Pull Request GitHub Action 

<iframe 
    width="100%"
    height="350"    
    src="data:text/html;charset=utf-8,
    <head><base target='_blank' /></head>
    <body><script src='https://gist.github.com/adilshehzad786/25cd7431cf3e559376dc96b685704f69.js'></script>
    </body>">


---
# Branch Protection on GitHub 

---
# Project : Creating MEME Using GitHub Actions 

<iframe 
    width="100%"
    height="350"    
    src="data:text/html;charset=utf-8,
    <head><base target='_blank' /></head>
    <body><script src='https://gist.github.com/adilshehzad786/3bd76db40b5c3e700fd80d7925d7ed3d.js'></script>
    </body>">

---

# Command for Giphy 

<!-- .slide: data-state="layout-quote" class="bg-dark" -->
<blockquote class="animate__animated animate__backInDown">
 <i class="fa fa-quote-left text-secondary " aria-hidden="true"></i>
/giphy its so cool
 <i class="fa fa-quote-right text-secondary" aria-hidden="true"></i> 
</blockquote>



---

# GitHub Learning 

<a class="btn btn-success btn-lg text-white fab fa-github-alt" href="https://lab.github.com/" target="_blank"> GitHub Learning </a>

---

# Feedback

<a class="btn btn-info btn-lg text-white fas fa-comments" href="https://linktr.ee/adilshehzad786" target="_blank"> FeedBack </a>

---