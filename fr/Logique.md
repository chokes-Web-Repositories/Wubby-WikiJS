---
title: Logique
description: Les blocs qui rendent possible la création d'une mécanique dans votre monde
published: true
date: 2023-05-20T17:06:23.575Z
tags: 
editor: markdown
dateCreated: 2023-05-20T17:06:23.575Z
---

> Cette page est incomplète et tout peut changer.
{.is-warning}

> Cette page explique des fonctionalités avancées, certains joueurs ne pourront peut-être pas tout comprendre dans cette page.
{.is-warning}

# La logique
Se sont des blocs qui autorisent les joueurs avec les permissions de construction d'ajouter des fonctionnalités supplémentaires à leurs mondes comme par exemple:
- [Touche clavier] pour courir
- [Touche clavier] pour avoir l'abilité d'activer

et etc.
> Un signal d'entrée est où le bloc de logique reçoit un signal depuis un cable connecté à lui
> Un signal de sortie est où le bloc de logique envoit à un cable connecté à lui
>
> "true" = signal actif
> "false" = signal inactif
{.is-info}

## {.tabset}

### AND Gate
> La AND gate prend un seul ou plusieurs signaux d'entrée et produit un signal de sortie si tout les signaux d'entrée sont en **true**.
{.is-info}

Exemple:
<div class="input-container">
<label for="AND_input1">Signal d'entrée 1:</label> <input type="checkbox" id="AND_input1" class="input">
  
<label for="AND_input2">Signal d'entrée 2:</label> <input type="checkbox" id="AND_input2" class="input">
<button id="performANDButton" class="button">Performe l'opération AND</button>
<p id="AND_result">Résultat:</p>
</div>
 
### OR Gate
> La OR gate prend un seul ou plusieurs signaux d'entrée et produit un signal de sortie si un seul signal d'entrée est en **true**
{.is-info}

Exemple:
<div class="input-container">
<label for="OR_input1">Signal d'entrée 1:</label> <input type="checkbox" id="OR_input1" class="input">
  
<label for="OR_input2">Signal d'entrée 2 2:</label> <input type="checkbox" id="OR_input2" class="input">
<button id="performORButton" class="button">Perform l'opération OR</button>
<p id="OR_result">Résultat:</p>
</div>

### NOT Gate
> La NOT gate, aussi nommé inverseur, prend un seul signal d'entrée et produit le signal de sortie opposé 
{.is-info}

Exemple:
<div class="input-container">
<label for="NOT_input1">Signal d'entrée:</label> <input type="checkbox" id="NOT_input1" class="input">
  
<button id="performNOTButton" class="button">Performe l'opération NOT</button>
<p id="NOT_result">Résultat:</p>
</div>
