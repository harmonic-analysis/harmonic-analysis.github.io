---
layout: default
title: Harmonic Analysis
---

<div id="home">
  <h1>个人文章列表</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

  <h1>好文推荐</h1>
  <ul class="posts">
    <li><span>01 May 2019</span> &raquo; <a href="https://inkscape.org/zh/learn/tutorials/"> Inkscape 教程</a></li> 
  
  </ul>

</div>
