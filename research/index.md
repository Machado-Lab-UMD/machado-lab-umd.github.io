---
title: Research
nav:
  order: 2
  tooltip: Current and Past Projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Research Projects

Explore current and past research projects from the Machado Lab

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Current Projects

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## Past Projects

{% include list.html component="card" data="projects" filter="!group" style="small" %}
