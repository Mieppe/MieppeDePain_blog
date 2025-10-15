
---
# Liste Télévision
Bam, vous aimez les listes ? J'aime les listes, nous aimons les listes.
Miam miam ! Des listes de ce que j'ai découvert côté cinéma, par année (surement).

## Liste des posts
<ul>
  {% for incredible_post in site.categories.liste-television %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
--- 