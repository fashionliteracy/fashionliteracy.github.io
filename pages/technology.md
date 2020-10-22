---
layout: page
show_meta: false
title: "Use of technology in Fashion"
subheadline: "Fashion and Technology"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/technology/"
---


<ul>
    {% for post in site.categories.technology %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
