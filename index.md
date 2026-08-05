---
---

# Data Science Group @ Heidelberg University

Welcome to the Data Science Research Group at [Heidelberg University](https://www.uni-heidelberg.de/en). Our research focuses on the management, processing, and analysis of complex data, ranging from scientific datasets to large-scale text corpora.

We work at the intersection of data science, natural language processing (NLP), information retrieval, machine learning, and generative AI. Our goal is to develop methods and techniques for practical, user-centered tools that support chatbots, question-answering systems,  conversational AI, and transparent reasoning. Many of our [projects]({{ '/projects/' | relative_url }}) are interdisciplinary and connect to fields such as medicine, mental health, law, politics, and education.

In addition to our research, we offer courses, seminars, and software practicals at both introductory and advanced levels. For current and past offerings, please see our [teaching]({{ '/teaching/' | relative_url }}) page. Students interested in pursuing a Bachelor's or Master's thesis are encouraged to visit [this page]({{'/teaching/theses/'}}) first. If you are interested in an introductory or advanced research project, please feel free to [get in touch]({{ '/contact/' | relative_url }}). Open student research projects are typically presented at the beginning of lectures each semester.

{% include section.html %}

{% capture ws_notice %}
**Course Offerings in the Winter Semester 2026/27**

For information about the upcoming introductory class "Einführung in die Praktische Informatik (IPI)" as well as the seminar "Agentic AI for Problem Solving" and software practicals offered by our group, [see our winter semester 2026/27 courses]({{ '/teaching/winter-2026-27/' | relative_url }}).
{% endcapture %}

{% include alert.html type="info" content=ws_notice %}

## Highlights

{% capture text %}

Our research focuses on AI-driven methods that are common in many application domains, including intelligent search, knowledge graphs, neurosymbolic computing, reasoning, and conversational AI.

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
  image="images/Research-overview-small2.2026.02.08.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Get a quick overview of some of our current and past research projects, many of which address highly relevant interdisciplinary topics.

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
  image="images/MiaDDG.2026.02.08.icon.png"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We teach the enduring principles of data science and work to keep every course current with the latest methods and tools — from databases and text analytics to large language models and complex network analysis.

{%
  include button.html
  link="teaching"
  text="See all about our teaching"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Teaching-WordCloud.2026.02.08.png"
  link="teaching"
  title="Our Teaching"
  text=text
%}

{% capture text %}

Meet the people behind our work — a dedicated, interdisciplinary team driven by curiosity and a shared passion for both fundamental and application-oriented research.

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
  image="images/Team.2026.02.08.png"
  link="team"
  title="Our Team"
  flip=true
  style="bare"
  text=text
%}
