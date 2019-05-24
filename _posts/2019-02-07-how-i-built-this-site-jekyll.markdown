---
layout: post
title:  "How I built this site with Jeykll"
date:   2019-02-07 23:00:00 -0500
categories: general
---

I used Jekyll and GitHub Pages.

Jekyll is a static website generator.
GitHub Pages has limited free hosting for static websites.

See the source code for this site here: <https://github.com/coryBove/blog>

Check out the ```_posts/``` directory. You will notice that everything with a .md(markdown) file extension has minimal markup.

If you open your developer tools (usually F12) you will notice this page is an html file. Why is it different from the source code .md file? Because Jekyll is magical. It converts the markdown to HTML.

I won't attempt to explain how it works, because I don't know. I just know that it does work. If you're interested in building your own static website using Jekyll, do a quick google search for GitHub Pages and/or Jekyll. These organizations have some really great documentation.

Basic steps:
* Create a GitHub repository.
* Download/install Ruby and Jekyll.
* Run ```jekyll new blog``` from the command line. This generates your site.
* Add the generated files to your github repo, and set it up to use GitHub pages.

This is a minimal rundown of what it takes to generate a relatively simple website like the one you're reading this on.

Jeykll helps me quickly create content on the site without worrying about tedious HTML or CSS syntax. HTML and CSS are fun and all, but I'd rather not deal with them extensively. If you want to do that, Jekyll themes can be customized to your liking. I've made some small modifications to the theme I'm using - minima - on this website. If you're interested in how that works, see the jekyll-theme minima documentation on GitHub. You can use this repo as an additional example of customization.

I've often thought it could be profitable to build static websites for companies/people using the techniques I've used here. I may write about that in the future.

Here are some links for further exploration:
* GitHub Pages - <https://pages.github.com/>
* Jekyll Quickstart - <https://jekyllrb.com/docs/> (I go here all the time because I constistently forget the syntax to run jekyll)
* minima GitHub - <https://github.com/jekyll/minima>
* The repo this website is at - check out the .md(markdown) files to see how minimal the markup is for the pages on this site - <https://github.com/coryBove/blog>