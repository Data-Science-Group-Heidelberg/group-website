---
---

# Data Science Group @ Heidelberg University

Welcome to the Data Science Research Group at [Heidelberg University](https://www.uni-heidelberg.de/en). Our research centers on the management, processing, and analysis of complex data — ranging from scientific data to large-scale text corpora.

We work across data science, natural language processing (NLP), information retrieval, machine learning, and deep learning. Our focus is on the development of methods and techniques aimed at application and user-centric tools supporting chatbots, QA-systems, and conversational AI. Many of our [projects]({{ '/projects/' | relative_url }}) are interdisciplinary, reaching in particular into the domains of medicine, mental health, law, politics, and education.

Alongside our research, we offer a range of classes, seminars, and software practicals at the introductory and advanced level — see our [teaching]({{ '/teaching/' | relative_url }}) page for  current and past courses. Students interested in joining the group for a Bachelor's or Master's thesis are advised to first visit [this page]({{'/teaching/theses/'}}). If you are interested in introductory or advanced research project, you are welcome to [get in touch]({{ '/contact/' | relative_url }}). Open student research projects are typically presented at the beginning of the lectures each semester. 

{% include section.html %}

{% capture ws_notice %}
**Course Offerings in the Winter Semester 2026/27**

For information about the upcoming introductory class "Einführung in die Praktische Informatik (IPI)" as well as the seminar "Agentic AI for Problem Solving" and software practicals offered by our group, [see our winter semester 2026/27 courses]({{ '/teaching/winter-2026-27/' | relative_url }})
{% endcapture %}

{% include alert.html type="info" content=ws_notice %}

## Highlights

{% capture text %}

Our research focuses on AI-driven technologies in support of divers application domains and types, including semantic search, chatbots, knowledge graphs, reasoning, and conversational AI.

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
  image="images/MiaDDG.2026.02.08.icon.png"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We teach the enduring principles of data science and work to keep every course current with the latest methods and tools — from databases and text analytics to NLP and network analysis.

{%
  include button.html
  link="teaching"
  text="See our courses"
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
  image="images/Team.2026.02.08.png"
  link="team"
  title="Our Team"
  flip=true
  style="bare"
  text=text
%}
