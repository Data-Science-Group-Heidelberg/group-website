---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a team of computer scientist with a devotion for both application-oriented and fundamental research. 

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni

{% include grid.html style="square" content=content %}
