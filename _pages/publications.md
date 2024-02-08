---
layout: page
permalink: /publications/
title: Publications
description: Copyright notice. the material here is presented to ensure timely dissemination of scholarly and technical work. Copyright and all rights therein are retained by authors or by other copyright holders. All persons using this information are expected to adhere to the terms and constraints by author’s copyright. These works may not be reposted without the explicit permission of the copyright holder.
years: [2022, 2021, 2020]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
