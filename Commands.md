---
title: Commands
description: Actions that can be executed on a player
published: true
date: 2023-05-19T02:55:38.815Z
tags: 
editor: markdown
dateCreated: 2023-05-14T15:48:24.092Z
---

# Commands
> An essential part of world moderation / world mechanics that allow world owners to execute commands on players
> 
{.is-info}

```
[] = required parameter
() = optional parameter
```

## Visitor+
## {.tabset}
### cmds
Opens a command list

### rejoin
Rejoins whoever ran this command

## Builder+
## {.tabset}
### blind [player]
Makes [player] unable to see

### blur [player] (size)
Blurs [player]'s screen by (size) amount

### bring [player]
Teleports [player] to whoever ran this command

### damage/dmg [player] (amount)
Decreases [player]'s health by (amount)

### explode/exp [player]
Explodes [player], the explosion might move nearby objects

### fix/removeeffects [player]
Removes every single effect applied to [player] (blur, fov, blindness, etc.)

### fling [player] (amount)
Flings [player] at a speed of (amount)

### fly [player]
Makes [player] fly

### flyspeed [player] (amount)
Sets [player]'s flying speed to (amount)

### fov/fieldofview [player] (fov)
Sets [player]'s field of view to (fov)

### freeze/anchor [player]
Freezes [player], [player] wont be able to move

### ghost/gh [player]
Turns [player] into a ghost

### god [player]
Makes [player] invincible from all damage (unless killed)

### gyro [player]
Prevents [player] from changing orientation

### heal [player] (amount)
Increases [player]'s health by (amount) OR sets it to the [player]'s maxhealth if (amount) is not specified

### highlight [player] (brickcolor)
Makes [player] visible through walls with the color (brickcolor)

### invisible/inv/invis/hide [player] (isVisible)
Makes [player] invisible, if (isVisible) is "false", the player won't be able to see themselves

### jump [player]
Forces [player] to jump

### jumppower [player] (amount)
Changes [player]'s jumppower to (amount)

### kill/die [player]
Kills [player]

### lightning/smite/thunder [player]
Summons Zeus and throws a lightning bolt at [player]

### magnet [player] (amount)
Attracts every single player to [player] with a force of (amount)

### maxhealth [player] (amount)
Sets [player]'s maximum health to (amount)

### message/m/msg/shout/announce [player] (message)
Displays (message) in [player]'s screen

### nuke [player]/[coordinates]
Places a nuke in [player]/[coordinates]

### removelimbs [player]
Removes [player]'s limbs

### respawn [player]
Respawns [player], Basically removes the [player]'s character and places it where it was

### sit/trip [player]
Forces [player] to sit

### sparkles/sparkle [player] (color)
Gives [player] some sparkles with the color (color)

### team name/teams name [teamName] [newName]
Changes [teamName]'s name to [newName]

### team set/teams set [player] [teamName]
Sets [player]'s team to [teamName]

### to/tp/teleport (player) (player2)/(coordinates)
If no parameters are entered, this command will teleport whoever ran this command to their mouse position
If (player) is entered, this command will teleport whoever ran this command to (player)
If (player) and (player2) are entered, this command will teleport (player) to (player2)
If (coordinates) are entered, this command will teleport whoever ran this command to (coordinates)

### trail [player] (color)
Puts a trail in [player], its color will be (color)

### unblind [player]
Makes [player] able to see again

### unblur [player]
Unblurs [player]'s screen

### unfly [player]
Removes [player]'s ability to fly

### unfreeze/thaw/unanchor [player]
Unfreezes [player]

### ungod [player]
Makes [player] vulnerable to damage

### ungyro [player]
Allows [player] to change orientation again

### unhighlight [player]
Removes [player]'s highlight

### unmagnet [player]
Removes [player]'s magnet

### visible/vis [player]
Makes [player] visible again

### walkspeed [player] (amount)
Changes [player]'s walkspeed to (amount)

## Admin+
## {.tabset}
### ban [player]
Prevents [player] from joining the game

### kick [player] (reason)
Kicks [player] with the reason (reason)

### stat/stats add [statName]
Creates a new stat with the name [statName]

### stat/stats name [statName] [newName]
Changes [statName]'s name to [newName]

### stat/stats remove [statName]
Removes the stat under the name [statName]

### stat/stats set [statName] [player] (value)
Sets [player]'s [statName] value to (value)

### stat/stats visible [statName] (isVisible)
Toggles the visibility of [statName], if (isVisible) is "false", [statName] will not be shown on the playerlist

### team/teams add [teamName] (teamColor)
Creates a new team with the name [teamName] and the color (teamColor). If (teamColor) is not specified, the team will be created with a random color

### team/teams autoassign [teamName] (isEnabled)
Sets if new players should be automatically assigned to [teamName] or not. If there are multiple teams with this setting enabled, the player will be assigned to the team with the least players

### team/teams color [teamName] [teamColor]
Changes [teamName]'s color to (teamColor)

### team/teams remove [teamName]
Removes the team under the name [teamName]

### unban [player]
Allows [player] to join the game