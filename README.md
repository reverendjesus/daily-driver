## What is this shit, man‽

This is a nametag program, and I've made every effort I'm able to make to make sure it's random and unpredictable.
DailyDriver requires a micro:bit, with the scroll:bit addon board. It runs a "heartbeat" animation on the micro:bit, and a scrolling ticker on the scroll:bit. 

## heartBeats

The **heartBeat** function picks a random number from 0-100; on 95 of those results, it runs the normal "heartbeat" animation (small heart icon, random pause, large heart icon, random pause, clear screen) on the micro:bit, and then has a 50/50 chance to run one of the lines from the "daily" string array (**dailyScroll**) on the scroll:bit.

4 of the other 5 results display an alternate icon instead of the large heart — still using randomized pauses — and run something from the "alternate" text array (**seattleScroll**) across the scroll:bit. 

"Rolling" a 99 will flash a random number of fast, non-paused heartbeats on the micro:bit, and a string from **seattleScroll** across the scroll:bit.

## Show Mode

Pressing button A&B will, after the current scroll:bit animation is finished, display "metal horns" on the micro:bit, scroll "show mode," and set **concertMode** to true. 

While true, the operation of **heartBeats** will change; 95 of the results will display a heartbeat animation and always scroll a line from the **bandScroll** text array (the idea is that the user changes the **bandScroll** array to whatever bands are playing at the show you're at). The 5 'alternate' heartbeats will scroll a line from **dailyScroll** instead.

Pressing button A&B will display a stickman on the micro:bit and set **concertMode** back to false.

## Magic 8 Ball

Button A will run a "magic 8-ball" function, with a (yes/no/noncommital) answer randomizer, displaying one of the original 20 responses from the actual magic 8-ball, or one of the responses from the "sarcastic 8-ball" parody products floating around in the æther. 
 
 It'll display a short animation on the micro:bit, then one of the response lines from the **8ball** function on the scroll:bit.
 
 ## Arcane Bullshit
 
 Button B randomly displays an Elder Futhark rune on the micro:bit, and the name of a random [Arcane Bullshit](https://arcanebullshit.com/) tarot card on the scroll:bit.

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/reverendjesus/daily-driver** and import

## Edit this project ![Build status badge](https://github.com/reverendjesus/daily-driver/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/reverendjesus/daily-driver** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/reverendjesus/daily-driver/raw/master/.github/makecode/blocks.png)

## LICENSE

Kopyleft [FSoFCabal.com](https://www.fsofcabal.com) 2020

All rites reversed; re-use as you like

> Open this page at [https://reverendjesus.github.io/daily-driver/](https://reverendjesus.github.io/daily-driver/)

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>



> Open this page at [https://reverendjesus.github.io/daily-driver2/](https://reverendjesus.github.io/daily-driver2/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/reverendjesus/daily-driver2** and import

## Edit this project ![Build status badge](https://github.com/reverendjesus/daily-driver2/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/reverendjesus/daily-driver2** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/reverendjesus/daily-driver2/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
