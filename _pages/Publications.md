---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<ul>
  {% for post in site.publications %}
    <li>
      {{ post.date | date: "%Y" }} —
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<p>Number of publications: {{ site.publications | size }}</p>

