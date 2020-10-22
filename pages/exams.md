---
layout: page
show_meta: false
title: "News on entrance exams of fashion colleges"
subheadline: "Fashion College exams News"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/news/exams/"
---

<br>
<br>

> <h3> Coming Soon..</h3>
>
>
<ul>
    {% for post in site.categories.examnews %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
