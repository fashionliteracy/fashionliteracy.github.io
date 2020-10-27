---
layout: page-fullwidth
show_meta: false
title: "Books by FashionLiteracy"
subheadline: "Read our books on Fashion and technology"
header:
   image_fullwidth: "header_unsplash_8.jpg"
sitemap: false
permalink: "/products/books/"
---

<br>
<br>

> <h3> Coming Soon..</h3>
>
>
<ul>
    {% for post in site.categories.books %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
