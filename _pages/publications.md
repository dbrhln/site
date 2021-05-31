---
layout: page
permalink: /pubs/
title: papers & presentations
description:
years: [2021, 2020, 2019, 2017, 2015]
nav: true
order: 3
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
