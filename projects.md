---
layout: page
title: Projects
permalink: /projects/
---

<ul>
    {% for project in site.data.projects %}
    <li>
      <a href= "{{project.url}}">
        {{project.name}}
      </a>
      <p>{{project.description}}</p>
    </li>
    {% endfor %}
</ul>
