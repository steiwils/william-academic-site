---
authors:
- admin
categories:
- Demo
date: "2023-09-07T00:00:00Z"
draft: false
featured: false
image:
  caption: 'Image credit: [**Pexels**](Photo by Vie Studio from Pexels: https://www.pexels.com/photo/hello-word-with-smiley-6168067/)'
  focal_point: ""
  placement: 2
  preview_only: false
lastmod: "2020-12-13T00:00:00Z"
projects: []
subtitle: "Welcome \U0001F44B this is my first post on my new site. Let me explain what I'm trying to do here."
summary: "Welcome \U0001F44B this is my first post on my new site. Let me explain what I'm trying to do here.."
tags:
- Academic
title: Hello World! The Start of Something New.
---

```python
import libr
print('hello world!')
```

## My Personal Website Plans

This is my first successful attemp at making a personal website. I've tried in the past, but was never able to quite get the aesthetic right. This will not be the final form of this website either, but I'm already at a much better place with its construction than I was in the past. 

I hope to have this website be a bit of a digital resume, profile and portfolio, along with general blog about my thoughts and works in a professional or quasi-professional manner. You'll probably see some things about courses I'm taking to continue developing in data science and artificial intelligence, but don't be surprised to see something related to urbanism of [Strong Towns](https://www.strongtowns.org/) related analysis. 

The **Posts** section of this website is meant to be a little more relaxed, yet informative. Whatever deep learning projects I find interesting enough, I'll include a post related to it here. But like I said, you might find posts related to other topics here too!


## Building the Website

A quick note on the construction of this website. I'll probalby include a more thourough explination on how I did this in a dedicated post, but for now let me give you the brief rundown. 

I am using [blogdown](https://github.com/rstudio/blogdown) in R and the [Hugo](https://gohugo.io/) theme [Academic](https://github.com/wowchemy/starter-hugo-academic) from [Wowcemy](https://wowchemy.com/). I've built this website starting in 2023, and at the time there were some tutorials I found that referenced a `content/home/` folder. When I followed the instructions seen [here](https://bookdown.org/yihui/blogdown/a-quick-example.html) and in this [video](https://youtu.be/BHpkLJieXPE?si=jLyEVS93XuaZnynd), I did not get this `content/home/` folder. Instead, I got a lot of `_index.md` files in the `content/` folder. From what I can gather, these markdown files are the stand ins for the `content/home/` organization that was seen previously. If you open one of these files, and run the `blogdown::serve_site()` command, you should be able to start playing around with to contents of the markdown files, and see what they do to the starter site. This is a little less intuitive than my previous `blogdown` experience where you interacted with `.Rmd` files and then knitted them to reflect the changes or additions to your site, but with a little time and patience I (and hopefully you) was able to figure it out.


Any how, thanks for stopping by. I hope you find something interesting!


Peace, 

William

