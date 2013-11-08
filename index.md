---
layout: default
title: Penser le numérique
---

Identification du corpus (200 livres) / Classification rapide 4e de couverture + sommaire / 10 ouvrages clés / Problématique (Quel est le problème? Pourquoi est-ce mal compris?) / 20 mots-clés / 5 mots-clés / Hypothèse / Direction / Citations livres + commentaires / Classification 5 boîtes (chapitres de l’ouvrage) - Ecrire pour chacune une introduction et une conclusion (Les 5 conclusions sont classées dans 1 boîte Conclusion / Conclusion / Finir par l’introduction</p>

-------

### actualité
  
<ul class="posts">
{% for post in site.posts %}
<li><span>{{ post.date | date: "%d/%m/%Y" }}</span> &rarr; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

-------

* [Corpus](/corpus/)
