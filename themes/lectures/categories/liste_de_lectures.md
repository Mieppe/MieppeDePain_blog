
---
# Liste de lectures
Hop là salut ! Bon vous voyez, j'ai beaucoup lu dans ma vie, et j'espère que je continuerai encore et encore, même si mon temps de lecture s'est pas mal réduit au cours des dernières années.
Bref, l'idée de cette catégorie est de faire la liste des bouquins que je lis. Peut être par année ? En faisant une première liste préliminaire qui tente de regrouper les trucs que j'ai lu toutes les années précédentes (mdr ça va être du boulot ça).
Mais oui, l'esprit est le même que pour la musique : garder en tête tout ce que j'ai lu.

## Liste des posts
<ul>
  {% for incredible_post in site.categories.liste-de-lectures %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
--- 