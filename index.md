---
layout: default
title: Harmonic Analysis
---

![avatar](/harmonic-analysis.png)


<div id="home">
  <h1>调和分析介绍</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

  <h1>核心问题介绍</h1>
  <ul class="posts">
    主要研究
  <div><a class="extra" href="/core">更多详情</a></div>
  </ul>
  

</div>
