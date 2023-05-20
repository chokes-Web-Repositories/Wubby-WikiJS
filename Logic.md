---
title: Logic
description: The blocks that make it possible to create a mechanic in your world
published: true
date: 2023-05-20T10:41:05.789Z
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
<label for="input1">Input 1:</label>
<input type="checkbox" id="input1" class="input">
<label for="input2">Input 2:</label>
  <input type="checkbox" id="input2" class="input">
<button onclick="performAND()">Perform AND Gate Operation</button>
<p id="result">Result:</p>

### OR Gate
only one or more **true** inputs is needed to give an output, if all of the inputs are false there will be no output.

### NOT Gate
if NONE of the inputs are **true**, then there will be an output. if ONE or MORE of the inputs are true, then there will be an output.