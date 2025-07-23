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
      <a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<p><strong>Number of publications:</strong> {{ site.publications | size }}</p>
