
---
# Jeux Vidéos
Whaaaaaa ! Alors vous aussi vous aimez les jeux vidéos ? C'est fabuleux ça !

## Liste des posts
<ul>
  {% for incredible_post in site.categories.jeux-videos %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

--- 