---
title: Changelog
description: The game's changelog for people who aren't in the discord
published: true
date: 2024-02-02T22:37:35.040Z
tags: 
editor: markdown
dateCreated: 2024-01-08T13:40:37.581Z
---

> This page *should* be up to date with Wubby V8.
{.is-success}

> This page will automatically update dates depending on your local timezone.
{.is-info}

> Wubby was released on t:1688520360:D
{.is-info}

[comment]: # (Please use https://www.unixtimestamp.com/ to add dates.)

# 2022
## December
### <b>t:1670342400:D</b>
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

### <b>t:1670428800:D</b>
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

### t:1670515200:D
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

### t:1670601600:D
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

### t:1670688000:D
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

### t:1670774400:D
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

### t:1671206400:D
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

### t:1671292800:D
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

### t:1671379200:D
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


### t:1671724800:D
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


### t:1671897600:D
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


### t:1671984000:D
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


### t:1672070400:D
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


### t:1672243200:D
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


### t:1672329600:D
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


### t:1672416000:D
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
### t:1672588800:D
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


### t:1672675200:D
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


### t:1672761600:D
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


### t:1672848000:D
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


### t:1672934400:D
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


### t:1673193600:D
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


### t:1673625600:D
```diff
+custom physical properties
+attribute changer block 
+thrust attribute
+gravity changer attributes

*command block now can use variables too

-fixed text filtering bugs 
```

### t:1673712000:D
```diff 
+added sound zone
+implemented a bunch of stuff related to zones
+added zones gui
+added create zones tool

*upgraded rotate

-fixed a bug with templates and physical properties
-fixed a small issue with springs
```


### t:1673798400:D
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


### t:1674316800:D
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

### t:1674403200:D
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


### t:1674921600:D
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

### t:1675008000:D
```diff
+ team name and team set can now be ran by command blocks
+ stat saving
+ added stats, set stat gate, get stat gate
+ added gear block (V136)
+ added a basic loading screen (V137)
+ mobile players can now place zones (V138)
+ ok fixed a ton of bugs n stuff (V141)
```

### t:1675094400:D
```diff
* fixed the resize bug and some other bugs like wiring not throwing input sometimes or set stat being broken (V142)
* fixed a major bug with resize in which if you were moving any tool and change tool and quickly switch to another tool, you would break the transform tool (V143)
* fixed the following transform tool bugs
	- quickly switching to another mode (like moving, resizing etc) would not upload to the server
  - if you are moving smt and you change tool, the changes will update to the server
```

## February
### t:1675180800:D
```diff
* fixed some bugs while placing blocks
```

### t:1675353600:D
```diff
* fixed a ton of bugs reported in ⁠🪲bug-reports (V145)
	- camera lock should be fixed in mobile
	- marbles no longer weight so you can fly with one of them
	- confirm button not showing in mobile
	- text input placeholder text fixed
	- text input bottom position fixed
	- block default to non collide (hope this annoying one is fixed)
  - attributes now remove when clicking twice
```

### t:1675440000:D
```diff
+ added a report game button
+ command blocks can now use admin commands as long as the last person who edited it is an admin and still permed

* fixed a small annoying core bug
* fixed morph block for good
* hopefully fixed the random blocks deleting bug
* fixed permissions and other small bugs like number setters and number math (V147)
```

### t:1675526400:D
```diff
+ added a button for mobile players to fly

* fixed a small block facing bug
* fixed a major bug in which spamming the transform buttons would really bug the selected button
* fixed flight activating when holding space
* fixed a bug in which you couldn't jump/ go up in fly
* fixed motor however it spins in its own axis hope u guys don't mind
* fixed a bug in which input blocks couldn't be attribut'd
* world name and description can now be edited (V150)
* bug fixes (V151)
* fixed highlight attribute being deleted
* fixed zone placement (V152)
```

### t:1675612800:D
```diff
+ added sound block (V157)

* fixed sound zones
* applied a fix to the transform bug in which the gui wouldn't pop up for some reason
* fixed brickcolors (selecting brickcolors grr)
* fixed zones placement (again) (V154)
* added modulus and atan to math gate
* added display message block (output) (V155) (lets you display notifications and chat messages)
* fixed game settings
* fixed game breaking bug in which the report button wasn't visible (V156)
```

### t:1676044800:D
```diff
+ wubby now runs faster since ive updated the physics handler script

# currently working on saving

* fixed a bug in which notifications wouldn't filter + use {INPUT}
* fixed a bug when cloning wiring
```

### t:1676131200:D
```diff
* fixed the block count and now walkspeed and jumppower game properties update in real time
* fixed a small vulnerability related to build zones
```

### t:1676217600:D
```diff
! currently making everything work together
```
![](https://cdn.discordapp.com/attachments/1051156891880935565/1074366897811894412/PXL_20230212_172934727.jpg =60%x)

### t:1676649600:D
```diff
+ game setup gui now works

* fixed a major bug in which some settings would straight up not change
* fixed some bugs related to load in
```

### t:1676822400:D
```diff
+ search games/id (allows checking which game you're about to play)
```
![](https://media.discordapp.net/attachments/1051156891880935565/1076619327748440225/PXL_20230218_224015185.jpg?width=496&height=662 =60%x)

### t:1676908800:D
```diff
+ joining a player in wubby will now teleport you to their game
+ linked the game itself with the hub
+ visits and blocks are now visible
```

### t:1677254400:D
```diff
+ kick & ban now teleports you to the hub
+ kick & ban now has an optional reason parameter

* fixed quick buttons on the core gui (quickly perm/kick/ban someone)
```

## March
### t:1678032000:D
```diff
+ fixed loading in not loading attributes and wiring correctly
+ attributes and wiring are fixed
+ fixed saving
```

### t:1678550400:D
```diff
+ attributes save
```

### t:1678636800:D
```diff
+ fixed a bug in which if you loaded in before wubby, guis would not load
+ fixed a bug in which you couldn't modify game properties
+ added allow reset and allow rejoin game settings (allow rejoin enables/disables the :rejoin command (which is on by default))
+ added no collision attribute
+ added some hints here and there on attributes
+ fixed a bug in which properties would not be established
+ fixed wiring
```

### t:1679068800:D
```diff
+ fixed some attributes
+ fixed a bug related to placing attributes
+ fixed a bug related to wiring on startup
+ fixed a memory leak
+ fixed bug in which wiring wouldn't wire
+ the game freezes until the entire game loads in so y'know structures like cars n such don't break on startup
```

### t:1679155200:D
```diff
+fixed a bug in which sometimes some properties would not show up in the attributes menu
+ fixed thrusts
+ fixed a bug in which you couldn't move with wasd when going upwards/downwards flying
+ fixed bug that attributes wouldn't completely load in
```
### t:1680274800:D
```diff
+ added field of view game setting
+ added extra layer of security
+ removed the following properties in the get player property block:
VelocityX, VelocityY, VelocityZ, PositionX, PositionY, PositionZ, RotationX, RotationY, RotationZ,
MouseHitX, MouseHitY, MouseHitZ
+ replaced them with the following properties:
Velocity, Position, Orientation, Mouse3DPosition
+ added a "break vector block"
+ added a screen when first playing wubby that warns players to not um violate roblox tos
+  cleaned up some animations
```
## July
### t:1688520360:D (Release)
```diff
! released wubby
+attribute changers now use the input if the property matches

*raised free worlds from 20 to 50
*gears no longer show up when you're building

-fixed the if gate from always powering true with text
-fixed the game property gate
-fixed a big vulnerability that would let you edit ANYTHING in the game
-removed "ghost servers"
-fixed f11
-fixed searching by id
-somewhat fixed actives
-fixed boolean values on the attribute changer block
-fixed the morph block
-fixed the 2 owner bug more or less
-fixed some problems with duplicating
```

### t:1688665363:D
```diff
+added a daily streak system
+added featuring
+added stat teleporter attribute
+added delay property on every teleporter
+added ignoredeactivation property in the delay gate

*message command no longer requires a player

-! fixed actives for once
-! fixed wiring breaking for no reason when rejoining
-fixed fonts turning weird when rejoining
-fixed set stat gate
-fixed settings saving
-fixed stat visible
-fixed textures not appearing
-fixed banning people
-fixed welds with property changers 
```
### t:1688832062:D
```diff
+added cooldown property to the clone block
+added target rotation to clone blocks
+added dodecahedron
+added fence
+added egg
+added stairs

*you can now wire things from outputs which just yields until their assigned task is done
*reporting now requieres atleast 10 characters (stupid reports really went down to zero with this change lol)
*morph blocks now waits until your character has loaded in preventing some issues
*clicking twice on the same block while placing 2 block attributes no longer does anything

-fixed global banning
-fixed an issue that would let players change ANY PROPERTY through the property changer
-fixed baller movement
-fixed wiring not hiding the inventory correctly
-fixed menu not hiding the inventory correctly
-fixed changing some attributes
-fixed delay on teleporters
-fixed stat teles
-fixed some animations
```

### t:1689092597:D
```diff
+added lookvector property for the get player property gate
+added stat block (for lazy people)
+added player event block
+added nukechoco command

* changed how parallel wiring works
*changed some documentation

-fixed a bug that would make the set stat gate multiply decimals
-fixed change signal block
-fixed apply impulse on physics zones
-fixed text input on bottom from not showing the controls
-fixed temp bans lo
-fixed kickabe command
```

### t:1689526009:D
```diff
+added clean command
+added some properties that allow you to change how body parts are

*changed how some numbers are filtered
*lowered the chances of actives not loading in on the first try
*clone blocks can no longer clone other clone blocks

-fixed changing size to effects
-fixed tshirt property
-fixed shirt property
-fixed pants property
-fixed target rotation on clone blocks
-fixed resizing in build zones
-fixed /c system and /team
-fixed rotation increment for plus
-fixed useinput in the property changer
```

## August
### t:1690941480:D (V2.0.16 | NPC Update)
```diff
+! npcs
+! path blocks
+ "motor orientation" to servos, motors and hinges
+ added a bunch of aliases for different blocks
+ added get npc property gate
+ path modifier attribute
+ message shout options for message display
+ message color for message display
+ message time for message display
+ attach block setting "replace existing blocks"
+added byte, length and packsize to text editing gates

* jump command now ignores if you're mid air
* changed how some blocks load in, so mechanisms with these blocks no longer break
* changed how blocks setup, so now there should be less bugs with precise first times
* affect npcs properties in attributes has been replaced by a dropdown that lets you customize what will attributes affect
* wiring is now a bit faster
*anchoring blocks now resets their angular velocity too
*menu now orders players by how important they are

-! fixed motors
-! fixed hinges
-! fixed servos
-! fixed variables
-! fixed effects maybe
-! impulse command is FIXED!!!
- fixed some animations
- fixed some freecam problems
- fixed burn command
- fixed trails
- fixed some wiring problems
- fixed property changers with enums
- fixed how some attributes get edited
- fixed setting mesh ids after placing mesh blocks
- fixed stat save false
- fixed block count
- fixed setting attributes faces manually
- fixed duplicating attributes with the duplicate selection tool
```

### t:1691114280:D (V2.0.20)
```diff
+ npc transparency
+ search bar for dropdowns
```

### t:1691546280:D (V3.0.10 | Camera Update) 
```diff
+! camera blocks
+! camera zones
+ name property to get npc property gate
+ normal property to text editing gate
+ drop-down search bar
+ drop-down hints
+ dropper tool for vectors
+ filter properties
+ stat show command
+ added mouse movement to touch detector
+ added get num npcs alive to get game property

* number sequences no longer require ">" to work (the "omggg i can't set size" bug)
* changing perms no longer changes ur tool if you're still permed

- fixed attributes dropdowns
- fixed the annoying "sliders setting all to 0" when dragging bug
- fixed attach block debris
- fixed some attributes with attach blocks and clone blocks
- fixed hints still being there after removing attributes
- fixed pixels per stud being a boolean
```

> V3.013 got pushed few hours after.
{.is-info}

```diff
- fixed sliders not working
- fixed getting out of ambient zones
- fixed paint tool
```

### t:1691805480:D (V3.1.17)
```diff
+! npc teams
+ bubble setting to message display blocks (works with players, npcs and blocks)
+ camerashake command
+ cameraoffset command
+ added loop through all npcs into loop through everyone gate
+ pyramidal frustum
+ conical frustum
+ vector dropper now supports velocity
+ double block attributes now show the block they're linked to

* rejoin now sends you to the hub if you're the only player on the server
* any command that kicks the player is now instant and more exploiter-proof
* build zones now show their limits

-! fixed build zones
- fixed number sequences being negative
- fixed exiting ambient zones
- fixed camera zone killing you for no reason
- fixed core menu not appearing when creating a world
- fixed switching from one camera zone to another
- fixed switching from a sound zone to another
- fixed duplicating wiring
- fixed rotating slider setting grid size to 0.01
- made npcs a bit more performant
```

### t:1692064680:D (V3.2.6)
```diff
+ npcs now climb trusses correctly

* changed how npcs chase and they should be smarter now
* r6 ballers and ragdolls will now change the camera focus to the center of your character to avoid seizures

- fixed if gates
- fixed wiring overall
- fixed r15 attach blocks
- ballers and ragdolls no longer mess up the camera on a camera zone
```

### t:1692237480:D (V3.3.4)
```diff
+ noclip command
+ clip command
+ :notepad command
+ animations for the gui
+ cameraoffset and camerashake now have animations to reduce eyestrain
+ icons for the gui
+ ;freecamstiff command
+ documented :time
+ no output property for storage changer gates

* lastedited is now a player command
* when you select a transparent block, it's surface box will now be invisible
* when transforming blocks, their outlines are now hidden until you release the mouse

-! made some important fixes to saving 
- fixed set stat taggin
- attach blocks without collision now don't get detected by raycasting 
- fixed unburn
- removed dummy
```

### t:1692323880:D (V3.4.7)
```diff
+! water world settings
+! water configuration to ambient zones
+ gui improvements overall
+ search bar for attributes
+ icons for attributes

* changed how npcs die to be more performant and have less physics glitches
* gui adjustments

-! fixed attach blocks despawning probably
- fixed editing some properties inside build zones
- fixed ballers detaching your camera
```

### t:1692410280:D (V3.4.12)
```diff
+! :clearduplicates command

-! saving now does some extra checks when saving blocks to ensure that there are no duplicates
- fixed using rotation with the property changer
- fixed setting mesh ids
- wubby now does a few extra checks after inserting the scripts to ensure that the world doesn't load in twice
```

### t:1692755880:D (V3.5.2)
```diff
+! added a lot of chat configuration settings to the world settings (14 to be exact)
+! time cycle world setting lol 😹😹
+ smoke attribute
+ fire attribute
+ sparkles attribute

* :mute now hides the input bar too

-! fixed spawning npcs with wiring
- fixed loading being infinite
- fixed setting images on attributes
```

## September
### t:1695002280:D (V??.??.?? (V4 or V5 i forgot) | Commercial Update)
```diff
+! in-world shop
+! shop
+! hats, auras and chat tags
+! inventory
+! local output block
+! wirer block
+! backups
+ you can now buy wubbits with robux
+ plus perk: you get more wubbits from worlds
+ plus perk: free chat tag and hat
+ plus perk: 2 extra backups
+ plus perk: equip 2 auras at once
+ added world settings to control if u want items from the wubby shop in your world
+ shop purchase block (input)
+ player has pass gate
+ camera coordinates in get player property gate
+ normal players can now set a block's color to 0 0 0
+ readvariables command (shows all the wiring variables in the notepad)
+ upgraded how variables filter
+ world owners can do purchase tests to test if their stuff work
+ gui improvements

*! drastically changed how wubbits are obtained
*! drastically changed how npcs check for players (massive optimization improvement)
*! drastically changed how most input blocks work (another massive optimization improvement)
*! drastically changed how some touch attributes are handled (handled by clients, much more performant and instant)
* not, and, xor and or gates now do a "cleanup" when fired, removing unnecessary inputs and outputs
* if you're not permed the "perm ur friends" notification won't appear anymore
* wiring is now slightly faster checking inputs
* command blocks now require the last player who edited them to have the "can use commands"
* placed mesh blocks now get hidden when saved, to avoid issues
* cloned wiring is no longer dropped if it's inside the cloned model
* cloned and attached blocks now listen for input if they're handled on the server 

-! fixed the annoying npc stutter bug
- removed the player parameter from the message command
- fixed attach block tping you sometimes
- fixed some wiring blocks not deactivating
- parallel wiring and local outputs cannot be cloned anymore
- fixed sky bottom not saving
- fixed player chatted's cooldown
- fixed NaN in a lot of commands
- fixed R6 not having forcefields
- fixed ragdolls having a standing still seizure
```

## November
### t:1699235880:D (V8.13.21 | Transform+ Update)
> The changelog is so long lmaoo - onion

```diff
+! hugely revamped the transform gui
+! global movement
+! non pivot rotating
+! dragging
+ passes and items now support decal ids
+! tutorial template + small gui tutorial
+! added "safe mode" world status (temporarily disables wiring, attributes (except newly placed), special blocks and temporarily freezes physics (anchors all blocks))
+! implemented the "backrub" saving system which makes saving faster, more lightweight and more reliable
+! added a lot of sounds (opening the menu, clicking a boolean, etc)
+ added "(team name)" player identifier that selects every player inside a team
+ added a lot of game juice and game feedback
+ added "(team name)"{number} player identifier which selects {number} random players in a team
+ added "(team name)"{number}% player identifier which selects {number}% of the players in a team
+ added reverb, pitch shift and echo settings to newly placed sound zones
+ on mobile, now you can hold on a block to add/remove it from the selection
+ added color correction settings to world settings / ambient zones
+ added anchor settings to the block touch detector
+ added "includes" and "excludes" to the if gate and stat teles
+ added "device" to get player property gate
+ added unattach command
+ added SUPER SECRET BLOCK!!!!
+ added a rules popup button to the hub
+ added 9 auras
+ added 3 hats
+ added ;rotation command which sets a player's rotation

*! cloned and attached input/special blocks now work
* backup failing operation notifications are now more descriptive
* attacking npcs with gears no longer deal damage if their tool is taken away from them
* smart npcs whose tools got taken away from them now toggle on the fleeing state
* changed how :cmds searches commands so it's now more comfortable to use
* the transform tool now uses the last block you selected as the pivot instead of the oldest one
* property changers now have a tiny cooldown to avoid crashes
* changed how some properties sort for the better
* morph blocks are now output blocks too that use a player's name/npc block as input to morph it
* anything that requires images now gets saved in a much more performant way
* changed how rotating and tilting works so now you can rotate a block in any way
* sound zones now muffle when you open the world menu
* usernames are now copyable (menu)
* face transparency now matches head transparency in morph and npc blocks
* upgraded the sign gui (it was ugly)
* the lightning command now accepts coordinates
* attach blocks now output the main block instead of a random one
* variables are now compatible with vectors too

-! fixed undo and redo not saving changes
-! fixed the grid offset bug
-! fixed blocks being weirdly offseted from the pivot block when placing blocks
-! fixed resize not resizing blocks in the correct way
- fixed stocks with gear and stat blocks
- npcs with wander cooldown set to 0 no longer dance like crazy
- tried fixing the "stats not loading" bug
- fixed some gui animations not displaying correctly
- fixed a visual bug while copying blocks
- fixed the path block
- fixed some aspects of the prompt block when using parallel wiring
- fixed running commands at players which names start with "random"
- fixed bool storage
- fixed NaN in the world shop
- fixed world setup jamming
- fixed mesh blocks not saving their texture correctly
- fixed blue resetting when opening the menu
- fixed some hats not showing up correctly
- attribute names no longer tag
- attempted to fix welds breaking on rejoin
- motors, hinges and servos should now break way less often
- fixed setting world name/description through the hub
- fixed placing zones not saving properties
- fixed beam attribute
- fixed rotating and tilting in mobile
- fixed copying colors with c
```

### t:1699667880:D (V8.14.4)
```diff
+! new awesome and juicy and super awesome repeater gate which replaces the old one (logic)
+ new :scale command

*! changed a lot of gate colors

- fixed 360° rotating with property changer and etc
- fixed the annoying selection box bug
- fixed a bug that would display the wrong amount of wubbits when buying something
- fixed anchoring attach/cloned blocks returning to their og pos
- fixed morph blocks on npcs
```

# 2024
## January
### t:1704160680:D
no changelog, deeplinking got added.

### t:1706306820:D (V12.24.26 | Optimization Update)
[original devforum post](https://devforum.roblox.com/t/wubby-changelog-v122426/2810418)
```diff
+! world setting changer block
+! variable support blocks
+! local variables 
+! zone changer block 
+! atmosphere world setting
+! warp attribute
+! break gate
+! new world info panel
+! multiple thumbnails
+! favorite count
+! player list
+! world panel customizable color
+! wubby now uses a much faster networking module that makes connections between the server and the client as fast as possible 
+! WIRING INTERPRETER!!
+ sharing variables through warps
+ added increment setting to repeaters
+ the gui now has new sounds to increase feedback
+ hollow half sphere
+ ingot
+ spiked sphere
+ coil
+ wind world setting
+ gravity world setting
+ cloud world settings 
+ added getting an npc by name et viceversa
+ banned people now display their ban reason
+ "focus block" property in camera blocks that makes your camera focus on a block
+ min and max camera distance properties to the camera zone
+ paint tool now lets you specific whether color material and color or just color or just material
+ 7 new command prefixes: , " & ( ) _ #
+ maxhealth to get player property
+ equippedgear to get player property 
+ ignore deactivation to repeater gates
+ "player despawn delay" world setting
+ healthchanged property to player event block
+ :nightvision command 
+ "clear variables on shutdown" world setting 
+ added a ;spectate command
+ input and output blocks now have images to differentiate them more
+ added frame loop block
+ there's a list of random descriptions u can get for ur world now 
+ "world visible on actives page" world setting
+ added a few keys to the key input block

*! MASSIVE OPTIMIZATION (istg the game feels like it now has 20 extra fps for me)
*! implemented native code to wiring so it runs way faster
*! massive gui changes across the entire game
*! teleporting requests now react better because the player now loads the area before teleporting
*! zones can now have up to 5 different shapes: block, sphere, cylinder, wedge and cornerwedge
*! when ctrl c, the cloned blocks' connections will remain
*! replaced "platform stand" property in property changer blocks by "respect physics"
*! respect physics property in property changers now keep your movement and your momentum
* sound blocks now muffle too when opening the menu 
* npcs now wander in a much more desyncronized way to make them look more human
* normal builders can't see inaccesible blocks anymore
* bulk delete should now crash less
* get npc property now supports npc names
* permissions will now be listed by their importance
* blockstepping in get npc and player property now respects the block's collisions
* get mouse pos now excludes zones
* :team autoassign is now false by default
* attached blocks with attributes no longer affect the player that they're attached to
* some wiring outputs and inputs are now faster
* more properties in wiring blocks are variable compatible 
* :explode now allows coordinates 
* world setting sliders now update in real time
* blocks that used to require the last player who edited them to be the owner now only require the last player to be an admin
* the saving system is now more stable when saving big worlds
* gates no longer render if they're 500 studs away from the camera
* "hold" in path blocks now creates a queue of places to go to
* searching blocks now supports other languages

-! fixed whitelisted, private and banned worlds from being accessed by randos
-! fixed R15 in R6 worlds
-! fixed not being able to change some properties in build zones 
-! fixed some gates not turning off in parallel wiring
-! fixed health changing attributes not correctly setting your health
-! fixed placing triangles
-! fixed and gates on parallel wiring
-! fixed setting a block property in mobile
-! fixed "force" in path block not forcing the npc to move to a certain place the way it should
- fixed dying while ragdoll not resetting your character
- tried fixing the build gui being visible by visitors 
- tried fixing :set stat
- fixed some guis not working on mobile
- fixed some problems with the player touch block
- fixed being able to select npcs' hats
- fixed health regen rate for npcs
- fixed ambient zones not updating in real time
- fixed camera zones not updating in real time
- fixed beam attribute 
- fixed some issues on morph blocks and npcs
- fixed excludes in IF gates
- fixed a bug in which number storages weren't able to store numbers if it did complex calculations earlier
- fixed scrolling through the properties panel of a zone in mobile 
- fixed exiting ambient zones with color correction 
- fixed placing zones in mobile
- fixed players having different colors on their screens
- fixed text property in text input gates
- fixed shoulder accessory in morph blocks and npcs
- fixed placing attributes in build zones
- fixed skyboxes not working sometimes
- fixed not being able to change your status in mobile
- fixed sound blocks
- attempted fixing welds
- tried fixing npc died and was killed events
- fixed renaming backups
- fixed a few problems with attributes' particles 
- fixed some minor gui bugs in the hub
- fixed the rotation command lagging your character
- pressing X on a text input gate should no longer fire the gate
```