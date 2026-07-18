---
layout: page
title: projects
permalink: /projects/
description: Research and technical projects.
nav: true
nav_order: 3
horizontal: false
---

Selected research and engineering projects in quantum devices, MEMS sensing, cosmological inference, and digital IC implementation.

{% assign sorted_projects = site.projects | sort: "importance" %}

{% if page.horizontal %}
{% for project in sorted_projects %}
{% include projects_horizontal.liquid %}
{% endfor %}
{% else %}
{% for project in sorted_projects %}
{% include projects.liquid %}
{% endfor %}
{% endif %}
