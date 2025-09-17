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


**[Auditing Membership Leakages of Multi-Exit Networks](https://arxiv.org/abs/2208.11180)** [[pdf](http://Liu199604.github.io/files/CCS22-MultiExit.pdf)] [[code](https://github.com/zhenglisec/Multi-Exit-Privacy)]

Zheng Li, **Yiyong Liu**, Xinlei He, Ning Yu, Michael Backes, Yang Zhang

*In ACM SIGSAC Conference on Computer and Communications Security (CCS 2022)*

&nbsp; 

**[Membership Inference Attacks by Exploiting Loss Trajectory](https://arxiv.org/abs/2208.14933)** [[pdf](http://Liu199604.github.io/files/CCS22_TrajectoryMIA.pdf)] [[code](https://github.com/DennisLiu2022/Membership-Inference-Attacks-by-Exploiting-Loss-Trajectory)]

**Yiyong Liu**, Zhengyu Zhao, Michael Backes, Yang Zhang

*In ACM SIGSAC Conference on Computer and Communications Security (CCS 2022)*

&nbsp; 

**[SoK: Data Reconstruction Attacks Against Machine Learning Models: Definition, Metrics, and Benchmark](https://arxiv.org/pdf/2506.07888?)** [[pdf](http://Liu199604.github.io/files/reconstruction_usenix_2025.pdf)] [[code](https://zenodo.org/records/15603060)]

Rui Wen<sup>＊</sup>, **Yiyong Liu<sup>＊</sup>**, Michael Backes, Yang Zhang (<sup>＊</sup>Equal Contribution)

*In USENIX Security Symposium (USENIX Security 2025)*

&nbsp; 

