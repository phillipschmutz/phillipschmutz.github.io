---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<ul>
{% for post in site.publications %}
  <li>{{ post.date }} – <a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>






