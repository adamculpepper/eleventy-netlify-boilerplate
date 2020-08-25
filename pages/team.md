---
title: Team
date: 2020-07-29T04:10:45.619Z
permalink: /team/index.html
eleventyNavigation:
  order: 6
  key: Team
---


<ul>
{%- for services in collections.team -%}
  <li>{{ team.data.title }} - {{ team.url }}</li>
{%- endfor -%}
</ul>


<h3>Blog Posts</h3>
<ul>
{%- for post in collections.post -%}
  <li{% if page.url == post.url %} class="active"{% endif %}>{{ post.data.title }}</li>
{%- endfor -%}
</ul>