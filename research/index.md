---
title: Research
nav:
  order: 2
  tooltip: Current and Past Research Projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Research Projects

<p style="text-align:center;"> Explore current and past research projects from the Machado Lab <p>

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Current Projects

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## Past Projects

{% include list.html component="card" data="projects" filter="!group" style="small" %}
