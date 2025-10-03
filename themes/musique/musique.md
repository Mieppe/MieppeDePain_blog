
---
# Musique
Bien le bonjour !

C'est parti pour le thème de la musique ! Ici je parle de.... *roulement de tambours*.... Musique !

J'ai plusieurs idées pour aborder ce thème : Partager mes playlists que je fais régulièrement mais aussi parler plus spécifiquement de certains genres, artistes, albums et que sais-je. Je pense aussi en profiter pour faire quelques sauvegardes des sons que j'apprécie.

Bref, voici donc les différentes catégories disponibles dans ce thème, et les différents posts !

## Liste des catégories
- [Playlist musicales](categories/playlists_musicales.md)
- [Musique divers](categories/musique_divers.md)

## Liste des posts
<ul>
  {% for incredible_post in site.categories.musique %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
--- 