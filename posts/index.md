---
layout: archive
permalink: /
title: "可视化图形笔记"
---

<div class="tiles">
{% for post in site.categories.notes %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
