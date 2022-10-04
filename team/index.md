---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

This is the team.

{% include section.html %}

{% capture text %}
Ioannis Panageas is the principal investigator.
{%
  include feature.html
  image="images/portraits/Panageas.jpg"
  link="research"
  title="Get to know the members of our group"
  text=text
%}
{:.center}
{% endcapture %}

{% include list.html data="members" component="portrait" filters="tier: first" %}
{% include list.html data="members" component="portrait" filters="tier: second" %}
{% include list.html data="members" component="portrait" filters="tier: " %}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

These are our collaborators.

{% include section.html %}

## Join

#### Post Dogtoral Researcher

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

- 3+ (dog) years experience managing bone portfolios
- Strong desire to learn tricks and go on walkies
- Aptitude to sit and stay

{% include link.html type="external" link="https://google.com/" text="Apply Now" icon="" style="button" %}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

