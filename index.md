---
---

# Data Science Group @ Heidelberg University

Welcome to the Data Science Research Group at Heidelberg University. Our research centers on the management, processing, and analysis of complex data — ranging from scientific data and large-scale text to evolving network data.

We work across data science, natural language processing (NLP), information retrieval and semantic search, machine learning and deep learning, complex network analysis, and Legal Tech. Many of our projects are interdisciplinary, reaching into the health sciences, law, politics, economics, physics, and biology.

Alongside our research, we offer a range of classes, seminars, and practicals at the introductory and advanced level — see our [teaching]({{ '/teaching/' | relative_url }}) page for the current courses. Students interested in joining the group for a Bachelor's or Master's thesis, or an introductory or advanced research project, are always welcome to [get in touch]({{ '/contact/' | relative_url }}).

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
