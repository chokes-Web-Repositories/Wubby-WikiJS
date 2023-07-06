---
title: Logic
description: The blocks that make it possible to create a mechanic in your world
published: true
date: 2023-07-06T12:37:46.354Z
tags: 
editor: markdown
dateCreated: 2023-05-19T13:12:59.267Z
---

> This page is incomplete and everything in this page is subject to change.
{.is-warning}

> This page explains advanced features, some players may not understand everything in this page.
{.is-warning}

# Input
## {.tabset}
### Block Touch Detector
Emits a signal when touched by a player or an unachored block.
Configurations:
- Activation Time: Amount of time to delay output. Default is 1
- Color To Filter: When filter color is true, only blocks with this color will trigger it. Default is pearl.
- Filter Color: Whether if this block will only trigger when a block with the specified color touches it. Default is false.

### Click Block
Emits a signal when clicked on. 
Configurations: 
- Activation Time: How long it activates for. Default is 1. 
- Max Distance: How far you can click this block. Default is 32.
- Toggleable: Whether if this block acts like a switch. Default is true.

### Humanoid State Block
PLACEHOLDER, PLEASE EDIT ME!

### Key Input Block
PLACEHOLDER, PLEASE EDIT ME!

### Player Chatted Block
PLACEHOLDER, PLEASE EDIT ME!

### Player Touch Detector
PLACEHOLDER, PLEASE EDIT ME!

### Prompt Block
Emits a signal when it's Proximity Prompt has been triggered.
Configurations:
- Activation Time: How long it activates for. Default is 1.
- Hold Duration: Amount of time to trigger the prompt. Default is 0.5
- Key: Key to hold when triggering the prompt. Default is E.
- Toggleable: Whether if this block acts like a switch. Default is true.

### REPEATER Gate
PLACEHOLDER, PLEASE EDIT ME!

### Tap Input Block
PLACEHOLDER, PLEASE EDIT ME!

# Logic
These are blocks that allow a player with build permissions to add extra functionality to their world, these examples include:
- [KEY] to sprint
- [KEY] to activate ability

and etc.
> An input is where the gate recieves a signal from a wire connected to it
> An output is where the gate sends a signal to a wire connected from it
>
> "true" = active signal
> "false" = inactive signal
{.is-info}

## {.tabset}

### AND Gate
> The AND gate takes a single or multiple input signal(s) and produces an output if all inputs are **true**.
{.is-info}

Demo:
<div class="input-container">
<label for="AND_input1">Input 1:</label> <input type="checkbox" id="AND_input1" class="input">
  
<label for="AND_input2">Input 2:</label> <input type="checkbox" id="AND_input2" class="input">
<button id="performANDButton" class="button">Perform AND operation</button>
<p id="AND_result">Result:</p>
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

### XOR Gate
> The XOR gate takes multiple input signals and produces an output if the number of true inputs are odd.
{.is-info}

Demo:
<div class="input-container">
<label for="XOR_input1">Input 1:</label> <input type="checkbox" id="XOR_input1" class="input">
  
<label for="XOR_input2">Input 2:</label> <input type="checkbox" id="XOR_input2" class="input">

<label for="XOR_input3">Input 3:</label> <input type="checkbox" id="XOR_input3" class="input">

<label for="XOR_input4">Input 4:</label> <input type="checkbox" id="XOR_input4" class="input">
  
<button id="performXORButton" class="button">Perform XOR operation</button>
<p id="XOR_result">Result:</p>
</div>