---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a team of computer scientists with a devotion for both application-oriented and fundamental research. The group is led by Prof. Dr. rer. nat. Michael Gertz and currently includes the doctoral researchers Ashish Chouhan, Jonas Gann, Marina Walther, and Nicolas Reuter, supported by Natalia Ulrich in the group's office.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and role != 'secretary' and group != 'alum'" %}

<div>
{% include list.html data="members" component="portrait" filter="role == 'secretary' and group != 'alum'" %}
</div>

{% include section.html %}

## {% include icon.html icon="fa-solid fa-users" %}Alumni

[Our Alumni]({{ '/team/alumni/' | relative_url }})

