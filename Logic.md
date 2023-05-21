---
title: Logic
description: The blocks that make it possible to create a mechanic in your world
published: true
date: 2023-05-21T04:24:37.496Z
tags: 
editor: markdown
dateCreated: 2023-05-19T13:12:59.267Z
---

> This page is incomplete and everything in this page is subject to change.
{.is-warning}

> This page explains advanced features, some players may not understand everything in this page.
{.is-warning}

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
<p id="NOT_result">Result:</p>
</div>