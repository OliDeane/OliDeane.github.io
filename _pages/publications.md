---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---



{% include base_path %}

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=Rm72wWEAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.</u>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
