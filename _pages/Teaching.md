---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
collection: teaching
---

{% include base_path %}

{% for course in site.teaching %}
[{{ course.title }}]({{ course.url | relative_url }})
{% endfor %}