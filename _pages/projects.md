---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
# pagination:
#     enabled: true
#     collection: projects
#     sort_field: 'title'
#     sort_reverse: false
# date: 2024-07-30T03:02:20+00:00
---
This page lists a few projects I've completed in my career so far.
Most of these were either done for school, work, or as fun side-projects to get experience with then-unfamiliar technologies.

<!-- TODO: add Memory 2D -->

---

{% for post in site.projects %}
  {% include archive-single.html %}
  ---
{% endfor %}