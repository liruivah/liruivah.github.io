---
layout: page
permalink: /projects/
title: projects
description: Research projects spanning Systems for AI, ML for Systems, and Pure Systems research areas.
nav: true
nav_order: 3
display_categories: [systems-for-ai, ml-for-systems, systems]
horizontal: true
---

<!-- pages/projects.md -->

<div class="section-header-bg" style="background-image: url('{{ '/assets/img/iceland.jpg' | relative_url }}'); background-size: cover; background-position: center 70%; height: 200px; border-radius: 10px; margin-bottom: 20px; position: relative;">
</div>

<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">
      {% case category %}
        {% when 'systems-for-ai' %}
          Systems for AI
        {% when 'ml-for-systems' %}
          ML for Systems
        {% when 'systems' %}
          Systems
        {% else %}
          {{ category }}
      {% endcase %}
    </h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display projects without categories -->

{% assign sorted_projects = site.projects | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-1">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>
