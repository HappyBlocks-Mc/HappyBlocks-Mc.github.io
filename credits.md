---
layout: default
title: Crédits
permalink: /Credits/

team:
  - name: StoneSet
    desc: Caractère bien trempé, ce chef de groupe n'hésite pas à engueuler le développeur de ce site !
    link: "#!"
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
    desc: Youtubeur sans talent, il s'illustre particulièrement dans le domaine de la malaisance !
    link: "#!"
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

  - name: Pizzacus
    desc: Développeur Web, cette personne n'a jamais été motivé pour faire ce site, c'était du travail forcé ...
    link: "#!"
    image: img/Credits/pizzacus.png
    button:
      - icon: github-circle
        url: "https://github.com/Pizzacus"
        background: "#111"
      - icon: steam
        url: "https://steamcommunity.com/id/Pizzacus/"
        background: "#000"
  
  - name: Squizzie
    desc: Joueur détérminé, il nous boost à avancer et joue parfois sur des serveurs nuls malheureusement ...
    link: "#!"
    image: img/Credits/squizzie.jpg

  - name: AquaKill
    desc: Cette personne a toujours des excuses pour ne pas venir sur le serveur mais on le met quand même car il a fait la map pvpsoupe ...
    link: "#!"
    image: img/Credits/aquakill.jpg
    button:
      - icon: youtube-play
        url: "https://www.youtube.com/channel/UCGj0dKoh4-PYEFZ92aIqnTw"
        background: "#e52d27"
  
  - name: Lukax
    desc: Joueur détérminé, il nous boost à avancer et joue parfois sur PureMerde malheureusement ...
    link: "#!"
    image: img/Credits/lukax.jpg

  - name: TineTine61
    desc: Cette personne ne peut plus utliser son pc de merde déjà qu'il ne pouvais venir deux jours toutes les 2 semaines ...
    link: "#!"
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

Plugin serveur Minecraft:
 * [Plugin](#!)
 * [Plugin](#!)
 * [Plugin](#!)
 * [Plugin](#!)
 * [Plugin](#!)
 * [Plugin](#!)
 * [Plugin](#!)
 * [Plugin](#!)
 * [Plugin](#!)
 * [Plugin](#!)
 * [Plugin](#!)
 * [Plugin](#!)

Technologies utilisées sur le site web:
 * [Jekyll](http://jekyllrb.com)
 * [Meterial Design Icons](http://materialdesignicons.com)
 * [clipboard.js](https://clipboardjs.com/)
{% endcapture %}

{% include darkBlock.html content=scrollContent %}
