
---
# Jeux Vidéos : Divers
Et voilà une super page pour répertorier tous les articles random concernant les jeux vidéos.
Je dis "tous" comme si j'allais en faire 100, mais on sait très bien que j'aurai la flemme au bout de 2 ou 3.
Bref, continuons à nous mentir dans la bonne humeur :

## Liste des posts
<ul>
  {% for incredible_post in site.categories.jv-divers %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
--- 