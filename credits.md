---
layout: default
title: Crédits
permalink: /Credits/

team:
  - name: StoneSet
    desc: "**Fondateur du serveur**, *Maintenance serveurs, plugins, sql*"
    image: img/Credits/stoneset.png
    button:
      - icon: twitter
        url: "https://twitter.com/StoneSetYT"
        background: "#00aced"
      - icon: youtube-play
        url: "https://www.youtube.com/channel/UC5pxpLJSVNgo7z7dn6YeT7w"
        background: "#e52d27"
      - icon: github-circle
        url: "http://stoneset.github.io/"
        background: "#111"

  - name: Wabfall
    desc: "**Fondateur du serveur**, *Builder WitherMaze*"
    image: img/Credits/wabfall.jpg
    button:
      - icon: twitter
        url: "https://twitter.com/FunnyGamers72"
        background: "#00aced"
      - icon: youtube-play
        url: "https://www.youtube.com/channel/UCjJZGHeHBy9pWjcEeQejkCQ"
        background: "#e52d27"
      - icon: facebook
        url: "https://www.facebook.com/profile.php?id=100010175804819"
        background: "#3b5998"

  - name: Squizzie
    desc: "**En attente d'approbation**,
    image: img/Credits/squizzie.jpg

  - name: Pizzacus
    desc: Graphiste, développeur du site
    image: img/Credits/pizzacus.png
    button:
      - icon: github-circle
        url: "https://github.com/Pizzacus"
        background: "#111"
      - icon: steam
        url: "https://steamcommunity.com/id/Pizzacus/"
        background: "#000"

  - name: Lukax
    desc: Modérateur du Serveur
    image: img/Credits/lukax.jpg

  - name: TineTine61
    desc: Builder FNAF
    image: img/Credits/tinetine.png
    button:
      - icon: facebook
        url: "https://www.facebook.com/profile.php?id=100011582926276"
        background: "#3b5998"
      - icon: youtube-play
        url: "https://www.youtube.com/channel/UCLwYea7Yv4ibY-TIhx2NSVw"
        background: "#e52d27"
---

# Team HappyBlocks

{% include team.html content=page.team %}

{% capture scrollContent %}
HappyBlocks utilise les technologies suivantes:

Police: [Ubuntu](http://font.ubuntu.com/) (Utilisée un peu partout et sur les versiones récentes du logo)


Technologies utilisées sur le site web:
 * [Jekyll](http://jekyllrb.com)
 * [Meterial Design Icons](http://materialdesignicons.com)
 * [clipboard.js](https://clipboardjs.com/)
{% endcapture %}

{% include darkBlock.html content=scrollContent %}
