# Adventurers

This document defines the current prototype rules for adventurers in Shopkeeper Showdown.

Adventurers are the player’s way of interacting with the Adventure board. They explore Mystery Tokens, resolve Adventure Cards, fight Monsters, complete Quests, avoid Traps, and uncover Discoveries.

These rules are for Version 0.1.2 and are intentionally simple for the first playable prototype.

---

## 1. Purpose

Adventurers should give players a way to interact with the Adventure Phase.

They determine how strong a player is when resolving Adventure Cards and how likely they are to reach higher reward thresholds.

Adventurers currently affect:

* Adventure rolls
* Monster combat
* Quest success
* Trap avoidance
* Discovery reward quality

In future versions, adventurers may also have unique skills, gear, and class-specific abilities.

---

## 2. Prototype Adventurer Rules

In Version 0.1.2, all adventurers use the same basic rules.

Each adventurer starts with:

* 1d6 adventurer dice
* +1 to Adventure rolls
* 0 training
* No unique skills

This keeps the first prototype focused on testing the core Adventure, Town, and Selling loop before adding full adventurer asymmetry.

---

## 3. Adventure Rolls

When resolving an Adventure Card, roll the adventurer’s dice and add their flat roll bonus.

The starting Adventure roll is:

```text
1d6 + 1
```

The result is used differently depending on the Adventure Card type.

| Adventure Card Type | How the Roll Is Used                                         |
| ------------------- | ------------------------------------------------------------ |
| Monster             | Roll result is used to deal damage.                          |
| Quest               | Roll result is compared against success thresholds.          |
| Trap                | Roll result is compared against avoidance/disarm thresholds. |
| Discovery           | Roll result is compared against reward thresholds.           |

---

## 4. Training

Training improves the number of dice an adventurer rolls.

Training does not increase the flat +1 roll bonus.

| Training Level | Adventure Roll |
| -------------: | -------------- |
|   0–1 Training | 1d6 + 1        |
|   2–3 Training | 2d6 + 1        |
|    4+ Training | 3d6 + 1        |

Training should be gained through Town actions, especially the Training Grounds.

---

## 5. Training Design Intent

Training should make adventurers stronger quickly enough to matter within a 3-round game.

The current prototype has only 3 rounds, so training needs to produce visible improvements without requiring too many actions.

The intended progression is:

```text
Early game: 1d6 + 1
Mid game: 2d6 + 1
Late game / trained adventurer: 3d6 + 1
```

This should allow players to start by reaching lower Adventure thresholds, then build towards higher thresholds and faster Monster defeats.

---

## 6. Flat Roll Bonus

All adventurers currently start with a flat **+1** bonus to Adventure rolls.

This bonus is added after rolling dice.

Example:

```text
A player with 1d6 + 1 rolls a 4.

Final result = 5.
```

The flat +1 bonus does not improve through training.

The current design split is:

```text
Training improves dice.
Gear improves the flat bonus.
```

Gear rules are not fully defined in Version 0.1.2, but future equipment may increase the adventurer’s flat roll bonus.

---

## 7. Monster Combat

When fighting a Monster, the adventurer’s roll is used as damage.

To resolve a Monster combat roll:

1. Roll the adventurer’s dice.
2. Add the flat roll bonus.
3. Add any other bonuses or effects.
4. Subtract the Monster’s Armour.
5. Deal the remaining amount as damage to the Monster.

Damage cannot go below 0.

Example:

```text
The player rolls 1d6 + 1 and gets a total of 6.

The Monster has 1 Armour.

Damage dealt = 5.
```

Training helps players defeat Monsters faster by increasing the number of dice rolled.

---

## 8. Quests, Traps, and Discoveries

Quests, Traps, and Discoveries use the adventurer’s roll as a straight success check.

To resolve these cards:

1. Roll the adventurer’s dice.
2. Add the flat roll bonus.
3. Add any other bonuses or effects.
4. Compare the final result to the card’s targets.
5. Resolve the highest target reached.

Each type treats failure differently:

| Adventure Type | Failure Result           |
| -------------- | ------------------------ |
| Quest          | No reward.               |
| Trap           | Trigger the Trap Effect. |
| Discovery      | Gain the failure reward. |

---

## 9. Boons

Boons are temporary bonuses that may be gained through cards, discoveries, town effects, or future adventurer skills.

For Version 0.1.2, boons are a simple placeholder system.

Possible boon effects include:

* +2 to an Adventure roll
* Reroll 1 die
* Move +2 spaces
* Ignore 1 Trap Effect
* Prevent 1 Monster retaliation
* Draw 1 extra Resource after resolving an Adventure Card

Boons should usually be one-use effects.

---

## 10. Future Adventurer Skills

In future versions, boons may become unique adventurer skills.

Different adventurers may eventually have different abilities and playstyles.

Example future skills:

| Adventurer Style | Possible Skill                                    |
| ---------------- | ------------------------------------------------- |
| Ranger           | Reroll on Discovery cards.                        |
| Barbarian        | Deal +2 damage against Monsters.                  |
| Rogue            | Ignore the first Trap Effect each round.          |

These unique skills are not part of the first playable prototype unless added later.

---

## 11. Gear

Gear is expected to improve adventurers in a future version.

The current working assumption is:

```text
Training improves dice.
Gear improves the flat bonus.
Skills provide unique effects.
```

Gear may eventually come from:

* Crafted Goods
* Shop upgrades
* Town actions
* Selling Card rewards
* Adventure rewards
* Specific adventurer abilities

Gear is not fully defined in Version 0.1.2.

---

## 12. Current Prototype Assumptions

The current adventurer assumptions are:

* All adventurers start the same.
* Each adventurer starts with 1d6 + 1.
* Each adventurer starts with 0 training.
* Training increases dice at 2 and 4 training.
* Training does not increase the flat +1 bonus.
* Equipped Armaments, Consumables, or Trinkets may improve the flat bonus later.
* Boons are temporary one-use bonuses.
* Unique adventurer skills are a future design layer.
* The first prototype should test the shared dice system before adding full adventurer asymmetry.

---

## 13. Playtest Notes

Things to check during playtesting:

* Does 1d6 + 1 feel too weak or strong at the start?
* Are targets reachable enough in Round 1?
* Does training to 2d6 + 1 feel worth the Town actions?
* Can players realistically reach 3d6 + 1 within 3 rounds?
* Does Monster combat feel better with more dice?
* Are Trap penalties too harsh for low-dice adventurers?
* Do Discoveries feel rewarding enough even with low rolls?
* Should the flat +1 bonus stay fixed, or should gear improve it earlier?
