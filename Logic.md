---
title: Logic
description: The blocks that make it possible to create a mechanic in your world
published: true
date: 2023-05-20T12:43:24.624Z
tags: 
editor: markdown
dateCreated: 2023-05-19T13:12:59.267Z
---

> This page is incomplete and everything in this page is subject to change.
{.is-warning}

> true = wire is on
> false = wire is off
> 
> An input is where the wire goes into the gate, and output is where it goes out. If an output is "given," then that means the output wire has been turned on.
{.is-info}

## {.tabset}

### AND Gate
if all inputs are **true**, then it will give an output. But if only ONE of the inputs is false, there will be no output.

Demo:
<div class="AND-input-container">
<label for="AND_input1">Input 1:</label> <input type="checkbox" id="AND_input1" class="input">
  
<label for="AND_input2">Input 2:</label> <input type="checkbox" id="AND_input2" class="input">
<button id="performANDButton" class="button">Perform AND operation</button>
<p id="AND_result">Result:</p>
</div>
 
### OR Gate
only one or more **true** inputs is needed to give an output, if all of the inputs are false there will be no output.
<div class="OR-input-container">
<label for="OR_input1">Input 1:</label> <input type="checkbox" id="OR_input1" class="input">
  
<label for="OR_input2">Input 2:</label> <input type="checkbox" id="OR_input2" class="input">
<button id="performORButton" class="button">Perform OR operation</button>
<p id="OR_result">Result:</p>
</div>

### NOT Gate
if NONE of the inputs are **true**, then there will be an output. if ONE or MORE of the inputs are true, then there will be an output.