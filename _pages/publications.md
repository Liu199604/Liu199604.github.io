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


**[Auditing Membership Leakages of Multi-Exit Networks](https://arxiv.org/abs/2208.11180)** [[pdf](https://arxiv.org/abs/2208.11180)] [[code](https://github.com/zhenglisec/Multi-Exit-Privacy)]

Zheng Li, **Yiyong Liu**, Xinlei He, Ning Yu, Michael Backes, Yang Zhang

*In ACM SIGSAC Conference on Computer and Communications Security (CCS 2022)*

&nbsp; 

**[Membership Inference Attacks by Exploiting Loss Trajectory](https://arxiv.org/abs/2208.14933)** [[pdf](https://arxiv.org/abs/2208.14933)] [[code](https://github.com/DennisLiu2022/Membership-Inference-Attacks-by-Exploiting-Loss-Trajectory)]

**Yiyong Liu**, Zhengyu Zhao, Michael Backes, Yang Zhang

*In ACM SIGSAC Conference on Computer and Communications Security (CCS 2022)*

&nbsp; 
