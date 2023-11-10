---
title: Le Blog 1.0
author: MieppeDePain
description : Ceci est un blog. Enfin je crois.
---

---
# Divers
Ci dessous, une petites listes des postes que j'ai pu faire et pour lesquels j'ai eu la flemme de créer une catégorie. La bise !

## Liste des postes
<ul>
{% for post in site.posts %}
{% if post.categories contains "random-shit" %}
    <li>
        <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
    </li>
{% endif %}
{% endfor %}
</ul>

--- 