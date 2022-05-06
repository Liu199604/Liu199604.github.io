---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**[Auditing Membership Leakages of Multi-Exit Networks]**
Zheng Li, **Yiyong Liu**, Xinlei He, Ning Yu, Michael Backes, Yang Zhang
*In ACM SIGSAC Conference on Computer and Communications Security (CCS 2022)*

&nbsp; 
