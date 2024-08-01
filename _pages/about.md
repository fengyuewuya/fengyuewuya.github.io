---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Yang Zhang is currently a fourth-year Ph.D. student at the Gaoling School of Artificial Intelligence at Renmin University of China, supervised by Professor Zhewei Wei. Prior to this, he obtained his Master's degree in Applied Statistics from the School of Statistics, Beijing Normal University, under the guidance of Professor Guangming Lv, in June 2017. Furthermore, he graduated with a Bachelor's degree in Statistics from Zhengzhou University in June 2015.

Research Interests
======
- Artificial Intelligence
- Graph Neural Networks
- Graph Neural Networks for Chemical, Physical and Biochemical
- Artificial Intelligence Security

Publication
======
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
