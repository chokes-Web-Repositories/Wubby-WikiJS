---
title: Commandes
description: Actions qui peuvent être exécuter sur un joueur
published: true
date: 2023-05-20T18:06:25.690Z
tags: 
editor: markdown
dateCreated: 2023-05-20T18:06:25.690Z
---

# Commandes
> Une partie essentielle de la modération du monde / de la mécanique du monde qui permet aux propriétaires du monde d'exécuter des commandes sur les joueurs.
{.is-info}

```
[] = Option obligatoire
() = Option optionelle
```

## Visitor+
## {.tabset}
### cmds
Ouvre la liste des commandes

### rejoin
Fait rejoindre la personne qui a écrit la commande

### kickabe
Cherche dans les tout les serveurs et expulse [Abe](https://roblox.com/users/663611757) de ce server.
(C'est un blague et cette commande va bientôt être supprimée)

## Builder+
## {.tabset}
### blind [joueur]
Rend [joueur] aveugle

### blur [joueur] (taille)
Floute l'écran du [joueur] par rapport à la (taille)

### bring [joueur]
Teleporte le [joueur] à la personne qui a écrit la commande

### damage/dmg [joueur] (nombre)
Baisse la vie du [joueur] par rapport au (nombre)

### explode/exp [joueur]
Explose le [joueur], l'explosion peut peut-être bouger les objets proches

### fix/removeeffects [joueur]
Enlève chaque effet appliqué sur le [joueur] (flou, champ de vision, aveuglement, etc.)

### fling [joueur] (nombre)
Pousse le [joueur] TRES LOIN :] à une vitesse de (nombre)

### fly [joueur]
Fait voler le [joueur]

### flyspeed [joueur] (nombre)
Met une vitesse de vol sur le [joueur] à (nombre)

### fov/fieldofview [joueur] (champ de vision)
Met le champ de vision du [joueur] à (champ de vision)

### freeze/anchor [joueur]
Bloque le [joueur], le [joueur] ne pourra plus bouger

### ghost/gh [joueur]
Transforme le [joueur] en un phantome, oulala j'ai peur!!

### god [joueur]
Rend le [joueur] invincible de tout les dégats (sauf tué par une commande)

### gyro [joueur]
Empèche le [joueur] de changer d'orientation

### heal [joueur] (nombre)
Augmente la vie du [joueur] by par le (nombre) OU met la vie maximale du [joueur] si le (nombre) n'est pas spécifié

### highlight [joueur] (brickcolor)
Rend le [joueur] visible à travers les murs avec la couleur (brickcolor)

### invisible/inv/invis/hide [joueur] (isVisible)
Rend le [joueur] invisible, si (isVisible) est "false", le joueur ne pourra pas se voir lui même

### jump [joueur]
Force le [joueur] à sauter

### jumppower [joueur] (nombre)
Change la puissance de saut du [joueur] à (nombre)

### kill/die [joueur]
Tue le [joueur]

### lightning/smite/thunder [joueur]
Fait apparaitre Zeus et lançe un éclair sur le [joueur]

### magnet [joueur] (nombre)
Attire tout les joueurs au [joueurs] avec une force de (nombre)

### maxhealth [joueur] (nombre)
Met la vie maximale du [joueur] à (nombre)

### message/m/msg/shout/announce [joueur] (message)
Montre le (message) à l'écran du [joueur]

### nuke [joueur]/[coordonnées]
Place une bombe atomoque sur le [joueur] ou aux [coordonnées]

### removelimbs [joueur]
Enlève les membres du [joueur]

### respawn [joueur]
Réapparait le [joueur] en le laissant à sa position d'avant

### sit/trip [joueur]
Force le [joueur] à s'asseoir

### sparkles/sparkle [joueur] (couleur)
Donne au [joueur] des particules avec les (couleurs)

### team name/teams name [Nom de l'équipe]  [Nouveau nom]
Change le [Nom de l'équipe] au [nouveau nom]

### team set/teams set [joueur] [Nom de l'équipe]
Assigne l'équipe du [joueur] à [Nom de l'équipe]

### to/tp/teleport (joueur) (joueur 2)/(coordonnées)
Si aucune option n'a été écrite, la commande va téléporter le joueur qui l'a écrite au pointeur de sa sourie
Si (joueur) est écrit, cette commande va téléporter la personne qui a écrite cette commande au (joueur)
Si le (joueur) et le (joueur2) sont écrits, cette commande va téléporter le joueur) au (joueur2)
Si les (coordonnées) sont écrits, cette commande va téléporter la personne qui l'a écrite vers les (coordonnées)

### trail [joueur] (couleur)
Met une trainée sur le [joueur], sa couleur va être (couleur)

### unblind [joueur]
Rend la vision au [joueur]

### unblur [joueur]
Enlève le flou sur l'écran du [joueur]

### unfly [joueur]
Enlève la capacité du [joueur] à voler

### unfreeze/thaw/unanchor [joueur]
Rend le [joueur] capable de bouger

### ungod [joueur]
Rend le [joueur] vulnérable aux dégats

### ungyro [joueur]
Autorise le [joueur] à changer d'orientation

### unhighlight [joueur]
Enlève le fluo du [joueur]

### unmagnet [joueur]
Enlève l'aimant du [joueur]

### visible/vis [joueur]
Rend le [joueur] visible

### walkspeed [joueur] (nombre)
Change la vitesse de marche du [joueur] au (nombre)

## Admin+
## {.tabset}
### ban [joueur]
Empèche le [joueur] de rejoindre le monde

### kick [joueur] (raison)
Expulse le [joueur] avec la (raison)

### stat/stats add [Nom du tableau des scores]
Créé un tableau des scores avec le [Nom du tableau des scores]

### stat/stats name [Nom du tableau des scores] [Nouveau nom]
Change le [Nom du tableau des scores] au [Nouveau nom]

### stat/stats remove [Nom du tableau des scores]
Enlève le tableau des scores sous le [Nom du tableau des scores]

### stat/stats set [Nom du tableau des scores] [joueur] (valeur)
Met la valeur du [joueur] du [Nom du tableau des scores] à la (valeur)

### stat/stats visible [Nom du tableau des scores] (Isvisible)
Change la visibilité du [Nom du tableau des scores], si (isVisible) est en "false", [Nom du tableau des scores] ne va pas être montré sur la liste des joueurs.

### team/teams add [Nom de l'équipe] (Couleur de l'équipe)
Créé une nouvelle équipe avec le nom [Nom de l'équipe] et la couleur (Couleur de l'équipe). Si (Couleur de l'équipe) n'est pas specifié, l'équipe va avoir une couleur aléatoire.

### team/teams autoassign [Nom de l'équipe] (isEnabled)
Fait en sorte que le joueur devrait être automatiquement assigné à l'équipe [Nom de l'équipe] ou non. Si il y a plusieurs équipes avec cette option activée, le joueur va être mit dans l'équipe avec le moins de joueurs

### team/teams color [Nom de l'équipe] [Couleur de l'équipe]
Change la couleur du [Nom de l'équipe] à [Couleur de l'équipe]

### team/teams remove [Nom de l'équipe]
Enlève l'équipe sous le nom de [Nom de l'équipe]
### unban [joueur]
Autorise le [joueur] à rejoindre le monde.