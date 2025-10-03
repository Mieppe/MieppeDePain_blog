
---
# Lectures : Divers
Bienvenue dans la catégorie ou je parle de lectures en terme général. Parce que lire c'est bien.
Ecrire aussi d'ailleurs. Et c'est là qu'on va remarquer que faire honneur à des bouquins qu'on a aimé quand on est pas bon écrivain c'est dur.
Bref je vais faire de mon mieux.

## Liste des posts
<ul>
  {% for incredible_post in site.categories.lectures-divers %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
--- 