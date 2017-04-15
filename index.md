---
layout: default
diapo:
  - image: img/Diapo/01.jpg
    text: Bienvenue sur le prototype de HappyBlocks Web 2.0
    subtext: "Le futur de lendemain du jour suivant... demain !"
    button:
        text: "非常に癌性の"
        link: "https://www.youtube.com/watch?v=7q50z0s7MOs"
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
  - image: img/Gay/gay01.png
    text: "Lesbian Simulator: サンプルテキスト"
    subtext: Yuri, yaoi et des raviolli ! ( ͡° ͜ʖ ͡°)
    badge: Nouveau !
    link: "#!"

  - image: img/Gay/gay02.png
    text: Au tour de Pokémon
    subtext: Okay, je devrais arréter
    link: "#!"

  - image: img/Gay/gay03.png
    text: C'est Chara x Frisk
    subtext: (oui, c'est pas hyper évident). Fun fact, j'ai littérallement rencontré quelqu'un avec cette photo en fond d'écran sur son portable.
    link: "#!"

  - image: img/Gay/gay04.jpg
    text: Dragon Yuri
    subtext: C'est surprenant, mais il y a pas beaucoups de fanarts de Kobayashi x Tohru, mais j'ai peut-être pas assez cherché
    badge: Bientôt disponible
    url: https://www.youtube.com/watch?v=ZMeg69665yU
    progress: 21%

  - image: img/Gay/gay05.jpg
    text: 20%
    subtext: "Fun fact: On peut shipper n'importe quel mane 6 ensemble et sa marche"
    link: "#!"

  - image: img/Gay/etienne.png
    text: Etienne
    subtext: Des recherches approfondies ont prouvées que ceci est la dernière image que le cerveau reçoit avant la mort, cerais-ce dieu ?
    link: "#!"

features:
  - icon: bell
    text: Des cloches
    subtext: Beaucoup de cloches

  - icon: cake
    text: piece of kek
    subtext: kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek kek

  - icon: cat
    text: Question existenciel
    subtext: Si on encule une loli neko, c'est de la pédophilie ? ou de la zoophilie ?

  - icon: gender-transgender
    text: Plus De Question
    subtext: Les hentai futanari sont-t-ils gays ? Ou ethero ?

  - icon: car
    text: Attend, Pourquoi le FBI sont-ils devant ma porte ?
    subtext: Ils viennent d'arriver, j'ai dit quelque chose qu'il fallais pas ?

  - icon: emoticon-poop
    text: Vous saviez qu'ils vont faire un film sur les emoticons ?
    subtext: Genre, ça vas devenir le nouveau bee movie ou quoi

  - icon: voice
    text: Les aliens ont implantés une antenne dans ma tête
    subtext: En tout cas c'est comme ça que j'interprète cette icone
---

{% include diapo.html content=page.diapo %}

{% capture scrollContent %}
## Disclaimer

**Depuis que j'ai commencé a dev cette version d'HappyBlocks, j'ai un running gag où je met que des trucs pervers ou attardé comme faux contenue (images, textes, ect...). Donc s'il vous plait, prenez tout au serieux, c'est pas une phase, Maman.**

Et oui, la plupart de ces trucs sont même pas marrants.

## A propos de HappyBlocks

*HappyBlocks* est un serveur mini-jeux pour le jeu Minecraft, où vous pouvez vous divertir avec d'autres personnes en jouant à divers Mini-jeux.

Nous avons 2 147 483 647 jeux pour tous les types de joueurs, vous êtes sûrs d'y trouver ce que vous cherchez.
Et comme vous pouvez jouer avec d'autres personnes, ou avec vos amis, vous n'êtes jamais vraiment seul, la convivialité est garentie !

Mais bien sûr, il existe des jeux qui peuvent êtres joués seuls, donc vous avez toujours la possibilité de amuser sur HappyBlocks.

## ~~Mini-jeux~~ Ships disponibles

{% include games.html content=page.games %}

## Pourquoi HappyBlocks ?

{% include features.html content=page.features %}
{% endcapture %}

{% include darkBlock.html content=scrollContent %}
