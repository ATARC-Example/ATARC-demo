---
layout: page
title: Completed Products
---

Include list of completed products taken from <a href="http://www.atarc.org/documents/#white-papers">here</a>

## Mobile Efforts

<ul>
{% for file in site.static_files %}
  {% if file.extname == '.pdf' %}
  <li>
    <a href="http://github.com/ATARC-Example/ATARC-demo/blob/master{{file.path}}">
      {{file.name}}
    </a>
  </li>
  {% endif %}
{% endfor %}
</ul>
