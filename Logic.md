---
title: Logic
description: The blocks that make it possible to create a mechanic in your world
published: true
date: 2023-05-20T12:55:39.358Z
tags: 
editor: markdown
dateCreated: 2023-05-19T13:12:59.267Z
---

> This page is incomplete and everything in this page is subject to change.
{.is-warning}

> This page explains advanced features, some users may not understand everything in this page.
{.is-warning}

# Logic
These are blocks that allow a player with build permissions to add extra functionality to their world, these examples include:
- [KEY] to sprint
- [KEY] to activate ability

and etc.
> An input is where the gate recieves a signal from a wire connected to it
> An output is where the gate sends a signal to a wire connected from it
{.is-info}

## {.tabset}

### AND Gate
if all inputs are **true**, then it will give an output. But if only ONE of the inputs is false, there will be no output.

Demo:
<div class="input-container">
<label for="AND_input1">Input 1:</label> <input type="checkbox" id="AND_input1" class="input">
  
<label for="AND_input2">Input 2:</label> <input type="checkbox" id="AND_input2" class="input">
<button id="performANDButton" class="button">Perform AND operation</button>
<p id="AND_result">Result:</p>
</div>
 
### OR Gate
only one or more **true** inputs is needed to give an output, if all of the inputs are false there will be no output.

Demo:
<div class="input-container">
<label for="OR_input1">Input 1:</label> <input type="checkbox" id="OR_input1" class="input">
  
<label for="OR_input2">Input 2:</label> <input type="checkbox" id="OR_input2" class="input">
<button id="performORButton" class="button">Perform OR operation</button>
<p id="OR_result">Result:</p>
</div>

### NOT Gate
if NONE of the inputs are **true**, then there will be an output. if ONE or MORE of the inputs are true, then there will be an output.

Demo:
<div class="input-container">
<label for="NOT_input1">Input 1:</label> <input type="checkbox" id="NOT_input1" class="input">
  
<label for="NOT_input2">Input 2:</label> <input type="checkbox" id="NOT_input2" class="input">
<button id="performNOTButton" class="button">Perform NOT operation</button>
<p id="NOT_result">Result:</p>
</div>