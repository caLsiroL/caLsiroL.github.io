---
title: "Jeu sérieux réalité augmenté sur le casque Microsoft Hololens 2"
description: "Projet universitaire "
dateString: Janvier - Mai 2021
draft: false
tags: ["Godot", "Multiplayer", "Networking", "University Project"]
weight: 203
cover:
    image: "/projects/dixit/cover.png"
---

## 🔗 [Github de Geololens](https://github.com/LuxemTheFez/Geololens)
## 🔗 [Github de Electrololens](https://github.com/LuxemTheFez/Electrololens)

## Introduction
Dans le cadre de ma licence 3 nous avions un projet de 4-5 mois à réaliser. Avec 4 autre camarades nous eu la possibilité de produire une preuve de concept de numérisation en 3D du jeu de société Dixit. L'objectif derrière ce projet était tester la création d'application exploitant les capacitées de la salle Ark-Inseec, une salle de classe du futur équipée de 5 murs tactiles géants

{{< video src="electrololens" >}}

## Résultats
Nous avons donc produit un jeu multijoueurs en P2P avec le moteur de jeu open source Godot avec des cartes etxtraites du jeu officiel (un grand merci à Dixit de nous avoir laissé utiliser leurs illustrations pour ce jeu)

Le jeu reprend l'intégralité des règles du Dixit sans compromis. Nous nous sommes même permis d'ajouter quelques fonctionnalitées complémentaires comme des effets sur les cartes lorsque les cartes sont dévoillées

![Carte avec effet spéciaux](/projects/dixit/img2.png)

Notre jeu est multi-plateforme, pouvant se jouer sur téléphone, PC et web avaec même un mode "plateau" ayant pour objectif d'afficher le plateau sur un écran externe, ici l'un des murs de la salle Ark-Inseec par exemple.

Je me suis personnellement occupé de :
- La partie réseau du jeu & multijoueur du jeu
- Du chat rapide
- De la création du mode plateau 
- De la sélection des personnages et du choix de leur couleur
- De la distribution "aléatoire" des cartes
- Du positionnement des pions lors des votes

Voici une vidéo récapitulative du projet monté et réalisé par mes soins, dont je suis la voix off, dans le cadre de notre rendu

{{< video src="geololens" >}}


## Conclusion

Le projet Ark'Dixit m'a permis de mettre un premier pied dans le developpement de jeu multijoueur, ce qui était quelque chose qui m'interressait beaucoup et sur lequel j'ai pris beaucoup de plaisir. Ce fut aussi une première expérience de développement de jeu en groupe.
Pour un projet d'étudiant le projet a abouti là ou nous le voulions et j'ai pu apprendre énormement de chose à refaire ou non. Ce qui, pour moi, est une réussite.
