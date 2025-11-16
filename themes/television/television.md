
---
# Télévision
Bon, comme créer des catégories c'est relou, en voilà une qui regroupe tout ce qui touche de près ou de loin à la TV : j'ai nommé :
- les films
- les séries
- les animes
- et que sais-je

Ouais j'aurai pu appelé cette catégorie "cinéma" en fait. IDK.

## Liste des catégories
- [Listes télévision](categories/liste-tv.md)
- [Télévision divers](categories/tv-divers.md)

## Liste des posts
<ul>
  {% for incredible_post in site.categories.television %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
--- 