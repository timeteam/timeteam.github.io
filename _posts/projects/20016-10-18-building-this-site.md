---
layout: post
title:  "Building this site"
date:   2016-10-18
category: 'jekyll and other software notes'
---

The following sources were used to build this site:

The <a href="https://github.com/smallmuou/Jekyll-Pithy">Pithy Theme</a>

The main jekyll sources of course:
[Jekyll docs][jekyll] 
[Jekyll’s dedicated Help repository][jekyll-help].

Assigning posts to multiple categories was easy but only when I realised that in "jekyll categories" != "category".  Thus this is legal 
categories: ['The is a category', 'This is another category'] 

and so is
category: ['A single category']

but this is not:
category:  ['The is a category', 'This is another category'] 


but also these are useful:
Documentation on <a href="https://github.com/jekyll/jekyll-help/issues/129">One multiple categories solution</a>

Documentation on <a href="https://amakelov.github.io/2015/11/24/multiple-categories-for-jekyll-posts.html">another solution</a>

Documentation on <a href="http://jekyllrb.com/docs/frontmatter/#predefined-global-variables">jekyll variables</a>

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help

