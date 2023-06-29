---
title: Hats
description: Floating wearable cosmetics on your player character
published: true
date: 2023-06-29T18:56:47.507Z
tags: 
editor: markdown
dateCreated: 2023-05-20T13:19:01.276Z
---

> This page talks about an unreleased feature.
{.is-danger}

There is currently no info for this page.

<p id="demo"></p>

<script>

var countDownDate = new Date("July 4, 2023 11:00:00").getTime();

var x = setInterval(function() {

  var now = new Date().getTime();

  var distance = countDownDate - now;

  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  document.getElementById("demo").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";

  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "WUBBY IS RELEASED";
  }
}, 1000);
</script>

Hats from the [Megathread](https://discord.com/channels/1049644155246227466/1050934352978133033) may be added to the game.