---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team GOAL Laboratory 


{% capture text %}
<strong> Principal Investigator </strong>: [Ioannis Panageas](https://panageas.github.io/){% endcapture %}

{%
  include feature.html
  image="images/portraits/Panageas.jpg"
  link="https://panageas.github.io/"
  text=text
%}

{% include list.html data="members" component="portrait" filters="tier: first" %}
{% include list.html data="members" component="portrait" filters="tier: second" %}
{% include list.html data="members" component="portrait" filters="tier: " %}
{:.center}



{% include section.html %}
<strong> External Collaborators </strong>.

