---
{"publish":true,"created":"2025-07-16T20:36:18.644+02:00","modified":"2025-05-30T21:52:02.000+02:00","cssclasses":""}
---

Found on docks and ships, these small, pot-bellied monstrosities have bright green hair, orange eyes, and a drunken stare. They are only a foot tall and weigh ten lb, but they are renowned for causing mischief far beyond their tiny size. Their mouths are filled with razor-sharp teeth.

**Drunken Aura.** Rum gremlins make their homes near the docks of seaside towns and some are known to stow away on ships. Each rum gremlin radiates a magic aura causing drunkenness affecting any creatures in the area. Those affected find it difficult to stay on their feet and may become sick from the effect.

**Sailor Victims.** The little horrors often create distracting sounds and small traps. Rum gremlins prey on sailors and dockworkers, working in groups to swarm affected victims who they drag into their lairs below docks or in the holds of ships. They also take great delight in the collateral damage their magic can wreak, frequently sparking accusations and quarrels in places they inhabit before picking off isolated victims.

**Rat Friends.** Rum gremlins are often found with rat swarms or doppelrats they have trained to help protect their nests. The sound of bells drives rum gremlins into a rage and they will go to great lengths to destroy the source of their torment.
[stealth](3-Mechanics/CLI/skills/Stealth)

```statblock
layout: Basic 5e Layout
image: [[Rumgremlin.webp]]
name: Gremlin, Rum
size: Tiny
type: fey
subtype: 
alignment: Chaotic evil
ac: 13
hp: 22
hit_dice: 5d4
speed: 20 ft., climb 10 ft., swim 10 ft.
stats: 
  - !!int "10"
  - !!int "16"
  - !!int "14"
  - !!int "12"
  - !!int "9"
  - !!int "12"
skillsaves:
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
damage_resistances: poison
condition_immunities: [Poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)
senses: "darkvision 120 ft., passive Perception 10"
languages: Common
cr: 1/2
traits:
  - name: Magic Resistance.
    desc: "The gremlin has advantage on saving throws against spells and other magical effects."
  - name: Aura of Drunkenness.
    desc: "A rum gremlin radiates an aura of drunkenness to a radius of 20 feet. Every creature that starts its turn in the aura must make a successful DC 12 Constitution saving throw against poison or be poisoned for one hour. Creatures that have drunk any alcohol during the previous hour have disadvantage on the saving throw. While affected by this poison, a creature falls prone if it tries to move more than half its speed during a turn."
  - name: Innate Spellcasting.
    desc: "The gremlin’s innate spellcasting ability is Charisma (spell save DC 11). It can innately cast spells, requiring no material components"
spells:
  - At will: [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb)
  - 3/day: [hex](/3-Mechanics/CLI/spells/hex-xphb)
actions:
  - name: Multiattack.
    desc: "The goblin makes one claw attack and one bite attack."
  - name: Bite. 
    desc: "Melee Weapon Attack: +5 to hit, range 5 ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  - name: Claws. 
    desc: "Melee Weapon Attack: +5 to hit, range 5 ft., one target. Hit: 6 (1d6 + 3) slashing damage."
```