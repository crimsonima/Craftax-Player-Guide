# Combat

[Home](../README.md) · [Controls](controls.md) · [Crafting](crafting.md) · [Help](troubleshooting.md)

| Attack | Key | Needs |
|---|---|---|
| Melee | Space | An adjacent enemy you face; uses your sword (or fists) |
| Arrow | I | A bow and 1 arrow per shot |
| Fireball / iceball | G / H | The learned spell and 2 mana |

Damage below is per hit, before the enemy's resistances.

## Melee damage

| Weapon | Str 1 | Str 2 | Str 3 | Str 4 | Str 5 |
|---|---:|---:|---:|---:|---:|
| Fists | 1 | 1.25 | 1.5 | 1.75 | 2 |
| Wood sword | 2 | 2.5 | 3 | 3.5 | 4 |
| Stone sword | 3 | 3.75 | 4.5 | 5.25 | 6 |
| Iron sword | 5 | 6.25 | 7.5 | 8.75 | 10 |
| Diamond sword | 8 | 10 | 12 | 14 | 16 |

Only strength matters here. An enchanted sword adds separate fire or ice damage: see [sword enchantment bonus](upgrades.md#sword-enchantment-bonus).

## Bow damage

| Dexterity | 1 | 2 | 3 | 4 | 5 |
|---|---:|---:|---:|---:|---:|
| Physical | 5 | 6 | 7 | 8 | 9 |
| Extra fire/ice if the bow is enchanted | 2.5 | 3 | 3.5 | 4 | 4.5 |

## Spells

| Intelligence | 1 | 2 | 3 | 4 | 5 |
|---|---:|---:|---:|---:|---:|
| Fireball or iceball damage | 3 | 4.5 | 6 | 7.5 | 9 |

Spells always cost 2 mana. Reading a book learns a spell; intelligence raises its damage.

## Enemy resistances

Physical, fire and ice damage are reduced separately by the enemy's resistance to each, then added up.

| Enemy | Physical | Fire | Ice |
|---|---:|---:|---:|
| Most enemies and all animals | 0% | 0% | 0% |
| Knights, archers (Vault) | 50% | 0% | 0% |
| Trolls (Troll Mines) | 20% | 0% | 0% |
| Pigmen, fire elementals (Fire Realm) | 90% | 100% | 0% |
| Frost trolls, ice elementals (Ice Realm) | 90% | 0% | 100% |

Example: against a fire elemental, a diamond sword at strength 3 deals 12 × 10% = **1.2**. Ice-enchanted, it adds 4.2 ice damage, for **5.4** in total. An iceball at intelligence 2 deals **4.5**; a fireball deals **0**.

The Necromancer is different: each hit while it's vulnerable counts as one step of progress, whatever your weapon.

## Armour

| Per armour piece | Protection |
|---|---|
| Iron | 10% physical |
| Diamond | 20% physical |
| Fire / ice enchantment | 20% fire / ice |

Protection adds up over the four pieces; for example, a full diamond set gives 80% physical. [Armour costs](crafting.md#armour)

---

[Back to home](../README.md)
