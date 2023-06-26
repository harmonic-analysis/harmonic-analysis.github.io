---
layout: default
title: Mathematical Physics
permalink: /mathematical-physics/
---
# 调和分析与数学物理

<div id="home">
    <h1>数学物理相关列表</h1>
    <ul class="posts">
        {% for post in site.categories.mathematical-physics %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
    </ul>
</div>