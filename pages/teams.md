---
title: Teams
date: 2020-08-02T04:10:45.619Z
permalink: /teams/index.html
eleventyNavigation:
  order: 6
  key: Teams
---

<h1>Team Members</h1>
<ul>
{%- for teams in collections.teams -%}
	<li>{{ teams.data.title }} - {{ teams.url }}</li>
{%- endfor -%}
</ul>