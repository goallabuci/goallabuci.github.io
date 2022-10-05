---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team


{% capture text %}
Principal Investigator: Ioannis Panageas{% endcapture %}

{%
  include feature.html
  image="images/portraits/Panageas.jpg"
  link="research"
  title="Meet our team"
  text=text
%}

{% include list.html data="members" component="portrait" filters="tier: first" %}
{% include list.html data="members" component="portrait" filters="tier: second" %}
{% include list.html data="members" component="portrait" filters="tier: " %}
{:.center}



{% include section.html %}
<strong> External Collaborators </strong>.

