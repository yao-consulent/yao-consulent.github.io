---
layout: default
---

# Samenwerkingen

<ul>
{% for samenwerking in site.samenwerkingen %}
    <li>
        {{ samenwerking.title }}
        {{ samenwerking.content }}
   </li>
{% endfor %}
</ul>