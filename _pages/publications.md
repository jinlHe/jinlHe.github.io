---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

* PERS: Parameter-Efficient Multi-modal Transfer Learning for Remote Sensing Visual Question Answering <br>
<b>Jinlong He</b>, Pengfei Li, Gang Liu*, Xiaonan Su, Wenhua Jiang and Shenjun Zhong <br>
IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (JStars), vol. 17, pp. 14823-14835, 2024, doi: 10.1109/JSTARS.2024.3447086. (2024 IF 4.7)
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
