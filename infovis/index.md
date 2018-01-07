---
layout: archive
title: "信息可视化作品集"
date: 2018-01-02T11:40:45-04:00

---
![image](https://lyanwaiting.github.io/images/故事.png)
https://public.tableau.com/views/1_5341/1_1?:embed=y&:display_count=yes

<div class="tiles">
{% for post in site.categories.posts infovis %}
  {% include post-grid.html %}
{% endfor %}
</div>
