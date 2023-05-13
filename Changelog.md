---
title: Changelog
description: The game's changelog for people who aren't in the discord
published: true
date: 2023-05-13T06:15:03.361Z
tags: 
editor: markdown
dateCreated: 2023-05-13T05:57:37.428Z
---

# 2022
## December
### December 7
```diff
+ added around 12 blocks
+ added an special category
+ added multiple block transform tool
+ added a new way to select brickcolors
+ if you attach the properties gui to one side of the screen, the undo and redo button and the grid size panel will go to the other side

* changed how spheres work so now they resize in a custom way
* changed a bit how blocks are displayed to allow search in the future
* made undo and redo button a bit smaller
* changed overall the size of the gui so it fits bigger screens better

- fixed a bug that somehow broke setnetworkserver and hidetextures properties
- fixed some lag issues
- fixed a bug in which blocks wouldn't load when trying to load in
```

### December 8
```diff
+ added search bar for block search
+ added search bar for enum search
+ selected enum by default will highlight

* fixed how the enum selector works so it's less prone to breaking
* replaced some things around
* turned most of the gui into scale so it fits better in larger and smaller devices

- fixed a bug related to the transform tool not closing correctly
- fixed resize resizing in a weird way
- fixed move tool so it now goes in the right way
- fixed a really important bug in which blocks affected by the transform tool would continue being cancollide off after turned off
- fixed a bug in which the selection box would not clear correctly
```

### December 9
```diff
+ added z, x and c keybinds to select modes in the transform tool
+ holding ctrl while clicking on an already selected part will deselect it
+ added text block

* changed how building and editing works for future compatability with wiring (a bit broken, will fix tomorrow)
* changed some variable settings so they're more precise

- fixed resize from doing pretty weird stuff
- resize will no longer turn a part into a thin piece of paper and move it in a weird way at the same time
- multiple selection no longer selects already selected blocks
- the transform tool no longer makes really big jumps between grabs
- move tool has been fixed so now every part follows the main part instead of its own axis
- fixed a bug in which the selection would not recognize clicks sometimes
- fixed a major bug in which every single gui turned off when the player died
- removed some useless lines of codes so the game runs with less lag
```

### December 10
```diff
+ added font choosing enum
+ added floating text block
+ added burger block
+ added ketchup block
+ added "secret" category

* changed how the main block handler works
* changed a lot of internal stuff u guys don't care about lol 💔💔

- fixed undo from literally not working with the edit tool, paint tool and transform tool
- same applies to redo
- fixed a bug in which the enum face select screen would not work for no reason whatsoever
- fixed the edit tool and build tools completely
- fixed text block from not letting some properties apply
- fixed a small lag issue with enums
```

### December 11
```diff
+ added spiked cylinder
+ added octogon
+ added hexagon
+ added inverted cylinder
+ added cylinder cap

+ added prompt block
+ added click block
+ added AND gate
+ added NOT gate
```

### December 12
```diff
+added a goddamn big button to switch between wiring & building
+added a button to switch to connection mode
+added a button to switch to disconnection mode

!+started coding the wiring system
!+added line creation and destruction functions

*added a shit ton of variables to each one of these blocks just because
*made wires more curvy
*made green wires faster
```

### December 17
```diff
+added disconnect tool
+new fancy and cool and epic animations for various shit
+when you focus on one block with the disconnect tool the lines that do not correspond with that block (aka connected to another block and not connected to that block) will get transparent (wiring indicators too) to avoid confusion and increase clarity
+wiring lines now curve more

*changed a bit how wiring works so now when you disconnect something the game makes sure to not power those again until they're powered again
*changed how preview wires look
*changed how normal wires look slightly

-fixed a visual bug in which wires would not appear as active even though they were
-fixed a bug in which gates will sometimes assing the wrong value
```

### December 18
```diff
+added a command system

+added invisible command
+added visible command
+added kill command
+added explode command
+added ghost command
+added freeze command
+added unfreeze command
+added sit command
+added jump command
+added message command (aka shout but you can specify which player can see it)
+added god command
+added ungod command
+added gyro command (locks the character's rotation)
+added ungyro command
+added blind command
+added blind command 

+added "all" to specifiers
+added "me" to specifiers
+added "others" to specifiers
+added "random(number)" to specifiers (selects a specified amount of random players)
+added "%" specifiers (selects a percentage of the players)
+added player specifiers + display name specifiers

*the amount of time in which a message in the message command is displayed depends on how long it is
```

### December 19
```diff
+added lighting command (aka smite but instead of a smite, it kills u with a fucking lighting 💋)
+added nuke command
+added fling command

+added trail command (there's also a special color (🏳️‍🌈), added it cuz um rainbows r cool i swear it hasn't got any relationship with me i swear)
+added highlight command (basically makes the player visible through surfaces)
+added sparkles command

+added heal command
+added damage command
+added max health command

+added magnet command (you can set the force!)
+added unmagnet command
```