---
title: Zones
description: Areas that can affect the player in many ways
published: true
date: 2024-01-25T11:49:16.700Z
tags: 
editor: markdown
dateCreated: 2024-01-08T13:41:00.765Z
---

>  This page is incomplete and everything in this page is subject to change.
{.is-warning}

Zones are areas in your world that do something when a player goes inside of them. The changes only apply to the players inside the zone.

# {.tabset}
## Build Zone
![zone](/zones/new/build_zone.png =200x)

It allows the player to build inside the zone. Nothing can be built outside of the zone. (text blocks dont work too)

- Whitelist: The player(s) that can build in the zone.

## Sound Zone
![zone](/zones/new/sound_zone.png =200x)

Any player walking in this zone will hear the music of your choice. Any player walking out will stop hearing it.

<video controls>
  <source src="https://yourlocalonion.github.io/media/sound_zone_demo.mp4" type="video/mp4">
</video>

> The descriptions are taken from the roblox documentation.
{.is-info}

- Echo Delay: The amount of time between echoes.
- Echo Dry Level: The output volume of the original sound.
- Echo Enabled: Decides if the echo effect is enabled.
- Echo Feedback: The echo decay every time the echo plays.
- Echo Wet Level: The output volume of the echoed effect.
---
- Pitch Shift Enabled: Decides if the pitch shift effect is enabled.
- Octave: The percentage to shift the original pitch.
---
*unfinished*
## Safe Zone
Players inside this zone will recieve a forcefield.

![](https://yourlocalonion.github.io/media/safe_zone_demo.gif =200x)


## Physics Zone
![zone](/zones/new/physics_zone.png =200x)

Players inside this zone will have settings related to physics changed (gravity, etc.)

![](https://yourlocalonion.github.io/media/physics_zone_demo.gif =200x)


## Ambient Zone
![zone](/zones/new/ambient_zone.png =200x)

Players inside this zone will have settings related to the world's environment changed (world time, fog, etc.)

![](https://yourlocalonion.github.io/media/ambient_zone_demo.gif =200x)


## Camera Zone
![zone](/zones/new/camera_zone.png =200x)

Players inside this zone will have settings related to the player's camera chanhed (camera offset, camera position, etc.)

![](https://yourlocalonion.github.io/media/camera_zone_demo.gif =200x)
