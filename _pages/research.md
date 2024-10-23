---
layout: page
permalink: /research/
title: Research
type: [WP, in progress]
nav: true
publications: false
---

### Working Papers
<div class="publications">
{% for y in page.type %}
  {% bibliography -f working_papers -q @*[abbr={{y}}]* %}
{% endfor %}
</div>


### Work in progress
<div class="publications">
{% for y in page.type %}
  {% bibliography -f ongoing -q @*[abbr={{y}}]* %}
{% endfor %}
</div>
