---
layout: page
permalink: /publications/
title: Publications
description: My Publications
years: [2026, 2025, 2024, 2023]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
<!-- Will come soon! -->
