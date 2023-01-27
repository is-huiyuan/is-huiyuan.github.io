---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Working papers
======
* B.S. in Beijing, Renmin University of China, 2012
* M.S. in Beijing, Renmin University of China, 2015
* Ph.D in Hong Kong, City University of Hong Kong, 2019

Publications
======
* 2019.08~2021.12: Assistant Professor
  * Shanghai International Studies University

* Since 2022.01: Associate Professor
  * Shanghai International Studies University

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


