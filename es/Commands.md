---
title: Comandos
description: Acciones que pueden ejecutarse sobre un jugador
published: true
date: 2023-05-20T18:11:49.801Z
tags: 
editor: markdown
dateCreated: 2023-05-19T16:04:19.466Z
---

# Comandos
> Una parte esencial de la moderación del mundo / mecánica del mundo que permite a los propietarios del mundo ejecutar comandos en los jugadores.
{.is-info}

```
[] = parámetro obligatorio
() = parámetro opcional
```

## Visitante+
## {.tabset}
### cmds
Abre una lista de comandos

### rejoin
Vuelve a unirse a quien ejecutó este comando

### kickabe
Busca en todos los servidores de Wubby y echa a Abe de ese servidor.
(comando de broma y será borrado de esta lista muy pronto)

### Builder+
## {.tabset}
### blind [jugador]
Hace que [jugador] no pueda ver

### blur [jugador] (talla)
Desenfoca la pantalla de [jugador] en una cantidad (tamaño)

### bring [jugador]
Teletransporta a [jugador] a quien ejecutó este comando

### damage/dmg [jugador] (importe)
Disminuye la salud de [jugador] en (cantidad)

### explode/exp [jugador]
Explota [jugador], la explosión puede mover objetos cercanos

### fix/removeeffects [jugador]
Elimina todos los efectos aplicados a [jugador] (desenfoque, fov, ceguera, etc.)

### fling [jugador] (importe)
Lanza a [jugador] a una velocidad de (cantidad)

### fly [jugador]
Hace volar a [jugador]

### flyspeed [jugador] (importe)
Establece la velocidad de vuelo de [jugador] a (cantidad)

### fov/fieldofview [jugador] (fov)
Establece el campo de visión de [jugador] a (fov)

### freeze/anchor [jugador]
Congela [jugador], [jugador] no podrá moverse

### ghost/gh [jugador]
Convierte a [jugador] en un fantasma

### god [jugador]
Hace a [jugador] invencible de todo daño (a menos que muera)

### gyro [jugador]
Evita que [jugador] cambie de orientación

### heal [jugador] (importe)
Aumenta la salud de [jugador] en (cantidad) O la establece en la salud máxima de [jugador] si no se especifica (cantidad)

### highlight [jugador] (brickcolor)
Hace visible a [jugador] a través de paredes con el color (colorladrillo)

### invisible/inv/invis/hide [jugador] (esVisible)
Hace [jugador] invisible, si (esVisible) es "false", el jugador no podrá verse a si mismo

### jump [jugador]
Fuerza a [jugador] a saltar

### jumppower [jugador] (importe)
Cambia el jumppower de [jugador] a (cantidad)

### kill/die [jugador]
Mata a [jugador]

### lightning/smite/thunder [jugador]
Invoca a Zeus y lanza un rayo a [jugador].

### magnet [jugador] (importe)
Atrae a todos los jugadores hacia [jugador] con una fuerza de (cantidad)

### maxhealth [jugador] (importe)
Establece la salud máxima de [jugador] en (cantidad)

### mensaje/m/msg/shout/announce [jugador] (mensaje)
Muestra (mensaje) en la pantalla de [jugador]

### nuke [jugador]/[coordenadas]
Coloca un nuke en [jugador]/[coordenadas]

### removelimbs [jugador]
Elimina las extremidades de [jugador]

### respawn [jugador]
Respawns [jugador], Básicamente quita el personaje de [jugador] y lo coloca donde estaba

### sit/trip [jugador]
Obliga al [jugador] a sentarse

### sparkles/sparkle [jugador] (color)
Le da a [jugador] unos destellos con el color (color)

### team name/teams name [equipoNombre] [nuevoNombre]
Cambia el nombre de [equipoNombre] a [nuevoNombre].

### team set/teams set [jugador] [equipoNombre]
Establece el equipo de [jugador] en [nombredeequipo].

### to/tp/teleport (jugador) (jugador2)/(coordenadas)
Si no se introducen parámetros, este comando teletransportará a quien lo haya ejecutado a la posición del ratón.
Si se introduce (jugador), este comando teletransportará a quien ejecutó este comando a (jugador)
Si se introducen (jugador) y (jugador2), este comando teletransportará a (jugador) a (jugador2)
Si se introducen (coordenadas), este comando teletransportará a quien ejecutó este comando a (coordenadas)

### trail [jugador] (color)
Pone un rastro en [jugador], su color será (color)

### unblind [jugador] (color)
Hace que [jugador] pueda ver de nuevo

### unblur [jugador]
Desenfoca la pantalla de [jugador]

### unfly [jugador]
Elimina la capacidad de volar de [jugador]

### unfreeze/thaw/unanchor [jugador]
Descongela a [jugador]

### ungod [jugador]
Hace a [jugador] vulnerable al daño

### ungyro [jugador]
Permite a [jugador] volver a cambiar de orientación

### unhighlight [jugador]
Elimina el resaltado de [jugador]

### unmagnet [jugador]
Elimina el imán de [jugador]

### visible/vis [jugador]
Hace [jugador] visible otra vez

### walkspeed [jugador] (importe)
Cambia la velocidad de [jugador] a (cantidad)

## Admin+
## {.tabset}
### ban [jugador]
Evita que [jugador] entre en el juego

### kick [jugador] (razón)
Expulsa a [jugador] con la razón (reason)

### stat/stats add [statNombre]
Crea un nuevo stat con el nombre [statNombre]

### stat/stats name [nombredeestat] [nuevoNombre]
Cambia el nombre de [statNombre] a [nuevoNombre].

### stat/stats remove [nombredeestat]
Elimina la estadística con el nombre [statNombre].

### stat/stats set [statNombre] [jugador] (valor)
Establece el valor de [statNombre] de [jugador] a (valor)

### stat/stats visible [statNombre] (esVisible)
Cambia la visibilidad de [statNombre], si (esVisible) es "false", [statNombre] no se mostrará en la lista de jugadores

### team/teams add [equipoNombre] (equipoColor)
Crea un nuevo equipo con el nombre [equipoNombre] y el color (equipoColor). Si no se especifica (colorEquipo), el equipo se creará con un color aleatorio.

### team/teams autoassign [equipoNombre] (isEnabled)
Establece si los nuevos jugadores deben ser asignados automáticamente a [equipoNombre] o no. Si hay varios equipos con esta opción activada, el jugador será asignado al equipo con menos jugadores.

### team/teams color [equipoNombre] [equipoColor]
Cambia el color de [equipoNombre] a (equipoColor)

### team/teams remove [nombredelequipo]
Elimina el equipo con el nombre [nombredeequipo].

### unban [jugador]
Permite a [jugador] unirse al juego