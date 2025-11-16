
---
# Playlists Musicales
Vous savez, on a chacun des trucs que l'on aime faire pendant notre temps libre.
Moi par exemple, une choses que j'aime faire, c'est me perdre sur youtube pour découvrir de nouvelles musiques.

A vrai dire j'aime découvrir de nouvelles musiques quels que soient les moyens. Souvent au travers de séries, par des amis, ou même parfois grâce à des bouquins. Mais le plus souvent, j'en découvre en me perdant sur youtube. Bref, je suis toujours à la recherche de nouveautés.

Comme toute personne normalement constituée, je suis absolument fan de mes gouts musicaux. En tout cas maintenant. Quand j'étais au collège, je faisais partie de ces gens insuportables qui répondent "oh heu moi j'écoute de tout" quand on leur demandait ce qu'ils aimaient comme styles. En réalité c'était surtout parce que je n'avais pas vraiment de personnalité musicale à l'époque, et aussi parce que j'étais mal à l'aise à l'idée de partager mes gouts. 

Maintenant... Je fais toujours partie de cette même catégorie de gens insuportables, mais pour des raisons différentes.
Disons que maintenant j'essaie vraiment d'écouter "de tout", ou du moins d'élargir mes horizons. Parfois je dis que j'écoute de tout pour simplifier, ou par flemme, mais souvent je fais l'effort de donner des exemples de ce que j'écoute.

Pour être honnête donc, je devrais plutôt dire que j'essais d'être le plus ouvert possible musicalement, et franchement j'y arrive plutôt bien. Enfin j'espère.

J'adore découvrir de nouvelles choses et de nouveaux genres, et varier les styles. J'aime tellement ça qu'il y a quelques années je me suis dit que je devrai m'amuser à faire des playlists chaque mois pour mettre en avant les musiques que j'ai découvertes ou que j'ai dosées pendant le mois. Et chose extrêmement rare venant de moi, je m'y suis tenu, et ce jusqu'à aujourd'hui.

C'est donc (comme d'habitude lorsque je partage des musiques) avec un mélange de fierté et de gêne que je vous propose de découvrir le fantastique patchwork que j'ai pu construire à mesure des mois et des années. 

(Et btw, comme je suis une personne détestable je ne vais mettre aucun lien dans les pages qui viennent. A vous de chercher, ou pas, parce que soyons honnête personne ne fera cet effort. La vraie raison qui me pousse à rajouter mes playlists ici n'est pas tant l'envie de partager que la peur de les perdre un jour)

Donc heu - En avant la musique ?

## Liste des posts
<ul>
  {% for incredible_post in site.categories.playlists-musicales %}
    {% if incredible_post.url %}
        <li><a href="{{ site.baseurl }}/{{ incredible_post.url }}">{{ incredible_post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
--- 