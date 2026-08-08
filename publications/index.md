---
title: Publications
description: Publications of the Data Science Group.
nav:
  order: 4
  tooltip: Our publications
redirect_from:
  - /projects/
---

# {% include icon.html icon="fa-solid fa-book" %}Publications

Publications of our group since 2023. For the complete list, see our [Google Scholar profile]({{ site.links["google-scholar-url"] }}) or the [DBLP entry](https://dblp.org/pid/g/MichaelGertz.html) of Michael Gertz.


<!-- 05.08.2026, Claude co-work
To add a publication from now on: put - id: doi:… (or arxiv:…) in _data/sources.yaml on work, open the PR, let CI push the regenerated citations back to the branch, then merge. The failure mode that was skipping deploys is gone.
-->


{% include section.html %}

## Highlighted

{% include citation.html lookup="NeSy-RAG: Neuro-Symbolic RAG for Explainable Question Answering" style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}
