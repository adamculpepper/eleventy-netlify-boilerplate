---
title: Services
date: 2020-07-29T04:10:45.619Z
permalink: /services/index.html
eleventyNavigation:
  order: 5
  key: Services
---
fsdfsd fsd fsad fffff 5

<ul>
{%- for services in collections.services -%}
  <li>{{ services.data.title }} - {{ services.url }}</li>
{%- endfor -%}
</ul>


<h3>Blog Posts</h3>
<ul>
{%- for post in collections.post -%}
  <li{% if page.url == post.url %} class="active"{% endif %}>{{ post.data.title }}</li>
{%- endfor -%}
</ul>