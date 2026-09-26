---
tags:
  - One_Shot
  - Combat
marker:
Status: Played
Cannon: true
---
# Party
---
---

| Class   | Race     | Lvl | Backgroud                                                        |
| ------- | -------- | --- | ---------------------------------------------------------------- |
| Ranger  | Teafling | 4   | Enemy of [Micixhua - Istiyouilia](Micixhua%20-%20Istiyouilia.md) |
| Warlock | Half-Eld | 4   | Has the dagger of the blood eater                                |
| Cleric  | Hafling  | 4   | Not relevant                                                     |
| Fighter | Human    | 4   | Soldier of Arangtor, no feeling                                  |

# Flowchart of game
---
---
```mermaid
flowchart LR
	ev1{{Arriving to 'snow dessert'}}
	ev2{{Travers trail bar}}
	ev3{{Fight Micixhua}}
	
	ev1 e1@--> ev2 --> ev3
	
	e1@{ animation: fast }
	
	style ev1 fill:#be1
```
# Introduction
---
---
The snowy desert can be a unforgiving one and many have fallen to the consequences of them. Missing people have been reported from forging runs to the snowy dessert and the rumors of "bells". One must investigate the area of this reports, you'll try to found your way though the peerless weather of the snow, investigate the clues of the missing people and even maybe discover the core reason of the disappearance which may not be what other expect

## Setting
---
The party will meet at the back of a caravan with an old farmer from the city of [Brogfrior](Brogfrior.md) steering it, the city where they left. All characters, be it by choice, coincidence or fate, accepted the task of investigating the missing people that have been reported to happen on forging runs to the ice dessert.
## NPCs
---
### Adaidh
**Race:** Human (changeling)
**Profession:** Farmer (Watcher for [The Eye of Punishment](The%20Eye%20of%20Punishment.md))
**Physical traits:** Old human with a hunching posture but firm grip and arm posture when grabbing the leashes. His eyes almost seam to be hidden behind his lush eyebrows and a face with many wrinkles but still with a face one could recognize if they knew him in a younger age.
#### Information (Human)
- Legend of the [The Snow with Eyes](The%20Snow%20with%20Eyes.md)
- Cities of Torania
- Trading route of [Brogfrior](Brogfrior.md)
- Additional reports of bell noises when people go missing
- Basic knowledge of [Brogfrior](Brogfrior.md)

## Activities
- Roleplay
- Knowing the world
- Context if needed

# Development
---
---
The way the campaign will move forward is by filling a "trail meter" that will indicate when they will find the bells in the snow. When finding the bells the party must complete a small puzzle to find the final layer.
## Tiles
---
### Tile 1
**Snow hill**
- A peculiar flower can be found under the snow. One that seams like it's made by ice petals 
- **(Investigation check 12)** One will notice that there is part of a stone that has less snow than it should. Someone was supporting his back on this rock
	- **Pass:** +1 trail
	- **Fail:** +0 trail
### Tile 2
**Powder snow**
 - (**Perception 10**) There is some deep snow that is difficult to tell the difference between solid snow and this
	 - **Pass:** +0 trail
	 - **Fail:** -1 trail
### Tile 3
**Locket**
- (**Perception 12**) The reflection of a silver locket can be seen buried on the snow. Inside it there is a picture of small girls smiling and hugging each other with one arm.
	- **Pass:** +3 trail
	- **Fail:** +0 trail
### Tile 4
**Ancient tablet**
### Tile 5
**Snow Creatures | Min. 4 trail**
- Snow will seam like it'll start standing up, as if there was conscience in the floor
	- +2 trail per creature
- 3 ogre zombi
- ogre zombi HP 85
``` statblock
monster: Ogre Zombie
```

# Final Boss
---
---
## Setting
The oldest or the closes to death will hear the bell closer and then one of the party members (any) will see a dim light on the snow storm. When followed they will arrive to a snow dune to steep to climb and then behind them a slim looking snowman with bells in one arm and a dim lantern in another. the [Micixhua - Istiyouilia](Micixhua%20-%20Istiyouilia.md) has appeared and the first to see it must make a DC 12 Wisdom saving throw or be Frightened.
## Adult Oblex or [Micixhua - Istiyouilia](Micixhua%20-%20Istiyouilia.md) (For this oneshot)
Using the Adult Oblex as it's not in his full power, it spread to attack more mortals (a mistake it'll learn to correct)
``` statblock
ac: 14
hp: 75
speed: 20 ft
stats: [8,19,16,19,12,15]
saves:  
- Int: +7
- Cha: +5
skillsaves:  
- Deception: +5
- Perception: +4
- History: +7
condition_immunities: blinded, charmed, deafened, exhaustion, prone
senses: blindsight 60 ft. (blind beyond this radius), passive Perception 14
languages: Common plus two more languages  
cr: 5
traits:  
- [Amorphous., The oblex can move through a space as narrow as 1 inch wide without squeezing.]
- [Aversion to Fire., If the oblex takes fire damage, it has disadvantage on attack rolls and ability checks until the end of its next turn.]
- [Unusual Nature., The oblex doesn't require sleep.]
actions:  
- [Multiattack., The oblex makes two Pseudopod attacks, and it uses Eat Memories.]
- [Pseudopod., Melee Weapon Attack: +7 to hit, reach 5 ft., ine target. Hit: 11 (2d6 + 4) bludgeoning damage plus 7 (2d6) psychic damage.]
- [Eat Feelings., The oblex targets one creature it can see within 5 feet of it. The target must succeed on a DC 15 Wisdom saving throw or take 18 (4d8) psychc damage and become emotional drained until it benefits from the greater restoration or heal spell. Constructs, Oozes, Plants, and Undead succeed on the save automatically. While emotional drained, the target must roll a d4 and subtract the number rolled from its ability checks and attack rolls. Each time the target is emotional drained beyond the first, the die size increases by one, the d4 becomes a d6, the d6 becomes a d8 until the die become a d20, at wich point the target becomes unconscious for 1 hour. The effect then ends. The oblex learns all the languages a memory-drained target knows and gains all its skill proficiencies]
```
& Spawn Oblex
``` statblock
monster: Oblex Spawn
```

# Depricated (did not happen)

### Puzzle Tile
**Balance rock platform**
When walking they will feel like a big lose stone moved underneath them, then movement as if they would start spinning around. They are now on a loose rock on top of a pillar that has luckily landed in a way that it "stabilized" as a ball gimble.
#### Timeline
- **Immediate:** Dexterity saving throw
	- **Pass:** Choose where to go
	- **Fail:** Stay where you are
The platform will spin constantly but in a slow pace, if they balance the platform correctly they will have a chance to jump of to the other side
- **Fail to balance:** The party will fall, receive 2d6 and Dexterity saving throw to dodge the falling rocks. The party will notice that they landed in Tile 1

When they pass to the other side one of the party members will hear a faint but clear sound of a bell ringing