---
hasCM: false
cycle: Day
hidden: true
layout: src/layouts/Fractal.astro
date: "2024-05-23T21:33:53.202Z "
title: Lonely Tower
difficulties:
  - level: 100
    ar: 150
consumables: []
record: {}
long_description: Immediately following the foundation of the Astral Ward,
  Eparch finally returned to Tyria to strike back against Isgarren's
  "betrayal"—this time with a full entourage. Help Isgarren, Mabon, and Dagda
  navigate the crumbling halls of the Wizard's Tower and push the Kryptis back
  to where they came from.
image: images/lonelytowerheader.jpg
api: 26231
bosses: 2
description: Mabon, Isgarren. Pick a god and thank her for your survival...
group: T4
sigils: []
---

Immediately following the foundation of the Astral Ward, Eparch finally returned to Tyria to strike back against Isgarren's "betrayal"—this time with a full entourage. Help Isgarren, Mabon, and Dagda navigate the crumbling halls of the Wizard's Tower and push the Kryptis back to where they came from.  
 
<Divider text="Normal Mode"/>
<Grid>
<GridItem>
<Achievement title="Wizard's Tower Is Ours, Eparch ">
Complete the Lonely Tower fractal on any tier. 
</Achievement>
</GridItem>
<GridItem>
<Achievement title="Wayfind Yourself Out ">
Complete the Lonely Tower fractal on the Master tier.
</Achievement>
</GridItem>
<GridItem>
<Achievement title="Lonely Tower Fractal">
Complete all the achievements associated with the Lonely Tower fractal.

**Reward:** <Item name="Endless Midnight King Combat Tonic"/> 
</Achievement>
</GridItem>
</Grid>

Upon entering the fractal take the _Mistlock Singularity_ and head out the starting room and follow the corridor to your right. Whilst moving down the corridor avoid Cerus's Despair attack (the falling red orbs, leaving AoEs on the ground), standing in this attack will apply <Effect name="Agony"/> and 5 stacks of <Condition name="Torment"/>. At the end of the corridor you will see Cerus standing in the Astral Purifier room.

## Astral Purifiers
<Grid>
<GridItem>
Inside the room, you will find four Astral Purifier Nodes that must be repaired. Interacting with a node will give you the effect <Label>Time Running Out</Label>. It will turn your weapon skills into a Simon Says styled minigame, where you will have to press a highlighted skill 10 times, before the 30 second timer runs out. Pressing the wrong skill will knock you back and cancel the minigame, requiring you to start again.

During the minigame, three Avatars of Spite will spawn and fixate on the player reapiring the node. When they get close they will apply <Condition name="Poisoned"/> and explode knocking the player back, cancelling the minigame. These can either be dealt with by the rest of the party, using crowd control and killing them, or alternatively the player on the node can b e given or use their own source of <Boon name="Stability"/> to negate the knockback, allowing them to continue the game. The <Boon name="Stability"/> method allows multiple nodes to be completed at the same time.  
</GridItem>
<GridItem>
<GifPlayer sourceId="snowblind-throw-firewood" caption="Soloing an Astral Purifier Node with Stability " />
</GridItem>
</Grid>

## Brothers
Once you have completed the Astral Purifier event, you can _/gg_ to respawn in the starting room. Leave the starting room, once again taking the _Mistlock Singularity_ if availible. However, this time turn left and move down the corridor. This time as well as Cerus's Despair attack (the falling red orbs) from before, you will also have to deal with Deimos's Grasping Hands, that apply <Condition name="Poisoned"/>, <Condition name="Torment"/>, and <Condition name="Crippled"/>. At the end of the corridor you will come to a single Astral Purifier node, which requires you to play the same minigame as before. Repairing this node will allow access to the room with the brothers Cerus and Deimos standing in.

<Grid>
<GridItem>
<Achievement title="Brothers, Together">
Defeat Cerus and Deimos within 5 seconds of each other in the Lonely Tower fractal. 
</Achievement>
</GridItem>
<GridItem>
<Information>
Providing you can deal with the mechanics, the easiest strategy to kill the brothers quickly (and get the achievement) is to pull them together.
</Information>
</GridItem>
</Grid>

### Cerus
Something

### Deimos
Something

## Eparch
Once you have defeated the brothers, take the portal to the final boss. Before fighting Eparch, you will have to kill some trash mobs. Once you have dealt with them you can _/gg_ again, to reset cooldowns and prestack boons while Eparch spawns. When ready aproach the white circle on the ground to enter the arena.

<Grid>
<GridItem>
<Achievement title="Emotionless ">
Defeat Eparch in the Lonely Tower fractal without allowing him to reach 20 stacks of any emotional attunement.
</Achievement>
</GridItem>
<GridItem>
<Achievement title="Fissure Walker ">
Defeat Eparch in the Lonely Tower fractal without taking damage from his rage fissures.
</Achievement>
</GridItem>
</Grid>

<Information>
There is no status reset upon starting a boss encounter in this fractal, so it is advisable to take advantage of the _Mistlock Singularity_ to prestack boons, since the fight mechanics require you to move and split shortly after entering combat.
</Information>
Something 

### Orbs

As Eparch carries out each attack, he will spawn Globules of Emotion. These can be collected by players giving different effects, some positive and some negative. Each attack has a corresponding emotion that it will spawn which can be seen in the table below. If you have stacks of a Globule of Emotion and go to collect a different type, each new Globule will remove a stack of the previous effect until you start to gain stacks of the new effect.

| Globule of Emotion (Colour)          | Boss Mechanic     | Player Effect                                                                          | Boss Effect                                               |
|-----------------------|--------------|----------------------------------------------------------------------------------------|-----------------------------------------------------------|
| **Despair (Blue)**    | Puddle Spawn | -3% Incoming Strike Damage, -3% Outgoing Strike Damage                                 | -3% Incoming Strike Damage, -3% Incoming Condition Damage |
| **Envy (Green)**      | Line Attack  | +5% Boon Duration, +5% Condition Duration, -50% Incoming Condition Damage, +5% Condition Damage | Boss attacks strip Boons                                  |
| **Gluttony (Orange)** | Spin Attack  | ~108.5 lifesteal on ~3s cd (cd unconfirmed), 100 Damage taken per second               | Heals boss                                                |
| **Malice (Purple)**   | Chasing AoEs | +4% increased defiance break                                                           | Boss attacks inflict additional Conditions                |
| **Rage (Red)**        | Wave Attack  | +5% Outgoing Strike Damage, +5% Incoming Strike Damage                                 | +5% Outgoing Strike Damage, +5% Outgoing Condition Damage |
| **Regret (Yellow)**   | Adds         | Grants a Gluttony stack upon collection                                                  | 20 (unconfirmed) damage reflect                           |

With this in mind, it makes sense for the following roles to prioritise the following Globules of Emotion to maximise party damage:
- Healer / Lowest damage build in a no-heal composition - Despair
- Power DPS - Rage
- Condi DPS - Envy

### CC
At the start of Eparchs CC phase, he will pull in and consume all Globules of Emotion left on the ground and gain their respective effects as per the table above. By breaking Eparchs Defiance Bar, you will remove some stacks of each effect. It is important to make sure you have collected all Malice and Envy Globules before the CC phase to make the fight considerably easier.

Additionally, during this phase, Eparch will target one player and apply the <Label>Consume</Label> effect. This will start to remove any Emotion stacks the player has untill they reach zero or the defiance bar is broken. At zero stacks, Eparch will apply stacks of the <Label>Consumed</Label> effect, with each stat lowering the players attributes. To reduce the stacks and remove this effect, the player will have to collect Globules of Emotion.

### Boss Mechanics
<Grid>
<GridItem sm="4">
#### Puddle Spawn
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
<GridItem sm="4">
#### Wave Attack
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
<GridItem sm="4">
#### Line Attack
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
<GridItem sm="4">
#### Spin Attack
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
<GridItem sm="4">
#### Chasing AoEs
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
<GridItem sm="4">
#### Adds
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
</Grid>