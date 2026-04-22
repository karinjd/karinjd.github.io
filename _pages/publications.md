---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find the most up-to-date publications list on [Google Scholar](https://scholar.google.com/citations?user=3jNZ2IYAAAAJ).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
