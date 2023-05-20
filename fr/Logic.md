---
title: Logique
description: Les blocs qui permettent de créer une mécanique dans votre monde
published: true
date: 2023-05-20T17:13:57.727Z
tags: 
editor: markdown
dateCreated: 2023-05-20T16:52:51.109Z
---

> Cette page est incomplète et tout ce qu'elle contient est susceptible d'être modifié.
{.is-warning}

> Cette page explique les fonctionnalités avancées, certains joueurs peuvent ne pas comprendre tout ce qu'elle contient.
{.is-warning}

# Logique

Il s'agit de blocs qui permettent à un joueur disposant de droits de construction d'ajouter des fonctionnalités supplémentaires à son monde :

- [TOUCHE CLAVIER] pour sprinter

- [TOUCHE CLAVIER] pour activer quelque chose

et etc.

> Un signal d'entrée est l'endroit où le bloc de logique reçoit un signal d'un cable qui lui est connecté.
> Un signal de sortie est l'endroit où le bloc de logique envoie un signal à un fil qui lui est connecté.
>
> "true" = signal actif
> "false" = signal inactif
{.is-info}

## {.tabset}

### Gate ET

> La Gate ET prend un ou plusieurs signaux d'entrée et produit un signal de sortie si toutes les entrées sont **true**.
{.is-info}

Démonstration

<div class="input-container">
<label for="AND_input1">Entrée 1:</label> <input type="checkbox" id="AND_input1" class="input">
  
<label for="AND_input2">Entrée 2:</label> <input type="checkbox" id="AND_input2" class="input">
  
<button id="performANDButton" class="button">Effectuer l'opération ET</button>
<p id="AND_result">Résultat:</p>
</div>

 

### Gate OU

> La gate OU prend un ou plusieurs signaux d'entrée et produit un signal de sortie si une seule entrée est **true**.
{.is-info}

Démonstration:

<div class="input-container">

<label for="OR_input1">Entrée 1:</label> <input type="checkbox" id="OR_input1" class="input">

  

<label for="OR_input2">Entrée 2:</label> <input type="checkbox" id="OR_input2" class="input">

<button id="performORButton" class="button">Effectuer l'opération OU</button>

<p id="OR_result">Résultat:</p>

</div>

### Gate NOT

> La Gate NOT, également appelée inverseur, prend un seul signal d'entrée et produit le signal de sortie opposée. 
{.is-info}

Démonstration:

<div class="input-container">

<label for="NOT_input1">Entrée:</label> <input type="checkbox" id="NOT_input1" class="input">

  

<button id="performNOTButton" class="button">Effectuer l'opération NOT</button>

<p id="NOT_result">Résultat:</p>

</div>