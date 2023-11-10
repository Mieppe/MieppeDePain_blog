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
  {% for incredible_post in site.categories.jeux-videos %}
    {% if incredible_post.url %}
        <li><a href="{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

--- 