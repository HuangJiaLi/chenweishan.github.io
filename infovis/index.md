---
layout: archive
title: "信息可视化作品集"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: ""
tags: []
image: 
  feature: Information_visualization_web_sample_reels.gif
  teaser: Information_visualization_web_sample_reels.gif
---

在此展示作品——关于网页设计和信息可视化作品


<div class="tiles">
{% for post in site.categories.visualization %}
  {% include post-grid.html %}
{% endfor %}