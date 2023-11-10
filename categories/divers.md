---
title: Le Blog 1.0
author: MieppeDePain
description : Ceci est un blog. Enfin je crois.
---

---
# Divers
Ci dessous, une petites listes des posts que j'ai pu faire et pour lesquels j'ai eu la flemme de créer une catégorie. La bise !

## Liste des posts
<ul>
  {% for post in site.categories.divers %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
--- 