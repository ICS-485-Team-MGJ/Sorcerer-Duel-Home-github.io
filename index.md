# Table of Contents
- [Overview](#overview)
- [How to Play](#how-to-play)
- [Team Ideas](#team-ideas)
- [Prototype](#prototype)
- [Final product](#final-product)
- [Team Members](#team-members)
- [Trello Board](#trello-board)

# Overview
Sorcerer's Duel is a tower defense game, but without the tower! Instead, YOU are the tower! Your goal is to defeat the enemy with a wide range of attacks, spells, and soldier units and survive the onslaught of attacks aimed towards you. You can use fireballs to directly damage the enemy from the minute the game starts, or destroy the barriers protecting the enemy using your soldier units to deal more damage. But be careful, the enemy can do the same. The longer the duel lasts, the more powerful the enemy becomes, so be sure to start out strong, prepare for a magical battle and be ready to get your duel on!

- Video of gameplay

## How to Play
### Controls
Movement:
w: move up
s: move down
space: shoot fireball

Spells
1: Meteor shower
2: Laser beam
3: Laser beam special attack

Summoning and Switching Units:
a: switch to left unit
d: switch to right unit
left mouse: summon unit from a barrier by clicking on the barrier you wish the unit to be summoned from.

The goal of the game is to defeat the enemy by dealing damage. You can do this by hitting the enemy with fireballs, or destroying one of the enemy's barriers and sending units to attack that opening. As the game goes on, the enemy will also summon units to attack your barrier. You can defend yourself from these units by sending your own units in the same lane to fight. 

Our game implements a rock-paper-scissor damage dealing mechanism for its units:
- Archer units are effective towards the knight units
- Knight units are effective towards horsemen units
- Horsemen units are effective towards archer units

A health bar and a mana bar is present on the player's side. The mana bar helps the player keep track of how much mana they have, which will allow the player to utilize spell attacks towards the enemy units. 

## Team Ideas
- Screen shot of the brains storm idea?

## Prototype
- Demo Video:
[![Prototype Demo](images/cover-Images/Prototype-cover-image.PNG)](https://youtu.be/oZFPC-a47eo)

- Early stages of the Game:
  - Player Side:
  
     ![Player Side](/images/cover-Images/prototype-images/player-side.PNG)
     
  - Player Side UI:
  
     ![Player Side UI](/images/cover-Images/prototype-images/player-side-ui.PNG)
     
  - Enemy Side:
  
     ![Enemy Side](/images/cover-Images/prototype-images/enemy-side.PNG)
     
  - Early Win scene:
    ![Early Win Scene](/images/cover-Images/prototype-images/early-win-state.PNG)
     
  - Early Gameplay
  
     ![Early Gameplay](/images/cover-Images/prototype-images/gamplay-prototype.PNG)


## Final Product
- put image with link to a channel that demonstrate the game
- put the link to where the game is currently hosted in

## Team Members

### 1. [Marcos Buccat](https://buccatm.github.io/)
<img src="images/marcosb/gitHub-profile-picture.jpg" width="220" height="220">

- ICS Student, Senior
- Include your individual Brainstoorm Documentation??
- Implemented the Player Side:
  - Player movment
  - Player power ups
  - Player spells
  - Player Side summoning Units
- Implemented all of the player units behaviors
- Implemented the Win & Lose Conditions
- Implemented the Functionality of the Start, Win, and Lose scnene
 
### 2. [Glen Larita](https://glarita.github.io/)
<img src="images/glen/IMG_0183.jpeg" height="220">

- ICS Student, Senior 
- Include your individual Brainstoorm Documentation???
- Responsible for implementing all behavior and functionality on the enemy AI side.
- Implemented: 
   - The enemy movements
   - The enemy's attacks (the fireball and mega fireball).
   - The enemy's spawns and unit scripts
   - The enemy's behavior change as the game is played out
   - Enemy side unit behavior
   - Sounds for all AI units and the enemy
   - Increased spawn rate of units over time
   - implemented animation of characters provided by Jestiny
   - Implemented change in background music when enemy health reaches 50%

### 3. Jestiny Lubas
- URL of your home page, linked in?
- Picture of your Team member
- State your standing and whether you are ICS or ACM
- Include your individual Brainstoorm Documentation???
- Put Stuff that I did here

# Trello Board
- [Team Trello Board](https://trello.com/b/p0tyVYj3/sorcerer-duel)
