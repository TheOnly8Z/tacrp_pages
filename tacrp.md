---
layout: page
title: TacRP
---

<ul>
  {% for post in site.posts %}
    {%- if post.category == "TacRP" -%}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>