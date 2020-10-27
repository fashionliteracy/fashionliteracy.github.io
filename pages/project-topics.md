---
layout: page-fullwidth
show_meta: false
title: "Fashion project topics by FashionLiteracy"
subheadline: "College project topic ideas"
header:
   image_fullwidth: "header_project_topics.jpg"
permalink: "/resources/project-topics/"
---

<br>
<br>

> <h3> Coming Soon..</h3>
>
>
<ul>
    {% for post in site.categories.project-topics %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
