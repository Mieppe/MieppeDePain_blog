
---
# Jeux de Société
Ok, j'aime les jeux de société, mais j'avoue que je n'y joue pas assez.
On verra si cette catégorie sera très remplie ou non.

## Liste des catégories
- [Liste de jeux de société](categories/liste_jeux_societe.md)
- [Jeux de société divers](categories/jeux_societe_divers.md)

## Liste des posts
<ul>
  {% for incredible_post in site.categories.jeux-de-societe %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

--- 