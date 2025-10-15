
---
# Liste de Jeux de Société
Hello la teaaaaaaam !
Bon je ne promets pas de découvrir de nouveaux jeux tous les ans. Enfin si ? j'espère ?
Bref, on verra :

## Liste des posts
<ul>
  {% for incredible_post in site.categories.liste-jeux-societe %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
--- 