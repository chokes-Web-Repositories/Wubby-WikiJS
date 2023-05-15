---
title: Changelog
description: The game's changelog for people who aren't in the discord
published: true
date: 2023-05-15T06:35:55.663Z
tags: 
editor: markdown
dateCreated: 2023-05-13T05:57:37.428Z
---

<p id='unix-timestamp'>Unix timestamp: t:1650960000</p>

# 2022
## December
### December 6
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

### December 7
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

### December 8
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

### December 9
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

### December 10
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

### December 11
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

### December 16
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

### December 17
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

### December 18
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


### December 22
```diff
+added command block
+added delay gate
+added number storage gate
+added number math gate (add, sub, mult, div, pow and sqrt)
+added number setter gate

*changed drastically how wiring works so now 2 things cannot run at once in the same gate
*new "gate cap" which determines how many actions have the gates done in total in a frame
*changed how wiring works internally so it works faster

-fixed a major bug in which gates couldn't power other gates
-fixed a visual bug in which the preview line wouldn't show
```


### December 24
```diff
+made a ton of gates n stuff placeable
+now you can set if gates are visible or not
+gate part transparency
+added hints on the properties menu, which can go from tutorials to tips and tricks

*changed how gates look cuz they used to be ugly 
*optimized the properties script
*changed every single text inside the gates so they have better color compatability

-fixed a bug in which when adding a connection it wouldn't work if the input was active
-fixed a bug in which the not gate wouldn't power by default
-fixed sliders from working in a weird way
-fixed a bug in which info wouldnt display for some reason
-fixed dropdowns from not showing the text correctly for some reason
```


### December 25
```diff
+made more gates placeable
+made the prompt block placeable
+made the click block placeable
+added useactivationtime to every input gate
+added block touched
+added player touched

+added absolute value, factorial, sin, cosin and tan to the math gate
+now you can change an storage's value through the properties menu
+putting {INPUT} in the value of a math gate/math setter use the input instead of the selected value

*changed how edit recognizes some values
*made the properties menu faster to load
*gates can no longer be resized

-fixed the edit tool 
-fixed a bug in which outputs would instantly power when created for some reason
-fixed the delay gate
-fixed some properties inside the info panels of gates not changing
```


### December 26
```diff
+made even more blocks placeable
+added light block
+started implementing property changer
+added text storage
+added text editing gate
+now you can use {INPUT} on the command block
+speed command
+jump power command
+made player detector placeable
+undo and redo now compatible with wiring
+text filtering to wiring
+made text filtering detect when it's an id of an item
+repeater gate

*message command now shows the message for less time
*message command shows a smaller text

-fixed a visual bug in which wires would seem active when they weren't
-fixed not gate
-fixed some gates not displaying the correct info
```


### December 28
```diff
+property changer 
+text input gate
+added templates 
+blur command
+fov command
+fix command
+unanchored parts now respawn when falling to the void

*changed how sliders work so now they don't flood the undo redo list
*changed how sliders work so their preview loads faster

-fixed a bug in which wiring would go back for no reason at all
```


### December 29
```diff
+added an invisible grid under you so now if there's no block to place something, you'd still be able to place blocks
+tp
+added <1 stud grid
+holding ctrl with the size tool now resizes blocks in both ways

*changed move tool so it supports <1 stud grid
*changed entirely how resize works so it's no longer biggy and supports increments
*changed how move tool works so it uses increments
*resize now also supports rotated parts
*changed the placement system so it supports <1 grid size
*multiple selection no longer selects locked blocks
*some gui adjustments

-fixed another bug related to sliders
-fixed a bug in which placement would place blocks up in the sky for no reason whatsoever
-fixed a lot of templates having offset
-fixed a selection visual bug in which it placed the selection frame 35 ontop of the mouse
-fixed a major bug in which the selection would select random blocks for no reason whatsoever
-fixed a grid size selector bug
-fixed a bug in which it would automatically select some options before the player opened the edit tools
-fixed the if gate checking strings
-fixed the input gate completely
```


### December 30
```diff
+added rejoin command
+added key input block
+added humanoid state changed block
+added a toggle for the do-on-gate system for the math gate
+selected blocks are now shared between the edit and transform tool

*changed how math gates work so now they can do math without any sort of number storage

-fixed tp command
-fixed some lag issues
```
# 2023
## January
### January 1
```diff
+added tap input block
+added cmds 
+added search bar to cmds
+added some animations to the gui
+nuke command now admits coordinates
+bring command
+to command

*changed how multiple selection rotate works drastically so it rotates as a tuple instead of individually
*changed the tool menu completely
*changed how some drags work
*resize no longer turns off its collisions 

-fixed a bug in which selection would occasionally break
-fixed a bug in which changes would apply for only 1 person
-fixed some major lag issues
-fixed a bug related to physics
-fixed a bug in which itd take a lot of time to place a block
-fixed a lot of bugs in which routines would just fail
-fixed tp again
```


### January 2
```diff
+kick command
+unhighlight command
+untrail command
+variable blocks 🔥🔥🔥
+build vector block (broken, will fix asap)
+platformstand on property changer
+seat block
+some mobile support

*changed some input gates so they support input ended and input started
*rotate is now way less laggy
*changed some gui elements again
*changed the text filtering system 

-fixed the unalignment bug for good 🥳🥳
-fixed property changer block
-fixed drags
-tried fixing morph block
-fixed an infinite loop in a script that broke the entire game
-fixed a bug in which the color picker wouldnt appear again if improperly closed
```


### January 3
```diff
+yoo mobile compatability 🔥🔥🔥🔥🔥
+some basic attributes
+added notifications for hints n stuff
+some more animations

*when disconnecting, every possible item now has a red outline around it
*optimized some scripts 

-fixed some pc issues
-fixed some more drags
-fixed paint tool
-fixed material selector
-fixed some templates 
-fixed dropdowns
```


### January 4
```diff
+attributes managers
+surface attribute
+decal attribute
+weld attribute
+rope attribute
+killer attribute
+tripper attribute
+when editing a block, it'll show every single attribute of that block
+maxhealth command
+player identifiers in the cmds menu

*revamped the happy home template
*changed a lot of health related commands so they no longer affect godded players
*chat now closses when selecting a block
*:invisible now has an animation and is more transparent and no longer has a shadow

-fixed a bug in which resize wouldn't resize if a block was really small
-fixed materials (yet again)
-fixed a bug in which dropdowns were not visible if they were at the bottom of the property panel
```


### January 5
```diff
+upgraded happy home
+added baller attribute
+added controllable setting to baller
+jump power attribute
+walkspeed attribute
+animation for changing attributes
+attribute sfx
+point light attribute
+surface light attribute
+spot light attribute
+healer attribute
+damager attribute
+removelimbs command
+prismatic attribute
+rod attribute
+spring attribute
+ballsocket attribute
+teleporter attribute
+block teleporter attribute
+they work with keep velocity
+effect attribute

-fixed way more bugs related to attributes
```


### January 8
```diff
+number sequences
+effect attribute
+sign attribute
+copy colors with c/long press
+added teams and a lot of team related commands
+beam attribute
+highlight attribute
+copying blocks now copy attributes too
+clone block
+vehicle seat
+mesh block
+get game property block
+duplicate selection
+player chatted block
+maxhealth attribute
+teamer attribute
+time command
+gravity command
+added motor block
+added hinge block
+added servo block
+started working on data encryption
+started working on zones

*brickcolors can now be seen through the color selector
*anything that uses images now uses decal id instead of image id
*added attributes to templates
*duplicate selection now compatible with undo and redo
*wires are no longer that curvy
*optimized planet template
*changed how tools layout so they're the same way as world builder
*motor is now wireable

-fixed color picker for mobile
-fixed a grid related bug
-fixed morph blocks
-fixed teamers
-fixed player chatted block
-fixed a bug related to command blocks
-fixed a small bug related to constraints 
-fixed motor, servo and hinge from having a weird orientation
+started working on data encryption
+started working on zones
!-fixed the grid offset bug (finnaly 🥳🥳)
```


### January 13
```diff
+custom physical properties
+attribute changer block 
+thrust attribute
+gravity changer attributes

*command block now can use variables too

-fixed text filtering bugs 
```

### January 14
```diff 
+added sound zone
+implemented a bunch of stuff related to zones
+added zones gui
+added create zones tool

*upgraded rotate

-fixed a bug with templates and physical properties
-fixed a small issue with springs
```


### January 15
```diff
+added safe zone
+added physics zone
+sound zones now update the sound in real time
+physics zone now has support for unanchored parts
+remove zones tool
+edit zones tool
+transform zones tool
+multiple selection on transform zones tool
+zones are now invisible for normal players

*zones now cleanup when removed to reduce lag by a ton
*the color selector is now bigger
*changed how the color selector works so it's more comfortable to use
*selection frame is no longer visible when clicking quickly
*changed how sound zones work so they can be combined to give non square shapes to zones
*changed zone selection slightly

-fixed a bug in which tool selection would act really weird
-fixed the color picker
-fixed zone placing
```


### January 21
```diff
+ parallel wiring
+fly command
+unfly command
+flyspeed command
+added some animations to the gui

* upgraded gui a ton
*color picker is now way bigger
*color picker's marker now uses the inverted color of the selected color
*frames can now be dragged from any point smoothly (unlike grabs smh 😤)
*servers will now run faster due to physics optimization

-removed grabs
-fixed some mobile compatability bugs here and there
-fixed AND and XOR gate
```

### January 22
```diff
+added world id to the core gui
+added game visits to the core gui
+added block count to the game gui
+zones now support undo and redo
+! permissions
+! basic game security
+! permissions panel
+! offline perming
+perm command
+unperm/demote command
+now you'll see yourself in a lighter color in the gui's leaderboard
+press space on flight mode to go upwards
+press ctrl on flight mode to go downwards

*grid size and undo/redo only pop up when building
*command blocks can no longer run admin commands

-fixed a small bug with redo and undo
-fixed a small gui placing bug
-removed the properties panel because the old system was really messy (gonna replace soon dw)
```


### January 28
```diff
+canbuild perm
+build zones
+half sphere
+hollow sphere
+corner cylinder
+corner cylinder 2
+edge wedge
+edge sphere
+inverted edge sphere
+saving system prototype
+copy blocks in mobile by holding them down
+get block property block
+isalive to player property gate 
+properties can now opened and closed
+! game settings
+ small security improvements

*buttons are now easier to click in mobile
*staff can no longer be edited through the perms gui
*mobile can now fly via double jump
*wires are no longer visible by default
*useinput in the property changer gate now also determine the selected block

-fixed a bug in which attributes wouldn't be removed correctly
-fixed unfly not working
-touch input blocks not working
-fixed commands being applied to everyone
-fixed a bug in which indicators could be seen when selecting a block
-fixed a small performance bug
-fixed some mobile issues
-fixed flight in mobile
-fixed gethit
-fixed build vector
-fixed max health
-fixed the block count
-fixed a small bug related to shout
-fixed players not being able to run commands
-fixed property changer block
-fixed wubby detecting the wrong device
-fixed selection not closing when the main menu closes
```


