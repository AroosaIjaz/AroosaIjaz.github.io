---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
These publications may also be found on my <u><a href="https://scholar.google.com/citations?user=jvubDjMAAAAJ&hl=en&oi=ao">google scholar profile</a>.</u>

---
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
