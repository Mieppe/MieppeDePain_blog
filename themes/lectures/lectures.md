
---
# Lectures
Vous savez,
Lire c'est bien.

C'est même très bien.
Si on me demandait je dirai que c'est l'une des activités les plus saines qui soit.
Surtout quand on est jeune. Et d'autant plus de nos jours #vieucon

Bref. Lisez.

Quoi vous ne savez pas quoi lire ? Rholala je n'osais pas, mais si vous insistez... :

## Liste des catégories
- [Liste de lectures](categories/liste_de_lectures.md)
- [Lectures divers](categories/lectures_divers.md)

## Liste des posts
<ul>
  {% for incredible_post in site.categories.lectures %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
--- 