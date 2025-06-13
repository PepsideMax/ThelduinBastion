---
statblock: inline
statblock-link: "#^statblock"
---
Programmed with knowledge of Strixhaven's extensive lore catalog, cogwork archivists serve as keepers of the university's various libraries. The archivists' towering metal frames are equipped with long, articulated limbs and retractable conservator tools, which they use to organize and preserve documents from throughout Strixhaven's winding history. Many cogwork archivists can be found among the towering shelves of the Biblioplex, simultaneously retrieving scrolls for curious students while keeping a stern eye on any rowdy groups that might disrupt the quiet atmosphere.

```statblock
layout: Basic 5e Layout
image: 3-Mechanics/Bestiary/img/Cogwork Archivist-1.webp
name: Cogwork Archivist
size: Large
type: Construct
subtype: 
alignment: typically Lawful Neutral
ac: 17
hp: 90
hit_dice: 12d10 + 24
speed: 40 ft.
stats: 
  - !!int "18"
  - !!int "10"
  - !!int "15"
  - !!int "17"
  - !!int "11"
  - !!int "6"
skillsaves: 
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+5"
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+6"
condition_immunities: Poison,[Charmed](/3-Mechanics/CLI/conditions.md#Charmed),[Exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),[Frightened](/3-Mechanics/CLI/conditions.md#Frightened),[Petrified](/3-Mechanics/CLI/conditions.md#Petrified),[Poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)
senses: "darkvision 60 ft., passive Perception 12"
languages: All
cr: 4
traits:
  - name: Spellcasting.
    desc: "The archivist casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability:"
spells:
  - At will: [dancing lights](/3-Mechanics/CLI/spells/dancing-lights-xphb), [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb)
  - 2/day: [silence](/3-Mechanics/CLI/spells/silence-xphb)
actions:
  - name: Multiattack.
    desc: "The archivist makes two Grasping Limb attacks."
  - name: Grasping Limb. 
    desc: "_Melee Weapon Attack:_ +6 to hit, reach 15 ft., one target. _Hit:_ 13 (2d8 + 4) bludgeoning damage, and the target is [grappled](Mechanics/CLI/conditions.md#Grappled) (escape DC 14). The archivist can have no more than two targets [grappled](Mechanics/CLI/conditions.md#Grappled) at a time."
```


![[Cogwork Archivist.webp]]