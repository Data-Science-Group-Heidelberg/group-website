---
title: Research
description: Research projects, datasets, and software of the Data Science Group.
nav:
  order: 3
  tooltip: Our research projects
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

Our research projects, together with the datasets, software, and other resources that come out of them.

{% include tags.html tags="publications, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
