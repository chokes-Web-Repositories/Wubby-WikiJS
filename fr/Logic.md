---
title: Logique
description: Les blocs qui permettent de créer une mécanique dans votre monde
published: true
date: 2023-05-20T16:52:51.109Z
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

- [KEY] to sprint

- [KEY] to activate ability

and etc.

> Une entrée est l'endroit où la porte reçoit un signal d'un fil qui lui est connecté.
> Une sortie est l'endroit où la porte envoie un signal à un fil qui lui est relié.
>
> "true" = signal actif
> "false" = signal inactif
{.is-info}

## {.tabset}

### Porte ET

> La porte ET prend un ou plusieurs signaux d'entrée et produit une sortie si toutes les entrées sont **vraies**.
{.is-info}

Démonstration

<div class="input-container">
<label for="AND_input1">Input 1:</label> <input type="checkbox" id="AND_input1" class="input">
  
<label for="AND_input2">Input 2:</label> <input type="checkbox" id="AND_input2" class="input">
  
<button id="performANDButton" class="button">Perform AND operation</button>
<p id="AND_result">Result:</p>
</div>

 

### OR Gate

> The OR gate takes a single or multiple input signal(s) and produces an output if a single input is **true**

{.is-info}

Demo:

<div class="input-container">

<label for="OR_input1">Input 1:</label> <input type="checkbox" id="OR_input1" class="input">

  

<label for="OR_input2">Input 2:</label> <input type="checkbox" id="OR_input2" class="input">

<button id="performORButton" class="button">Perform OR operation</button>

<p id="OR_result">Result:</p>

</div>

### NOT Gate

> The NOT gate, also called an inverter, takes a single input signal and produces the opposite output. 

{.is-info}

Demo:

<div class="input-container">

<label for="NOT_input1">Input:</label> <input type="checkbox" id="NOT_input1" class="input">

  

<button id="performNOTButton" class="button">Perform NOT operation</button>

<p id="NOT_result">Result:</p>

</div>