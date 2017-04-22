---
layout: default
diapo:
  - image: img/Diapo/01.jpg
    text: Bienvenue sur le prototype de HappyBlocks Web 2.0
    subtext: "Le futur de lendemain du jour suivant... demain !"
    button:
        text: "En savoir plus"
        link: "https://www.youtube.com/watch?v=xG0Ju_pUHAA"
        icon: "arrow-right-bold-hexagon-outline"

  - image: img/Diapo/02.jpg
    text: Il **supporte** le _markdown_ pour mettre en page
    subtext: C'est assez ~~improtant~~ important

  - image: img/Diapo/03.jpg

  - image: img/Diapo/04.jpg
    text: On est pas obligé de mettre de sous-titre ou de titre

  - image: img/Diapo/05.jpg
    text: Ajouter des photos est simple comme bonjour

  - image: img/Diapo/09.jpg

games:
  - image: img/Vignettes/pvpsoup.png
    text: Pvp Soup
    subtext: Le Pvp Soup est un mini-jeu où l'on choisit un kit pour devenir le roi de l'arène !
    badge: Bataille Royale !
    link: "#!"

  - image: img/Vignettes/creatif.png
    text: Créatif
    subtext: Le Créatif est un endroit où vous pouvez laisser libre cour à votre imagination et partager vos créations à vos amis !
    badge: Imaginations !
    link: "#!"

  - image: img/Vignettes/skywars.png
    text: SkyWars
    subtext: Le SkyWars est un mini-jeu où vous devez prendre le contrôle des îles aux alentours et être le survivant de cette bataille !
    badge: Comme Robinson Crusoé mais dans le ciel !
    link: "#!"

  - image: img/Vignettes/withermaze.jpg
    text: WitherMaze
    subtext: Le WitherMaze est un mini-jeu où vous devez trouver le centre du labyrinthe, tuer le Wither et revenir à votre entrée pour déposer l'étoile du Nether !
    badge: Inédit !
    progress: 60%

  - image: img/Vignettes/faction.png
    text: Faction
    subtext: Le Faction est un jeu où vous pouvez créer votre armée de joueurs et conquérir toute la map pour devenir la meilleur Faction !
    badge: À jouer en équipe !
    link: "#!"

  - image: img/Vignettes/fnaf.png
    text: Five Night's At Freddy's In Minecraft
    subtext: Le FNAF est un mini-jeu où vous incarnez un garde de nuit qui doit survivre à des horribles créatures !
    badge: Terrifiant !
    link: jeux/fnaf.md

  - image: img/Vignettes/survie.png
    text: Survival
    subtext: Le Survival est le principe de base de Minecraft , enrichissez-vous en exploitant les richesses de la terre !
    badge: Minecraft Tout Simplement !

features:
  - icon: calendar-today
    text: L'actualité
    subtext: L'avancement des mini-jeux sont décrits sur le site, allez y faire un petit tour !

  - icon: shopping
    text: Une Boutique
    subtext: HappyBlocks dispose d'une boutique pour avoir de nombreux avantages à bas prix mais aussi d'une boutique de goodies. Idéal pour avoir des produits uniques et originaux au couleurs de votre serveur favori !

  - icon: message-text
    text: Une communauté
    subtext: HappyBlocks vous permettra de vous faire de nombreux amis, sur le serveur mais aussi sur le forum où la communauté est très active !

  - icon: music-note
    text: De la Musique
    subtext: HappyBlocks vous permettra de découvrir de nombreux groupes ou compositeurs indépendant grâce à son système In Game !

  - icon: attachment
    text: Open Source
    subtext: Notre Site est open source, c'est à dire que vous pouvez l'utiliser comme bon vous semble par ailleurs, tous nos plugins sont cités dans la section crédits.

  - icon: security
    text: Sûr et Sécurisé
    subtext: Nos serveurs sont régulièrement contrôlés et sont sécurisés, en cas de défaillance faites-le nous savoir sur le forum ou dans le jeu.

  - icon: youtube-play
    text: Une Chaîne YouTube
    subtext: Nous postons régulièrement des vidéos et n'hésitez pas à nous proposer les votre ! Nous les posterons avec plaisir !
    link: "https://www.youtube.com/channel/UCWg0P5_BesetG-ov-H4wcXQ"

  - icon: gamepad-variant
    text: Venez nous rejoindre !
    subtext: HappyBlocks est un serveur ouvert à tous !
---

{% include diapo.html content=page.diapo %}

{% capture scrollContent %}
## AAAAAAAAaaaaaaaaaaAAAAAAAAAAAaaaaaa

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc lobortis est elit, ac finibus augue viverra quis. Nullam lacinia justo at enim venenatis, vitae valentin suscipit arcu porta. Aliquam at aliquam orci. Raviolli raviolli, don't lewd the dragon loli! Proin in ultrices risus, sit amet venenatis orci. Nullam ac faucibus libero. Pellentesque quis molestie velit. Aliquam tincidunt varius.

## A propos de HappyBlocks

*HappyBlocks* est un serveur mini-jeux pour le jeu Minecraft, où vous pouvez vous divertir avec d'autres personnes en jouant à divers Mini-jeux.

Nous avons 2 147 483 647 jeux pour tous les types de joueurs, vous êtes sûrs d'y trouver ce que vous cherchez.
Et comme vous pouvez jouer avec d'autres personnes, ou avec vos amis, vous n'êtes jamais vraiment seul, la convivialité est garentie !

Mais bien sûr, il existe des jeux qui peuvent êtres joués seuls, donc vous avez toujours la possibilité de amuser sur HappyBlocks.

## Mini-jeux disponibles

{% include games.html content=page.games %}

## Pourquoi HappyBlocks ?

{% include features.html content=page.features %}
{% endcapture %}

{% include darkBlock.html content=scrollContent %}
