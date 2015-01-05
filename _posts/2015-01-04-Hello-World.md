---
layout: post
title: "Teaching myself how to set up a modern blog"
subtitle:   "Things have happened in web design since 1997"
date: 2015-01-04
author: "Jens Eriksson"
category: blog
tags: [jekyll, web design, how-to, html, markdown]
header-img: "img/2015-01-01-bg.jpg"
---

#Hello World!

This is my first real blog post. At the tender age of 34 I have decided to get myself a proper home page and to take up blogging. Actually, I imagine that this will be more like a project log for the different projects that I undertake, since it has been pointed out to me that people may in fact be interested in what I do for some reason.

Come to think of it, I did actually have a "homepage" back in 1997-ish, which was hosted on Geocities, I think. Like many of its contemporaries, it comprised of some horrible images overlaid on some even more horrible tiled background. It will be different this time around, I promise.

##What I have done
I'm writing this text in a text editor called [TextMate](http://macromates.com/), in a format called [kramdown](http://kramdown.gettalong.org/quickref.html "kramdown reference page"). Kramdown is just an extention of the super convenient [markdown](http://daringfireball.net/projects/markdown/ "markdown reference page") text-to-HTML tool. From the Markdown home page:

>Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML).

This is how my computer screen looks right now:

[![Screenshot][screenshot-location]][screenshot-location]

[screenshot-location]:{{ site.baseurl }}/img/2015-01-04-image-1.png

The image above is a link to the screenshot of how I got the screenshot to display as an image on the page, cool right? All I have done is to nest the structural element for an image ‘![][]’ inside if the element for a link ‘[][]’ (line 25) with a reference name called _screenshot-location_ (line 27) that points to the location of the image file. Super convenient!

The stuff at the top between the three dashes (lines 1-10) is called YAML frontmatter and is processed by the [Jekyll](http://jekyllrb.com/ "Jekyll home page") static site generator program in to a nice html structure, which is hosted on my [GitHub Pages](https://pages.github.com/ "GitHub Pages site")-page. These pages have way better tutorials on the specifics of how to use these tools, so I'm just linking to them. If you want to see the source code for this site, just klick [here](https://github.com/Oftatkofta/Oftatkofta.github.io), or on the Octocat icon in the footer and navigate to the repository named _oftatkofta.github.io_.



