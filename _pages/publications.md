---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This is a list of selected publications throughout my academic career in which I've participated heavily. You can find all of my publications, including those mentioned below, on my [Google Scholar](https://scholar.google.com/citations?user=2Ak0HH8AAAAJ&hl=en).

-----
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
