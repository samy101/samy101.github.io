---
layout: page
permalink: /publications/
title: publications
years: [2023, 2022, 2021, 2020, 2019, 2018, 2016, 2015, 2013, 2012, 2011]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2>{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
