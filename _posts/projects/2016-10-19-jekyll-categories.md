---
layout: post
title:  "Jekyll categories"
date:   2016-10-19
category: 'software for websites'
---

---

**Assigning posts to multiple categories**

---


Assigning posts to multiple categories was easy but only when I realised that in jekyll

"categories" != "category"  

Thus, this works as expected: 

{% highlight ruby %}
categories: ['The is a category', 'This is another category'] 
{% endhighlight %}

and so does:

{% highlight ruby %}
category: ['A single category']
{% endhighlight %}

**but this does not**:

{% highlight ruby %}
category:  ['The is a category', 'This is another category'] 
{% endhighlight %}

**Other useful resources on jekyll categories**

<a href="https://github.com/jekyll/jekyll-help/issues/129">One multiple categories solution</a>

<a href="https://amakelov.github.io/2015/11/24/multiple-categories-for-jekyll-posts.html">another solution</a>

<a href="http://jekyllrb.com/docs/frontmatter/#predefined-global-variables">jekyll variables</a>

