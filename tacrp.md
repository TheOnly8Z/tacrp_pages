---
layout: page
title: Tactical RP
permalink: /tacrp/
---

Breathe new life into the guns of an ill-fated shooter. Tactical RP is a remix and expansion of Tactical Intervention weapons that aims to make it more customizable, more fun, and more immersive.

## Posts
<ul>
  {% for post in site.posts %}
    {%- if post.category == "TacRP" -%}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>

## Links
- **[Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2588031232)**
- **[GitHub](https://github.com/HaodongMo/tacrp)**