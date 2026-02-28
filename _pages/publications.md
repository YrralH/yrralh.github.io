---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

\* indicates corresponding author.

{% assign pubs = site.publications | sort: "date" | reverse %}
{% for post in pubs %}
  {% include archive-single.html %}
{% endfor %}
