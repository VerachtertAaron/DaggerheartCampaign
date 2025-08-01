---
encounterId: 1a9929693b7a
---


```adversary
source: "daggerheart-adversary"
name: "Acid Burrower"
alias: "Terror of Shay's Crossing"
tier: 1
type: "Solo"
description: "A horse-sized insect with digging claws and acidic blood. Scar has a large gash across one mandible and eye."
motives_and_tactics: "Burrow, drag away, feed, reposition"
difficulty: 14
thresholds: "8/15"
hp: 8
stress: 3
atk: "+3"
attack: "Claws"
range: "Very Close"
damage: "1d12+2 phy"
experience: "Tremor Sense +2"
feats:
- name: "Relentless (3) - Passive"
  text: "The Burrower can be spotlighted up to three times per GM turn. Spend Fear as usual to spotlight them."
- name: "Earth Eruption - Action"
  text: "Mark a Stress to have the Burrower burst out of the ground. All creatures within Very Close range must succeed on an Agility Reaction Roll or be knocked over, making them Vulnerable until they next act."
- name: "Spit Acid - Action"
  text: "Make an attack against all targets in front of the Burrower within Close range. Targets the Burrower succeeds against take 2d6 physical damage and must mark an Armor Slot without receiving its benefits (they can still use armor to reduce the damage). If they can’t mark an Armor Slot, they must mark an additional HP and you gain a Fear."
- name: "Acid Bath - Reaction"
  text: "When the Burrower takes Severe damage, all creatures within Close range are bathed in their acidic blood, taking 1d10 physical damage. This splash covers the ground within Very Close range with blood, and all creatures other than the Burrower who move through it take 1d6 physical damage."
```

```environment
name: Foo
impulses: Bar, Baz
difficulty: 1
potential_adversaries: Bear
feats:
- name: "Something - Passive"
  text: "An explanation"
```