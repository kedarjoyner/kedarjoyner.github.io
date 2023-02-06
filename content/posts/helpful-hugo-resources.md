---
title: "Helpful resources for learning Hugo"
date: 2023-02-05
draft: true
img: 
---

I've spend the past 48 hours learning [Hugo](https://gohugo.io/) and stumbled upon a few useful resources that might help others who want to learn. 

## Should I use Hugo?

If you're not a developer or don't want to be, you probably should use Hugo. Checkout simpler static site generators like [Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll) and [11nty](https://www.11ty.dev/) instead. 
 
If you need a simple blog or portfolio site and have little experience writing code, Hugo is probably not for you. [This article](https://arun.is/blog/choosing-a-static-site-generator/) from a product designer name Arun helped me make narrow down my choices for a static site generator. "Stick with what's familiar" and "Find a generator with plenty of support" are key. 

Honestly, Hugo is more complicated than *what I even need* but I had a few goals that made the experience valuable to me (so far). I wanted to... 

1. build a portfolio site that is simple and accessible
2. move my existing Squarespace site to <a target="_blank" href="https://pages.github.com/">Github Pages</a> to save on hosting costs
3. get back into learning web development

Hugo has a steep learning curve and the documentation needs *a lot* of work, but I was looking for a challenge and that's what I got. I still haven't figured it out yet 😅.

## Consider starting with a theme

As of this blog post, I'm using the [Congo](https://jpanther.github.io/congo/docs/) theme, because I wanted to use [Tailwind CSS](https://tailwindcss.com/) and it has 600+ followers with an active community. Just today, the creator responded to my three different annoying questions (Hi, James! Thank you! 🙏). Because Hugos's documentation is quite confusing, I thought it would be helpful to learn with a theme so I can understand best practices. 

It took me hours to figure out, but it's best to use a [module for adding a theme](https://gohugo.io/hugo-modules/use-modules/#use-a-module-for-a-theme) to your project rather than submodules. A lot of website tutorials haven't updated their documentation yet, but it's Hugo's recommended method for adding themes now.

Modules make it easier to swap themes in the future, upgrade the theme as it changes, and also protect you from editing the original theme files (always override, don't edit them directly!). 

I'm sure there are more technical benefits that I'm not aware of, but I'm the world's `okayest` developer and don't always understand the more complicated bits 👾. 

## Auto deploying a Hugo site to Github Pages 

Okay, this was an absolute b*t$h to figure out but my site now auto-deploys to my `gh-page`s branch using Git Workflows/Actions, but it was a pain to figure out. 

First, follow Hugo's tutorial on how to [host on GitHub](https://gohugo.io/hosting-and-deployment/hosting-on-github/). 

Second, make sure your 









