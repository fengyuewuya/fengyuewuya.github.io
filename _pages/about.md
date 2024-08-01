---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Yang Zhang is presently a fourth-year Ph.D. student at the Gaoling School of Artificial Intelligence, Renmin University of China, under the guidance of Prof. Zhewei Wei. Prior to this, he attained his M.A.S degree in Software Engineering from the School of Computer Science, Central South University in June 2020.

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
