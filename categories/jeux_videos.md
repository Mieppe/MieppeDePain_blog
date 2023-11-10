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
{% for post in site.posts %}
{% if post.categories contains "jeux-videos" %}
    <li>
        <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
    </li>
{% endif %}
{% endfor %}
</ul>

--- 