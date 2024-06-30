---
title: Lonely Tower
image: images/header.jpg
group: CM
bosses: 2
difficulties:
  - level: 100
    ar: 150
potions: []
hasCM: false
cycle: Day
hidden: true
layout: src/layouts/Fractal.astro
date: "2024-06-17T20:16:33.035Z "
consumables: []
record: {}
long_description: Immediately following the foundation of the Astral Ward,
  Eparch finally returned to Tyria to strike back against Isgarren's
  "betrayal"—this time with a full entourage. Help Isgarren, Mabon, and Dagda
  navigate the crumbling halls of the Wizard's Tower and push the Kryptis back
  to where they came from.
api: 26231
description: Mabon, Isgarren. Pick a god and thank her for your survival...
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

**Reward:** <Item id="101867"/>
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

## Brothers <Item id="9443" disableText size="medium"/>
Once you have completed the Astral Purifier event, you can _/gg_ to respawn in the starting room. Leave the starting room, once again taking the _Mistlock Singularity_ if availible. However, this time turn left and move down the corridor. This time as well as Cerus's Despair attack (the falling red orbs) from before, you will also have to deal with Deimos's Grasping Hands, that apply <Condition name="Poisoned"/>, <Condition name="Torment"/>, and <Condition name="Crippled"/>. At the end of the corridor you will come to a single Astral Purifier node, which requires you to play the same minigame as before. Repairing this node will allow access to the room with the brothers Cerus and Deimos standing in. Both bosses will fixate and move towards the closest player to them, with the players gaining the <Label>Cerus's Focus</Label> and <Label>Deimos's Focus</Label> effects respectively. When the brothers are close together they will gain the effect <Label>Brothers United</Label> leading their attacks to deal more damage.

<Grid>
<GridItem>
<Achievement title="Brothers, Together">
Defeat Cerus and Deimos within 5 seconds of each other in the Lonely Tower fractal. 
</Achievement>
</GridItem>
<GridItem>
<Information>
Providing you can deal with the mechanics, the easiest strategy to kill the brothers quickly (and get the achievement) is to pull them together. By pulling both brothers together they again the <Label>Brothers United</Label> effect, which increases their outgoing damage.
</Information>
</GridItem>
</Grid>

### Cerus's Mechanics
<Grid>
<GridItem sm="4">
#### Despair
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Cerus will spawn an expanding AoE under players. When the AoE fills a red orb will drop from above. Standing in the red AoE left behind will apply <Effect name="Agony"/> and 5 stacks of <Condition name="Torment"/>.
</GridItem>
<GridItem sm="4">
#### Cry of Rage
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Cerus will repeatedly pummel the ground as a large expanding AoE fills the arena. When the AoE fills it will deal damage to all players in it. Additionally any player hit by the attack will grant a stack of the <Label>Empowered</Label> effect to Cerus, which increases his damage by 5% per stack.
</GridItem>
<GridItem sm="4">
#### Malicious Intent
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Cerus will tether himself to a player and draw out a Malicious Shadow, that will slowly walk towards Cerus. Once it reaches Cerus's hitbox, the Shadow will be consumed giving cerus 5 stacks of <Label>Empowered</Label>.
</GridItem>
</Grid>

### Deimos's Mechanics
<Grid>
<GridItem sm="4">
#### Grasping Hnads
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Grasping Hands will spawn under the player furthest away from Deimos. Standing in them applies apply <Condition name="Poisoned"/>, <Condition name="Torment"/>, and <Condition name="Crippled"/>. Any hands close to Deimos will get pulled in and consumed, giving deimos stacks of <Label>Devour</Label> for each hand consumed. <Label>Devour</Label> increases Deimos's outgoing damage by 2% per stack.
</GridItem>
<GridItem sm="4">
#### Rapid Decay
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Deimos will stop and swing his maces for 5 seconds, after the 5 seconds the closest player to Deimos, without <Label>Cerus's Focus</Label> will have an orange AoE spawned under them. Shrotly after the field becomes black and anyone who steps in it will expand the field and also be dealt heavy damage.
</GridItem>
<GridItem sm="4">
#### Annihilate
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Deimos will slam the ground creating a large AoE on the ground. This will then start a shockwave moving from the front to the back, launching anyone hit backwards.
</GridItem>
</Grid>

## Eparch <Item id="9443" disableText size="medium"/> <Item id="24664" disableText size="medium"/>
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

### Globules of Emotion

As Eparch carries out each attack, he will spawn Globules of Emotion. These can be collected by players giving different effects, some positive and some negative. Each attack has a corresponding emotion that it will spawn which can be seen in the table below. If you have stacks of a Globule of Emotion and go to collect a different type, each new Globule will remove a stack of the previous effect until you start to gain stacks of the new effect.

| Globule of Emotion (Colour)          | Boss Mechanic     | Player Attunement                                                                          | Boss Empowerment                                               |
|-----------------------|--------------|----------------------------------------------------------------------------------------|-----------------------------------------------------------|
| **Despair (Blue)**    | Rain of Despair | -3% Incoming Strike Damage, -3% Outgoing Strike Damage                                 | -3% Incoming Strike Damage, -3% Incoming Condition Damage |
| **Envy (Green)**      | Wave of Envy  | +5% Boon Duration, +5% Condition Duration, +5% Condition Damage, -50% Incoming Condition Damage | Boss attacks strip Boons                                  |
| **Gluttony (Orange)** | Spin Attack  | ~108.5 lifesteal, 100 Damage taken per second               | Heals boss                                                |
| **Malice (Purple)**   | Spike of Malice | +4% increased defiance break                                                           | Boss attacks inflict additional Conditions                |
| **Rage (Red)**        | Enraged Smash  | +5% Outgoing Strike Damage, +5% Incoming Strike Damage                                 | +5% Outgoing Strike Damage, +5% Outgoing Condition Damage |
| **Regret (Yellow)**   | Spawns Adds         | +2% Skill Recharge, 50 Damage taken on activation                                                  | 20 damage reflect                           |
| **Consumed**   | Consume (CC)         | -3% Health, -3% Outgoing Strike Damage, -3% Outgoing Condition Damage |                           |

With this in mind, it makes sense for the following roles to prioritise the following Globules of Emotion to maximise party damage:
- Healer / Lowest damage build in a no-heal composition - Despair
- Power DPS - Rage
- Condi DPS - Envy

### Consume
<Grid>
<GridItem sm="8">
During his rotation, Eparch will gain a defiance bar, then pull in and consume all Globules of Emotion left on the ground and gain their respective effects as per the table above. By breaking Eparchs Defiance Bar, you will remove some stacks of empowerment. It is important to make sure you have collected all Malice and Envy Globules before the CC phase to make the fight considerably easier.

Additionally, during this phase, Eparch will target one player and apply the <Label>Consume</Label> effect. This will start to remove any Emotion stacks the player has untill they reach zero or the defiance bar is broken. At zero stacks, Eparch will apply stacks of the <Label>Consumed</Label> effect, with each stat lowering the players attributes. To reduce the stacks and remove this effect, the player will have to collect Globules of Emotion.
</GridItem>
<GridItem sm="4">
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
</GridItem>
</Grid> 

### Eparchs Attacks
<Grid>
<GridItem sm="4">
#### Rain of Despair
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
<GridItem sm="4">
#### Enraged Smash
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Spawns Rage Fissure lines on ground
</GridItem>
<GridItem sm="4">
#### Wave of Envy
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Stand inside hitbox
</GridItem>
<GridItem sm="4">
#### Inhale
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
<GridItem sm="4">
#### Spike of Malice
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
<GridItem sm="4">
#### Spawn Adds
<GifPlayer sourceId="snowblind-throw-firewood" caption="Throw firewood into the fire" />
Something
</GridItem>
</Grid>

<Divider text="Challenge Mode"/>
## Eparch CM <Item id="9443" disableText size="medium"/> <Item id="24664" disableText size="medium"/>
<Grid>
<GridItem>
<Achievement title="Secrets of the Tower ">
Accept the harbinger's challenge and defeat the final boss in the Lonely Tower fractal.
</Achievement>
</GridItem>
<GridItem>
<Achievement title="Wavering Ward">
Accept the harbinger's challenge and complete the Lonely Tower fractal without anyone in your group being defeated.

**Title:** Kryptis Exorcist
</Achievement>
</GridItem>
</Grid>
With Challenege mode enabled, the majority of the fractal plays out the same as the T4 version. The main difference is the Eparch encounter which gains the following changes:
- Split phases at 65% and 35%
- When successfully breaking Eparchs defiance bar, Eparch does not lose any aqquired Globule of Emotion Stacks
- Collecting Globules of Emotion will not reduce <Effect name="Consumed"/> stacks on players

The rest of the encounter is exactly the same as the T4 mode.

### Split Phase
When reaching a split phase, Eparch will leave the Arena and spawn 2 rifts in the 65% phase, and 3 rifts in the 35% phase. Each rift will spawn a Champion incarnation of Judgement, or a Champion Incarnation of Cruelty, along with some trash mobs. To close the rift, its associated Champion must be killed, to allow players to close the rift by channeling in a white AoE that spawns. Meanwhile the mobs will be drawn towards Eparch, who is floating above the arena. When the adds get close, they tether to Eparch giving him stacks of Globules of Emotion.

<Warning>
The split phases are currently very poorly balanced, making it hard to complete without Eparch gaining stacks of each emotion. To make the subsequent phases easier, it is best to stack Gluttony Globules on one player who can then lifesteal each rift to death in the splits, closing them before the trash mobs can reach Eparch. 
</Warning>
