---
layout: page
title: Projects
permalink: /projects/
---
<ul>
{% for project in site.projects %}
  <li>
    <a href="{{ project.project_url }}">{{ project.title }}</a> – {{ project.description | truncate: 100, '...' }}
  </li>
{% endfor %}
</ul>
