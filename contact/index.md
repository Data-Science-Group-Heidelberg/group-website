---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

{% capture col1 %}
Prof. Dr. Michael Gertz<br>
Institut für Informatik<br>
Im Neuenheimer Feld 205<br>
69120 Heidelberg<br>

GERMANY
{:.left}
{% endcapture %}

{% capture col2 %}
<div style="max-width: 300px; margin: auto;">
  {% include figure.html image="images/Mathematikon_6.png" link="https://www.informatik.uni-heidelberg.de/about/mathematikon#start" %}
</div>
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{%
  include button.html
  type="email"
  text="gertz(@)informatik.uni-heidelberg.de"
  link="gertz(@)informatik.uni-heidelberg.de"
%}
{%
  include button.html
  type="phone"
  text="+49 (0)6221 / 5414352"
  link="+49 (0)6221 / 5414352"
%}
{%
  include button.html
  type="directions"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Im+Neuenheimer+Feld+205,+69120+Heidelberg/@49.4174999,8.6729613,17z/data=!3m1!4b1!4m6!3m5!1s0x4797c1300f1a5095:0x38e6570ca1f68216!8m2!3d49.4174964!4d8.6755416!16s%2Fg%2F11c22h6y0q?entry=ttu&g_ep=EgoyMDI2MDMwOC4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}


