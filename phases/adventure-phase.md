# Adventure Phase

This document defines the Adventure Phase for the first playable prototype of Shopkeeper Showdown.

The Adventure Phase is where players move around the Adventure board, interact with Mystery Tokens, and resolve Adventure Cards.

---

## 1. Purpose

The Adventure Phase creates risk, discovery, and resource gain.

Players send their adventurers into the Forest to find opportunities, face danger, complete quests, trigger traps, defeat monsters, and uncover useful goods.

Rewards from the Adventure Phase should feed into later phases of the game, especially Town and Selling.

---

## 2. Current Prototype Structure

Each player takes **5 Adventure turns per round**.

Players take Adventure turns one at a time, starting with the First Player and continuing clockwise.

Continue until each player has taken 5 Adventure turns.

---

## 3. Adventure Turn Overview

On an Adventure turn, a player may:

1. Move up to their movement value.
2. Interact with one Mystery Token if they move onto one.
3. Reveal and resolve the top Adventure Card.
4. Continue moving if they have movement remaining.
5. End their Adventure turn.

Current prototype movement value:

```text
3 spaces
```

---

## 4. Movement

Players move on the Adventure board.

Unless an effect says otherwise, a player may move up to 4 spaces on their Adventure turn.

Players move orthogonally:

* Up
* Down
* Left
* Right

Diagonal movement is not allowed by default.

Players may move through spaces occupied by other players.

Multiple players may occupy the same space.

---

## 5. Mystery Tokens

Mystery Tokens represent unknown Adventure encounters.

When a player interacts with a Mystery Token, they reveal the top card of the Adventure Deck.

The revealed card may be:

* Monster
* Quest
* Trap
* Discovery

Players do not know the card type before revealing it.

---

## 6. Interacting During Movement

If a player moves onto a space containing a Mystery Token, they may pause their movement to interact with it.

When interacting with a Mystery Token:

1. Remove the Mystery Token from the board.
2. Reveal the top card of the Adventure Deck.
3. Resolve the Adventure Card.
4. Place a new Mystery Token on an empty valid space.
5. Continue moving if the player has movement remaining.

A player may only interact with one Mystery Token per Adventure turn unless a card, skill, or boon says otherwise.

---

## 7. Adventure Deck

The Adventure Phase uses one shared Adventure Deck.

All Adventure Cards use the same generic card back.

Adventure Card type is hidden until the card is revealed.

The Adventure Deck contains four card types:

* Monster
* Quest
* Trap
* Discovery

---

## 8. Adventure Card Types

Each Adventure Card type uses a different resolution style.

---

## 8.1 Monster

Monsters are combat encounters.

Monsters are about how quickly the player can defeat them.

A Monster has:

* HP
* Armour
* Retaliation
* Reward for defeating it in 1 attempt
* Reward for defeating it in 2 attempts
* Reward for defeating it in 3 attempts
* Failure effect if not defeated after 3 attempts

### Monster Resolution

When a player reveals a Monster:

1. Roll the player’s adventurer dice.
2. Add any boons, bonuses, or effects.
3. Subtract the Monster’s Armour from the result.
4. Deal the remaining amount as damage to the Monster.
5. If the Monster is defeated, gain the reward based on how many attempts it took.
6. If the Monster survives, it retaliates.
7. Repeat until the Monster is defeated or 3 attempts have been made.
8. If the Monster is not defeated after 3 attempts, resolve its failure effect.

Damage cannot go below 0.

### Monster Identity

Monsters usually punish the player’s economy.

Retaliation usually causes the player to lose:

* Cards
* Resources
* Coins

---

## 8.2 Quest

Quests are tasks, requests, heroic opportunities, and ways to assist people.

Quests use a straight roll for success level.

A Quest has:

* Target 1 and Reward 1
* Target 2 and Reward 2
* Target 3 and Reward 3

### Quest Resolution

When a player reveals a Quest:

1. Roll the player’s adventurer dice.
2. Add any boons, bonuses, or effects.
3. Compare the final result to the Quest’s targets.
4. Gain the reward for the highest target reached.

If the player fails to reach Target 1, they gain no reward.

Quests usually do not retaliate.

### Quest Identity

Quests are opportunity-based.

Failure means the player missed the opportunity, but usually does not lose resources, coins, movement, or dice bonuses.

---

## 8.3 Trap

Traps are sudden dangers, hazards, mimics, assault courses, or ancient mechanisms.

Traps use a straight roll to avoid, disarm, or overcome danger.

A Trap has:

* Target 1 and Reward 1
* Target 2 and Reward 2
* Target 3 and Reward 3
* Trap Effect

### Trap Resolution

When a player reveals a Trap:

1. Roll the player’s adventurer dice.
2. Add any boons, bonuses, or effects.
3. Compare the final result to the Trap’s targets.
4. Gain the reward for the highest target reached.

If the player fails to reach Target 1, the Trap Effect triggers.

### Trap Identity

Traps usually punish the player’s tempo.

Trap Effects usually cause the player to lose:

* Movement
* Dice bonuses
* Speed
* Future roll strength
* Boons
* Adventure efficiency

---

## 8.4 Discovery

Discoveries are hidden caches, strange finds, treasure sites, shrines, clues, resource nodes, and useful opportunities.

Discoveries use a straight roll to determine reward quality.

A Discovery has:

* Failure reward
* Target 1 and Reward 1
* Target 2 and Reward 2
* Target 3 and Reward 3

### Discovery Resolution

When a player reveals a Discovery:

1. Roll the player’s adventurer dice.
2. Add any boons, bonuses, or effects.
3. Compare the final result to the Discovery’s targets.
4. Gain the reward for the highest target reached.

If the player fails to reach Target 1, they still gain the Discovery’s failure reward.

### Discovery Identity

Discoveries are the safest Adventure Card type.

They always provide something, but higher rolls give better rewards.

---

## 9. Adventure Rewards

Adventure Cards may reward players with:

* Resource Cards
* Crafted Goods
* Coins
* Reputation
* Boons
* Movement bonuses
* Selling Cards
* Artifacts
* Training progress
* Temporary effects

Rewards should help players prepare for the Town and Selling phases.

---

## 10. Current Prototype Assumptions

The current Adventure Phase assumptions are:

* Each player takes 5 Adventure turns per round.
* Players move up to 4 spaces per Adventure turn.
* Players may interact with a Mystery Token during movement.
* Players may continue moving after resolving a Mystery Token.
* Players may only interact with one Mystery Token per Adventure turn by default.
* Adventure uses one shared Adventure Deck.
* Adventure Card types are hidden until revealed.
* Mystery Tokens refill when removed.
* The current Adventure map is the Forest.

---

## 11. Playtest Notes

Things to check during playtesting:

* Are 5 Adventure turns too many, too few, or correct?
* Is 4 movement enough on a 10x8 board?
* Does interacting mid-movement feel good?
* Does one Mystery Token interaction per turn feel right?
* Do Monsters feel distinct from Quests, Traps, and Discoveries?
* Are Trap penalties annoying but not too punishing?
* Are Discovery rewards too safe or just right?
* Do Quest failures feel fair?
* Does the board stay active with the refill rule?
