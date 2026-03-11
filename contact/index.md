---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Prof. Dr. Michael Gertz
Institut für Informatik
Im Neuenheimer Feld 205
69120 Heidelberg
GERMANY
{:.left}

{%
  include button.html
  type="email"
  text="gertz@informatik.uni-heidelberg.de"
  link="gertz@informatik.uni-heidelberg.de"
%}
{%
  include button.html
  type="phone"
  text="+49 (0) 6221 / 54 - 14352"
  link="+49 (0) 6221 / 54 - 14352"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="[https://www.google.com/maps](https://www.google.com/maps/place/Im+Neuenheimer+Feld+205,+69120+Heidelberg/@49.4174999,8.6729613,17z/data=!3m1!4b1!4m6!3m5!1s0x4797c1300f1a5095:0x38e6570ca1f68216!8m2!3d49.4174964!4d8.6755416!16s%2Fg%2F11c22h6y0q?entry=ttu&g_ep=EgoyMDI2MDMwOC4wIKXMDSoASAFQAw%3D%3D)"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
