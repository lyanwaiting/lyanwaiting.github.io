---
layout: archive
title: "信息可视化作品集"
date: 2018-01-07T23:08:45-04:00
modified:
excerpt: ""
tags: []
image: 
  feature: 
  teaser: 111.jpg
---

![image](https://Huangj0830.github.io/images/111.jpg)

<div class="tiles">
{% for post in site.categories.infovis tableau %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis tableau 的列出来-->
</body>
</html>
