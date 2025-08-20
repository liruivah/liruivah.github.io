---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 4
cv_pdf: assets/pdf/cv.pdf
description: My academic and professional experience, including research positions, publications, and awards.
---

<div class="section-header-bg" style="background-image: url('{{ '/assets/img/prague.jpg' | relative_url }}'); background-size: cover; background-position: center 60%; height: 200px; border-radius: 10px; margin-bottom: 20px; position: relative;">
</div>

<div class="cv">
  <div class="text-center mb-4">
    <a href="{{ page.cv_pdf }}" target="_blank" class="btn btn-primary">
      <i class="fa-solid fa-file-pdf"></i> Download CV (PDF)
    </a>
  </div>

  {% for entry in site.data.cv %}
    <div class="card mt-3 p-3">
      <h3 class="card-title font-weight-medium">{{ entry.title }}</h3>
      <div>
        {% if entry.type == 'list' %}
          {% include cv/list.liquid %}
        {% elsif entry.type == 'map' %}
          {% include cv/map.liquid %}
        {% elsif entry.type == 'nested_list' %}
          {% include cv/nested_list.liquid %}
        {% elsif entry.type == 'time_table' %}
          {% include cv/time_table.liquid %}
        {% elsif entry.type == 'list_groups' %}
          {% include cv/list_groups.liquid %}
        {% else %}
          {{ entry.contents }}
        {% endif %}
      </div>
    </div>
  {% endfor %}
</div>
