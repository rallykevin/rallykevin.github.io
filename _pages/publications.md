---
layout: page
permalink: /publications/
title: publications
description: The full list of publications can be found <a href="https://scholar.google.com/citations?hl=en&user=CsJKBq4AAAAJ">here</a>, my google scholar profile.
years: [2023, 2022, 2021]
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
