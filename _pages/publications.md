---
layout: archive
title: "Publications and preprints"
permalink: /publications/
author_profile: true
---


You can also find my articles on [my Google scholar profile](https://scholar.google.com/citations?user=u0rkSl0AAAAJ&hl=en}).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
