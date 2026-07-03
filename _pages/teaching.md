---
layout: page
permalink: /teaching/
title: teaching
description: Teaching activities and course materials.
nav: true
nav_order: 6
calendar: false
---

Teaching materials and course information will appear here as they are added.

{% if site.teachings and site.teachings.size > 0 %}
{% include courses.liquid %}
{% endif %}
