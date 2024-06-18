---
layout: page
permalink: /research/
title: research
description: Work in progress
years: [2025,2024,2023,2022,2021,2020,2019,2018]
type: [WP soon, in progress]
nav: true
publications: false
---


### Work in progress
<div class="publications">

{% for y in page.years %}
  <!-- <h2 class="year">{{y}}</h2> -->
  {% bibliography -f ongoing -q @*[year={{y}}]* %}
{% endfor %}

</div>
