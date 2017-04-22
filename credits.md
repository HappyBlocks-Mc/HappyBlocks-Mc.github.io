---
layout: default
title: Crédits
permalink: /Credits/

team:
  - name: StoneSet
    desc: Fondateur du serveur  *Crée les serveurs*
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
    desc: Fondateur du serveur  *Crée les serveurs*
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

  - name: Squizzie
    desc: **Administrateur** du Serveur, travaille sur *Faction* et *Skyblock*
    link: "#!"
    image: img/Credits/squizzie.jpg

  - name: Pizzacus
    desc: Développeur du site
    link: "#!"
    image: img/Credits/pizzacus.jpg
    button:
      - icon: github-circle
        url: "https://github.com/Pizzacus"
        background: "#111"
      - icon: steam
        url: "https://steamcommunity.com/id/Pizzacus/"
        background: "#000"

  - name: TrapTroll
    desc: Administrateur du serveur
    image: img/Credits/Traptroll.jpg
    button:
      - icon: youtube-play
        url:
        "https://www.youtube.com/channel/UCFjJxCxpLaTi_0sn9GQC12w"
        background: "#e52d27"

  - name: AquaKill
    desc: Modérateur du Serveur
    link: "#!"
    image: img/Credits/aquakill.jpg
    button:
      - icon: youtube-play
        url: "https://www.youtube.com/channel/UCGj0dKoh4-PYEFZ92aIqnTw"
        background: "#e52d27"

  - name: Lukax
    desc: Modérateur du Serveur
    link: "#!"
    image: img/Credits/lukax.jpg

  - name: TineTine61
    desc: Builder de HappyBlocks **Merci à lui pour le Fnaf**
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
