# Dungeon Adventure

## Overview

Dungeon Adventure is a top-down dungeon crawl rpg. Players will use arrow keys to move around the dungeon and spacebar to attack. They will have an inventory with items such as healing potions and power buffs.

After a player clears a dungeon they will be sent to a store where they can spend gold they earned on upgrading thier items or buying more consumables. When the player is ready they can enter another dungeon. As the player clears dungeons the dificulty will increase.

## Functionality and MVP Features

* Each dungeon level will be randomly generated
* level starts hidden and players reveal map as they explore
* Monsters will be randomly spawned on the map
* Players will use arrow keys to move around the dungeon
* Players use space bar to attack and x to switch weapons
* the player must kill all monsters to clear the level
* treasure hidden throughout the level

## Wire Frame

![Page Layout] (src/javascript_project_layout.jpg)

## Architecture and Technologies

* Vanilla javascript
    * Used for gamelogic
* webpack
    * bundle files
* Canvas
    * Used for rendering 
* Howler.js
    * Creating sound effects for different actions
    * play music in the background

## Implementation Timeline

#### Wed 01/09/19:

- [ ] Finish Proposal
- [ ] Reasearch canvas
- [ ] Reasearch how to randomly generate a map

#### Thu 01/10/19

- [ ] Finish splash page design
- [ ] Finish map generation

### Fri 01/11/19

- [ ] Render map in game view
- [ ] Place hero sprite in the middle of view
- [ ] be able to move hero

### Sat 01/12/19

- [ ] Add logic to prevent player from moving through wall
- [ ] Add enemies to map

### Sun 01/12/19

- [ ] Implement Player combat
- [ ] Implement Ai movment and combat

### Mon 01/13/19

- [ ] Implement store between levels
- [ ] Level tracker
- [ ] Bonus features