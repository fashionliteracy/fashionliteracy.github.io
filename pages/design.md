---
layout: page
show_meta: false
title: "Fashion design, style, and trends"
subheadline: "Fashion and Lifestyle"
teaser: "Get articles and posts on latest designs, outfit ideas and lifestyle tips from FashionLiteracy"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/design-and-lifestyle/"
---

Coming soon..

<ul>
    {% for post in site.categories.lifestyle %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

<!--
<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
-->
