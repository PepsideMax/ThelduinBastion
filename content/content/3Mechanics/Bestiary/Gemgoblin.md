---
{"publish":true,"created":"2025-07-16T20:36:18.642+02:00","modified":"2025-05-31T12:26:22.000+02:00","cssclasses":""}
---

# [[content/3Mechanics/Bestiary/Gemgoblin]]

Gemgoblin are the most secluded and used to darkness among the goblins. Through a combination of luck, cowardice and greed these scavengers have a obsession with gems and all things shiny.

## Goblins

*Wild Tricksters and Troublemakers*

- **Habitat.** Forest, Grassland, Hill, Planar (Acheron), Planar (Feywild), Underdark  
- **Treasure.** Implements, Individual  

Goblins are Feywild embodiments of recklessness and ruin. They delight in wreckage—the louder, the more energetic, and the more convoluted, the better. Goblin raids are often as much opportunities to enjoy setting fires and tormenting livestock as they are parts of more disruptive plots.

Goblins obey those who accomplish the wildest plans. Such leaders might be goblin raid masterminds, bombastic magic-users, or those capable of making the loudest noises. Hobgoblins and forceful humanoids might also command ornery groups of goblins, directing their destructiveness toward banditry, sabotage, or war.

The deity Maglubiyet claims to be the god of goblins, hobgoblins, and bugbears, and on the Infinite Battlefield of Acheron, the deity commands innumerable goblinoid legions. In ages long past, Maglubiyet witnessed the destructive propensity of goblinoids and relocated a population of them from the Feywild to his realm on the Outer Planes. Since then, hordes of these more martial-minded goblins have flourished, with some finding their ways to Material Plane worlds. These vicious invaders seek to sow ruin in preparation for their god's conquest.

> [!quote] A quote from Approximate translation from Goblin to Common: "Hey, rube!"  
> 
> Bree-yark!


```statblock
"name": "Gemgoblin"
"size": "Small"
"type": "fey"
"subtype": "goblinoid"
"alignment": "Chaotic Neutral"
"ac": !!int "17"
"hp": !!int "21"
"hit_dice": "6d6"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "10"
  - !!int "10"
  - !!int "8"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"senses": "darkvision 120 ft., passive Perception 9"
"languages": "Common, Goblin"
"cr": "1"
"actions":
  - "desc": "The goblin makes two attacks, using Scimitar or Shortbow in any combination."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +4, reach 5 ft. Hit: 5 (1d6 + 2) Slashing damage,\
      \ plus 2 (d4) Slashing damage if the attack roll had [Advantage](/3-Mechanics/CLI/variant-rules/advantage-xphb.md)."
    "name": "Scimitar"
  - "desc": "Ranged Attack Roll: +4, range 80/320 ft. Hit: 5 (1d6 + 2) Piercing\
      \ damage, plus 2 (d4) Piercing damage if the attack roll had [Advantage](/3-Mechanics/CLI/variant-rules/advantage-xphb.md)."
    "name": "Shortbow"
"bonus_actions":
  - "desc": "The goblin takes the Disengage or Hide action."
    "name": "Nimble Escape"
"reactions":
  - "desc": "Trigger: A creature the goblin can see makes an attack roll against it.\
      \ _Response:_ The goblin chooses a Small or Medium ally within 5 feet of itself.\
      \ The goblin and that ally swap places, and the ally becomes the target of the\
      \ attack instead."
    "name": "Redirect Attack"
"source":
  - "XMM"
"image": "[[Gemgoblin.webp]]"
```

