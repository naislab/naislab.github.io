---
title: People
---

{% for member in site.people %}
  <img src="{{ member.image }}" alt="{{ member.name }}" style="border-radius: 50%; width: 256px; height: 256px; object-fit: cover;"/>
  <h2>{{ member.name }}</h2>
  <i>{{member.position }}</i>
  <p class="prose">{{ member.content | markdownify }}</p>
{% endfor %}