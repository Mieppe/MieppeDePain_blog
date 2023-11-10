---
title: Le Blog 1.0
author: MieppeDePain
description : Ceci est un blog. Enfin je crois.
---

---
# Jeux Vidéos
Whaaaaaa ! Alors vous aussi vous aimez les jeux vidéos ? C'est fabuleux ça !

## Liste des posts
<ul>
  {% for post in site.categories.jeux-videos %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

--- 