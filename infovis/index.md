---
layout: archive
title: "信息可视化作品集"
date: 2018-01-04T03:08:45-04:00
modified:
excerpt: "这里的东西见证着我熬过的夜，"
tags: []
image: 
  feature: Tbleau图标.jpg
  teaser: Tbleau图标.jpg
---



<div class="tiles">
{% for post in site.categories.tableau %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 tableau 的列出来-->
