---
layout: default
---

# Samenwerkingen

<ul id="samenwerkingen-container">
{% for samenwerking in site.samenwerkingen %}
    <li>
        {{ samenwerking.title }}
        {{ samenwerking.content }}
   </li>
{% endfor %}
</ul>