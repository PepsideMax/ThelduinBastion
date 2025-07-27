---
{"publish":true,"aliases":"Psurlon","created":"2025-06-13T17:11:39.884+02:00","modified":"2025-07-18T17:53:34.915+02:00","cssclasses":"json5e-monster"}
---

# [[3Mechanics/Bestiary/Psurlon]]
Psurlons are malevolent, wormlike creatures that live on the Astral Plane. A fully grown specimen is 7 feet long. They have legs that end in hooves and arms that end in hands with three long fingers. A psurlon's eyeless head resembles that of an earthworm, capped by a maw ringed with teeth. [[3Mechanics/Bestiary/Psurlon]]s adorn themselves in richly colored robes and rarely wear armor or carry weapons.

[[3Mechanics/Bestiary/Psurlon]]s live for thousands of years because they spend most of their time in the Deep Astral. Every hundred years or so, [[3Mechanics/Bestiary/Psurlon]]s leave their astral strongholds, invade Wildspace systems, and indulge in a seven-year-long ceremony called the Feast of Worlds, during which they consume as many sentient life-forms as they can before returning to the Astral Plane. [[3Mechanics/Bestiary/Psurlon]]s prefer the flesh of humans and halflings but don't mind feasting on other folk. They use their spellcasting abilities to infiltrate the settlements of their intended victims.

On the Material Plane, [[3Mechanics/Bestiary/Psurlon]]s have been known to work with mind flayers. Together, they collect victims to feed on; the illithids devour the victims' brains while the psurlons consume the rest of the prey. Githyanki despise psurlons because of this alliance and attack psurlon strongholds in the Deep Astral wherever they are found.

When a psurlon dies, other psurlons store the corpse in a safe place. As the corpse decays, the psurlons lay one or more eggs inside it. These eggs hatch 24 hours later, each one producing a Tiny worm. For the next seven days, the worms feed on the corpse and on each other until only one remains. This worm crawls out of the putrescent remains of its dead host as an adult psurlon.


```statblock
layout: Basic 5e Layout
image: [[Psurlon.webp]]
name: Psurlon
size: Medium
type: Aberration
subtype: 
alignment: Lawful Evil
ac: 15 [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb)
hp: 45
hit_dice: 7d8 + 14
speed: 30 ft.
stats: 
  - !!int "14"
  - !!int "14"
  - !!int "14"
  - !!int "17"
  - !!int "11"
  - !!int "7"
senses: "blindsight 120 ft.([blind](/3-Mechanics/CLI/conditions.md#blinded) beyond this radius), passive Perception 10"
languages: Deep Speech, telepathy 120 ft.
cr: 2
traits:
  - name: Aberrant Mind.
    desc: "Magic can't read the psurlon's thoughts or put the psurlon to sleep"
  - name: Spellcasting (Psionics).
    desc: "The psurlon casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 13)"
actions:
  - name: Multiattack.
    desc: "The psurlon makes one Bite attack and two Claw attacks."
  - name: Bite. 
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 6 (1d8 + 2) piercing damage"
  - name: Claws. 
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4 + 2) slashing damage"
  - name: Psychic Crush.
    desc: The psurlon targets one creature it can see within 120 feet of itself. The target must make a DC 13 Wisdom saving throw, taking 14 (2d10 + 3) psychic damage on a failed save, or half as much damage on a successful one.
spells: 
  - 2/day each: [disguise self](3-Mechanics/CLI/spells/disguise-self-xphb), [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb) (self only)
  - 1/day: [suggestion](3-Mechanics/CLI/spells/suggestion-xphb)
```

