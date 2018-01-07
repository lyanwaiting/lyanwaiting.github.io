---
layout: archive
title: "网页设计作品集"
date: 2018-01-04T03:08:45-04:00
modified:
excerpt: "奉献给网页的无数夜晚"
tags: []
image: 
  feature: 1.gif
  teaser: 
---

在此展示学生作品集，好的丶可改进的及有趣的

[link](https://public.tableau.com/profile/.86047339#!/vizhome/GDP_221/1_1)

<div class="tiles">
{% for post in site.categories.infovis tableau %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis tableau 的列出來-->
