
---
# Divers
Ci dessous, une petites listes des posts que j'ai pu faire et pour lesquels j'ai eu la flemme de créer une catégorie. La bise !

## Liste des posts
<ul>
  {% for incredible_post in site.categories.random-shit %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
--- 