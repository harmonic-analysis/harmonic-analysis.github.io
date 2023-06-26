---
layout: default
title: Core
permalink: /core/
---
# 调和分析核心问题

<div id="home">
    <h1>核心问题列表</h1>
    <ul class="posts">
        {% for post in site.categories.core %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
    </ul>
</div>