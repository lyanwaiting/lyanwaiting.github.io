---
layout: archive
title: "信息可视化作品集"
date: 2018-01-04T03:08:45-04:00
modified:
excerpt: "做过的可视化呀"
tags: []
image: 
  feature: 2.gif
  teaser: 
---

在此展示学生作品集，好的丶可改进的及有趣的

<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 portfolio 的列出來-->
