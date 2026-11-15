---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

## Main Pages

- [About me]({{ '/' | relative_url }})
- [Research]({{ '/research/' | relative_url }})
- [Teaching]({{ '/teaching/' | relative_url }})
- [CV]({{ '/cv/' | relative_url }})

## Journal Publications

{% assign publications = site.publications | sort: 'date' | reverse %}
<ul>
{% for publication in publications %}
  <li><a href="{{ publication.url | relative_url }}">{{ publication.title }}</a></li>
{% endfor %}
</ul>

[XML sitemap]({{ '/sitemap.xml' | relative_url }})
