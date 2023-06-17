---
layout: default
title: Harmonic Analysis
---

<div id="home">
  <h1>调和分析介绍</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

  <h1>团队核心介绍</h1>
  <ul class="posts">
    miao
<!--     <li><span>01 May 2019</span> &raquo; <a href="https://inkscape.org/zh/learn/tutorials/"> Inkscape 教程</a></li>  -->
  </ul>

</div>
