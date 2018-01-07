---
layout: archive
title: "信息可视化笔记"
date: 2018-01-01
modified:
excerpt: ""
tags: []
image:
  feature: global.jpg
  teaser:
---
在此展示笔记

---
<div class="tiles">
{% for post in site.categories.posts_infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 posts_infovis 的列出来-->
