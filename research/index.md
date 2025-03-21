---
title: Research
nav:
  order: 2
  tooltip: Current and Past Projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Current Projects

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## Past Projects

{% include list.html component="card" data="projects" filter="!group" style="small" %}
