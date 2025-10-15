
---
# Liste de Jeux Vidéos
Salutations ! 
Bon, voilà, j'aime les listes.
Voici une nouvelle catégorie pour regrouper la liste des jeux vidéos que j'ai découvert au cours du temps. Parce que bon, je fais ça avec les livres, je pense faire ça avec les films, les séries, les animes... Pourquoi ne pas faire ça avec les jeux vidéos ?

## Liste des posts
<ul>
  {% for incredible_post in site.categories.liste-de-jv %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
--- 