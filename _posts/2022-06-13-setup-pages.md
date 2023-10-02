---
layout: post
title: How to set up a website in 5 minutes
date: 2010-01-01 12:00:00 +0200
description: 
img: github-pages.jpg
tags: [IT, web development] # add tag
---
1. Clone a Github repo with one of the free Jekyll templates. For example, this website uses [flexible-jekyll](https://jekyllthemes.io/theme/flexible-jekyll) theme.  or 

2. Publish on Github Pages following the instructions [here](https://pages.github.com/). In short:
- if your repo adress is https://github.com/user/repo, then your website will be published at https://user.github.io/repo,
- however, you can rename your repo to user.github.io which will publish your website at https://user.github.io without any subdomain,
- make sure that  the content of your Jekyll config file _config.yml matches the address of the Github repo:
>baseurl: "" 
>url: "https://user.github.io

3. If you want to build the website locally to preview the changes before pushing them to the public repo:
- first set up a server and click on the url to open it in a browser:
> jekyll s
- then, after every change you want to see applied in the website, just build without setting up a new server
> jekyll b
- refresh the website in your browser.
  
