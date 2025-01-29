---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

News
======
1.	[Sep. 2024] I am now pursuing my PhD degree at UCLA!
2.	[Oct. 2022] I started working as a Robotics Systems Engineer at [Mantis Robotics](https://www.mantis-robotics.com/).
3.	[June 2022] I received my Master’s degree in Electrical Engineering from NTU!


Projects
======
{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}

Publications
======
{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}
