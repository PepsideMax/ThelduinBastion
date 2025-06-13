---
statblock: inline
statblock-link: "#^statblock"
---

This mole-like creature is the size of a large dog, with a thick,
barrel-shaped body as heavy as a full-grown dwarf. A ring of
tentacles sprouts above a mouth dominated by spade-like incisors.
It bas no visible ears and only tiny, cataract-filled eyes, but
somehow it senses its environment nonetheless.

**Domesticated By Dwarves.** Mountain dwarves have
domesticated many subterranean creatures, among them a breed
of giant talpidae commonly called dogmoles. Energetic and
obedient, dogmoles pull ore-trolleys through mines, sniff out
toxic gases and polluted waters, and help dig out trapped miners.

**Sense Cave-ins.** Dogmoles are renowned for their ability to
detect imminent cave-ins and burrowing monsters, making
them welcome companions in the depths. Outside the mines,
dogmolcs serve as pack animals, guard beasts, and bloodhounds.

**Derro Cruelty.** Derro also use dogmoles, but such
unfortunate creatures are scarred and brutalized, barely
controllable even by their handlers.

```statblock
layout: Basic 5e Layout
image: [[Dogmole.webp]]
name: Dogmole
size: Medium
type: Beast
subtype: 
alignment: Neutral
ac: 14
hp: 71
hit_dice: 11d8
speed: 30 ft., burrow 10 ft., swim 10 ft.
stats: 
  - !!int "14"
  - !!int "17"
  - !!int "15"
  - !!int "2"
  - !!int "12"
  - !!int "10"
senses: "blindsight 30 ft., passive Perception 11"
languages: 
cr: 1
traits:
  - name: Burrow.
    desc: "Dogmoles can burrow into solid rock at half speed, they can move through softer material like soil or loose rubble at 10 ft., leaving a usable tunnel 5 feet in diameter"
  - name: Wormkiller Rage.
    desc: "Wild dogmole packs are famed for their battles against monsters in the dark caverns of the world. If the dogmole draws blood against vermin, a purple worm, or other underground invertebrates, it gains a +4 boost to its Strength and Constitution. but suffers a -2 penalty to its AC. The wormkiller rage lasts for 3 rounds. It cannot end the rage voluntarily while the creatures that sent it into a rage still lives."
actions:
  - name: Multiattack.
    desc: "The dogmole makes one claw attack and one bite attack."
  - name: Bite. 
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) piercing damage."
  - name: Claws. 
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 12 (3d6 + 2) slashing damage."
```

