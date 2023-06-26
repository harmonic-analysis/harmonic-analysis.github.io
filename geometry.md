---
layout: default
title: Geometry
permalink: /geometry/
---
# 调和分析在几何中应用

<div id="home">
    <h1>几何应用列表</h1>
    <ul class="posts">
        {% for post in site.categories.geometry %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
    </ul>
</div>