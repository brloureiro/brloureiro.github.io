---
layout: page
permalink: /publications/
title: publications
description: Publications by categories in reversed chronological order. Authors are listed in alphabetical order.
years: [2020, 2019, 2018, 2016]
---

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}