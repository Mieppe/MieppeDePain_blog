---
title: Le Blog 1.0
author: MieppeDePain
description : Ceci est un blog. Enfin je crois.
---

# Intro
Bien le bonjour voyageur !

<ul>
{% for post in site.posts %}
{% if post.categories contains "jeux-videos" %}
    <li>
        <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
    </li>
{% endif %}
{% endfor %}
</ul>

--- 