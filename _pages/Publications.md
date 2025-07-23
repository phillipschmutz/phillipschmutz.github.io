---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true       
---

{% include base_path %}

<article class="publication">
  <h3>{{ entry.title }}</h3>
  
  {% if entry.venue %}
    <p><strong>{{ entry.venue }}</strong>{% if entry.date %}, {{ entry.date | date: "%Y" }}{% endif %}</p>
  {% endif %}

  {% if entry.excerpt %}
    <p>{{ entry.excerpt }}</p>
  {% endif %}

  <p>
    {% if entry.DOI %}
      <a href="{{ entry.DOI }}" target="_blank">DOI</a>
    {% endif %}
    {% if entry.pdf %}
      {% if entry.DOI %} | {% endif %}
      <a href="{{ entry.pdf }}" target="_blank">PDF</a>
    {% endif %}
  </p>

  {% if entry.citation %}
    <p class="citation" style="font-size: 90%; color: gray;">{{ entry.citation | markdownify }}</p>
  {% endif %}
</article>





