
---
# Le Fond
Tiens, on dirait que vous avez touché le fond.
Bienvenue dans la twittosphère. Ou plutôt un erzatz de cette dernière, qui en copie l'escence tout en en modifiant la forme.
Ici rien n'est vrai, rien n'est nuancé, rien n'est réfléchi. Communiquer cesse d'être un outil et devient une fin en soi. Parler pour parler, écrire pour écrire.
Personne ne sait ce qui se trouve et se trouvera ici, pas même moi. Courage aux explorateurs qui prendront leur pelle pour tenter de trouver la pépite d'or parmi les déchets. Pour peu qu'il y en ait.

BTW on va mettre quelque chose en place ici : J'écris toujours sur la même page que je repost entièrement à chaque nouveauté.
Comme ça je multiplie pas les pages pour quasi rien.
Bon ok on va dire une page par année, et on verra ce que ça donne

Pour encore plus de quantité, et toujours moins de qualité, [c'est ici](https://twitter.com/Mieppe_De_Pain). Ou pas, qui sait.

## Liste des posts
<ul>
  {% for incredible_post in site.categories.le-fond %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
--- 