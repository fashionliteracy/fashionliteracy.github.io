---
layout: page-fullwidth
show_meta: false
title: "Industry news on fashion and technology"
subheadline: "Fashion industry news"
header:
   image_fullwidth: "header_industry.jpg"
sitemap: false
permalink: "/news/industry/"
---


<br>
<br>

> <h3> Coming Soon..</h3>
>
>
<ul>
    {% for post in site.categories.industrynews %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
