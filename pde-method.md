---
layout: default
title: PDE method
permalink: /pde-method/
---
# 调和分析的PDE方法

<div id="home">
    <h1>PDE方法列表</h1>
    <ul class="posts">
        {% for post in site.categories.pde-method %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
    </ul>
</div>