---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order (since 2020). 
years: [2022,2021,2020]
nav: true
nav_order: 1
---
<font size =3>Please refer to <a href="https://dblp.org/pid/g/FrancescoGuerra.html">DBLP</a> or [Scopus](https://www.scopus.com/authid/detail.uri?authorId=23396829400) or [Google Scholar](https://scholar.google.com/citations?hl=it&user=s3L_fj0AAAAJ&view_op=list_works&authuser=2) for the complete list.</font>


<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
