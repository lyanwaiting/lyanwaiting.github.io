---
layout: archive
title:  "信息可视化笔记"
date:   2017-11-30 22:07:50 +0800
modified:
excerpt: "涉及到visualization的内容"
tags: []
---

<div class="tiles">
{% for post in site.categories.infovisnotes %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovisnotes 的列出来-->
