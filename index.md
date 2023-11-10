---
title: Le Blog 1.0
author: MieppeDePain
description : Ceci est un blog. Enfin je crois.
---

# Intro
Bien le bonjour voyageur !

Ci dessous les articles "jeux vidéos" :
<ul>
{% for post in site.posts %}
{% if post.catefories contains "jeux-videos" %}
    <li>{{post.title}}</li>
{% endif %}
{% endfor %}
