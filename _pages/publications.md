---
layout: page
permalink: /publications/
title: publications
description: Publications by categories in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="section-header-bg" style="background-image: url('{{ '/assets/img/yellowstone.jpg' | relative_url }}'); background-size: cover; background-position: center; height: 200px; border-radius: 10px; margin-bottom: 20px; position: relative;">
</div>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --group_by year --group_order descending %}

</div>
