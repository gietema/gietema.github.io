---
layout: default
title:  "Publishing bookmarks"
date:   2020-06-13 23:31:23 +0100
categories: posts
published: true
---
# Publishing Bookmarks

The links on my bookmarks page are automatically synced from [pocket](https://getpocket.com/).  
I got the idea to do this from [Luke Miles](https://lukemil.es/blog/publishing-my-bookmarks).

#### How does it work?
1. I save articles I want to read on pocket.  
1. On my server, I run a small script that checks if anything new is added to my pocket list with the tag 'public'.
1. If it finds something that was not added to my bookmarks page yet, it adds the new link to the file that contains my bookmarks and commits and pushes it to GitHub.
1. [GitHub Pages](https://pages.github.com/) makes sure that the new change is deployed to this website automatically. 


[Here](https://github.com/gietema/bookmarks) is the code.
