---
layout: archive
title: "信息可视化作品集"
date: 2018-01-01
modified:
excerpt: ""
tags: []
image:
  feature:
  teaser:
---

<a href="/infovis/final_work/"><img src="/images/final_work.png" alt="期末信息可视化作品"></a>

---
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
