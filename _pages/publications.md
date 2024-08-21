---
layout: page
permalink: /publications/
title: publications
description: The full list of publications can be found in my google scholar profile. <a href="http://scholar.google.com/citations?user=CsJKBq4AAAAJ&hl=ko&oi=sra">SLINK</a>
years: [2025, 2023, 2022, 2021]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
