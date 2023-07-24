# Professional Demolition Service - Design Document

## Table of Contents

1. [Introduction](#introduction)
    1. [Game Summary](#game-summary)
    2. [Platform](#platform)
    3. [Genre](#genre)
    4. [Inspiration](#inspiration)
        1. [GTA2](#gta2)
    5. [Theme Interpretation (Do No Harm)](#theme-interpretation-do-no-harm)
    6. [Player Experience](#player-experience)
    7. [Development Software](#development-software)
    8. [Development Team](#development-team)
2. [Art and Music](#art-and-music)
3. [UI](#ui)
4. [Controls](#controls)
5. [Game Jam Minimal Viable Product](#game-jam-minimal-viable-product)
    1. [Time limit mode](#time-limit-mode)
    2. [Sandbox mode](#sandbox-mode)
    3. [Tutorial](#tutorial)
6. [Miles Stones / TODO](#miles-stones--todo)
7. [Other Documents](#other-documents)
    1. [Story](story.md)

## Introduction

### Game Summary

Top down view game where player controls different physics based hard industry vehicles (crane with wrecking ball) in kinda medieval setting with goal to demolish buildings, monsters and environment. Player needs to be careful not to harm people, their environment (and everything else that is not the target).

### Platform

The game will be developed for PC and should be available on Steam and fully playable on SteamDeck.
Going with simple approach game may be playable on web browser during early stages of development.

### Genre

2D racing, road rage destruction game with RPG elements and simple story plot.

### Inspiration

#### GTA 2

Top down view, simple controls, road rage, destruction, mayhem.

### Theme Interpretation (Do No Harm)

While main game mechanics is driving and swinging wrecking ball, player needs to be careful not to harm everything else as it may cost him money or even game over.

### Player Experience

While driving wrecking ball is not attached to the crane and is swinging around on a rope. Crane is attached on top of the moving platform and can be rotated around. Player can use this mechanics along with vehicle movement to swing wrecking ball around and hit targets. Or to dampen the swing and keep the possible undesired damage to minimum.

While driving there are other vehicles and pedestrians around that player needs to be careful not to harm. Also there are other objects like trees, animals, etc. that player needs to avoid.
Also while demolishing buildings there may bricks and other objects falling down that also may damage other objects, vehicles and pedestrians that are moving by.

### Development Software

Primary development software will be Godot 4.
For 3D modeling and texturing Blockbench.
For sketching and concept art Leonardo will be used.
For music and sound effects Audacity and Sonic Pi (bad in music, but this allows to create music by code)

### Development Team

Solo developer with a lot of knowledge about software development and coding in general, but still bad 3d modeling skills, music skills and even worse art skills.

## Art and Music

Would be great to have low poly 3D models to have simple and basic world destruction. World will be mostly static with some moving objects like cars, carriage with horses, pedestrians, animals, etc. Trying to replicate most of GTA 2 style, but in more medieval setting with only exception that player will be driving somewhat modern crane with wrecking ball.
Random medieval music may do with generic sounds effects for hits, brick falling and when pedestrians are hit. Later something unpleasant as bug squishing may be added (for alien bug squishing and maybe animals).

## UI

Important aspects of UI include:

- classic dialog boxes like in old RPG games or maybe comic like.
- information about current mission and objectives. Timer and score if needed.
- hit/smash affects and damage indicators when damaging buildings, vehicles and pedestrians. (different for each)
- minimap with current location and objectives.
- general direction indicator (compass) with current objective.
- at later development stages - inventory and equipment for vehicle improvements and modifications.

## Controls

Basic controls will be WASD for movement and mouse for controlling the crane and wrecking ball. Escape for pause menu.
In future Space may be used for handbrake and Shift for acceleration. (when drifting mechanics is fully introduced)
Tab may be used for inventory and equipment menu and/or map when introduced.

## Game Jam Minimal Viable Product

### Time limit mode

Game should include basic crawler crane with wrecking ball with physics controlled by keyboard and mouse.
Player should be able to drive crane around and swing wrecking ball around destroying marked buildings and other objects and avoiding pedestrians, other vehicles and objects that are not marked for destruction.
For every destroyed building player should get some points and for every destroyed pedestrian, vehicle or other object player should lose some points or punished in some other way (like time penalty or game over if damage is too high).
Goal is to bit the high score in limited time.

### Sandbox mode

Same as Time limit mode, but without time limit and with more freedom to explore the world and destroy everything.

### Tutorial

If time allows, there should be a tutorial level that introduces player to the game mechanics and story.

## Miles Stones / TODO

- [x] Basic driving mechanics with crane and wrecking ball. (without assets, using placeholders)
- [x] Basic physics for wrecking ball and crane.
- [ ] Basic physics for buildings and other objects.
- [ ] Building destruction mechanics.
- [ ] Basic physics and AI for vehicles and pedestrians.
- [ ] Minimalistic UI with basic information about current mission and objectives.
- [ ] Minimalistic 2D assets for vehicle, crane, wrecking ball, buildings, vehicles, pedestrians, etc. (in that order)
- [ ] Basic sound effects
- [ ] First tutorial/story introduction level.
- [ ] Basic game loop with start, pause, end and restart. As Sandbox mode.
- [ ] and more if I ever get this far...

## Other documents

1. [Story](story.md)
