# Town Phase

This document defines the Town Phase for the first playable prototype of Shopkeeper Showdown.

The Town Phase is where players prepare their shops, improve their adventurers, gain resources, craft goods, equip gear, and create future selling opportunities.

These rules are for Version 0.1.2 and are intentionally simple for the first playable prototype.

---

## 1. Purpose

The Town Phase is the main preparation and specialisation phase.

Players use Town actions to decide how they want to build towards scoring.

A player may focus on:

* Training their adventurer
* Gaining more Resources
* Crafting valuable goods
* Restoring Artifacts
* Building Reputation
* Preparing sales
* Equipping their adventurer
* Gaining Objectives
* Gaining Promotions
* Creating quick Coins

The Town Phase should create meaningful choices before the Selling Phase and the next Adventure Phase.

---

## 2. Current Prototype Structure

Each player takes **5 Town actions per round**.

Players take Town actions one at a time, starting with the First Player and continuing clockwise.

Continue until each player has taken 5 Town actions.

---

## 3. Town Turn Overview

On a Town turn, a player chooses 1 available Town location and resolves that location’s action.

A Town turn follows this structure:

1. Choose 1 Town location.
2. Pay any required cost.
3. Resolve the location action.
4. Gain any rewards or effects.
5. End the Town turn.

For Version 0.1.2, Town locations do not become blocked after use.

---

## 4. Town Locations

The first playable prototype uses 10 Town locations:

| Location         | Action                                                  |
| ---------------- | ------------------------------------------------------- |
| Barracks         | Gain 1 Training.                                        |
| Workshop         | Complete 1 Craft or make progress on 1 Artifact.        |
| Alchemist        | Convert 1 Resource into Reputation based on its Rarity. |
| Guild Hall       | Use 1 Professional effect.                              |
| Market Square    | Draw 2 Resource Cards.                                  |
| Auction House    | Roll and sell 1 Resource for quick Coins.               |
| Tavern           | Equip 1 eligible card to your Adventurer.               |
| Bulletin Board   | Draw 1 Objective Card.                                  |
| Promoter’s Booth | Draw 1 Promotion Card.                                  |
| Stables          | Gain +2 movement during your next Adventure Phase.      |

---

## 5. Location Availability

For the first playable prototype, all Town locations are always available.

Players may choose the same location as another player.

Players may choose the same location multiple times across a round unless the location or an effect says otherwise.

Location blocking is not used in Version 0.1.2.

---

## 6. Barracks Action

The Barracks trains the player’s adventurer.

Action:

```text
Gain 1 Training.
```

Training increases the number of dice the adventurer rolls.

| Training Level | Adventure Roll |
| -------------: | -------------- |
|   0–1 Training | 1d6 + 1        |
|   2–3 Training | 2d6 + 1        |
|    4+ Training | 3d6 + 1        |

The flat +1 bonus does not increase through Training.

---

## 7. Workshop Action

The Workshop is used for Crafting and Artifacts.

Action:

```text
Complete 1 Craft or make progress on 1 Artifact.
```

A Craft or Artifact card should list its own requirements.

Suggested prototype rules:

* To complete a Craft, pay the listed Resource requirement and gain the completed Crafted Good.
* To restore an Artifact, place 1 progress marker on that Artifact.
* If an Artifact reaches its required progress, complete or activate it.

If Craft and Artifact cards are not ready, the Workshop may be temporarily used as:

```text
Upgrade 1 Resource into a Crafted Good if you can pay its listed requirement.
```

---

## 8. Alchemist Action

The Alchemist converts Resources into Reputation.

Action:

```text
Discard 1 Resource. Gain Reputation based on its Rarity.
```

Suggested prototype conversion:

| Resource Rarity                    | Reputation Gained |
| ---------------------------------- | ----------------: |
| Common                             |                 1 |
| Uncommon / Rare                    |                 2 |
| Magical / Exotic / Cursed / Sacred |                 3 |

If the Resource has no listed rarity, treat it as Common.

The discarded Resource goes to the appropriate discard pile.

---

## 9. Guild Hall Action

The Guild Hall allows a player to use a Professional.

Action:

```text
Use 1 Professional effect.
```

Professionals are specialist helpers that provide one-use effects.

For the first prototype, choose one Professional from a shared list or draw one from a Professional deck if one exists.

Example Professional effects:

| Professional | Effect                                        |
| ------------ | --------------------------------------------- |
| Scout        | Move 1 Mystery Token up to 2 spaces.          |
| Appraiser    | Add +2 Coins to your next sale this round.    |
| Guard        | Protect 1 Resource from the next loss effect. |
| Broker       | Draw 2 Selling Cards, keep 1.                 |
| Trainer      | Gain +1 to your next Adventure roll.          |
| Courier      | Gain 2 Coins.                                 |

Professional effects should be resolved immediately unless the card says otherwise.

---

## 10. Market Square Action

The Market Square gives players basic Resources.

Action:

```text
Draw 2 Resource Cards.
```

Draw from the Basic Resource Deck.

Unless hand size or storage limits are added later, keep both cards.

If the Resource Deck is empty, shuffle the Resource discard pile to form a new deck.

---

## 11. Auction House Action

The Auction House lets players sell a Resource for quick Coins.

Action:

```text
Roll and sell 1 Resource for quick Coins.
```

To resolve the Auction House:

1. Choose 1 Resource from your shop or hand.
2. Roll 1d6.
3. Apply the auction modifier.
4. Gain Coins equal to the Resource’s value plus the modifier.
5. Discard the Resource.

Auction modifier:

| d6 Result | Modifier |
| --------: | -------: |
|         1 | -2 Coins |
|       2–3 |  -1 Coin |
|       4–5 | +0 Coins |
|         6 | +2 Coins |

A Resource cannot sell for less than 1 Coin.

The Auction House does not count as completing a Selling Card.

---

## 12. Tavern Action

The Tavern allows players to equip their adventurer.

Action:

```text
Equip 1 eligible item to your Adventurer.
```

Eligible gear items are:

* Armaments
* Consumables
* Trinkets

Trade Goods cannot normally be equipped as gear unless a card specifically says otherwise.

Gear is not a separate card type. It is a use for certain item types.

Working design split:

```text
Training improves dice.
Gear improves the flat bonus or provides Adventure effects.
Skills provide unique effects.
```

To resolve the Tavern action:

1. Choose 1 Armament, Consumable, or Trinket you own.
2. Equip it to your Adventurer.
3. Apply the item’s equipment effect.
4. If the item is a one-use item, discard it after use.

---

## 13. Bulletin Board Action

The Bulletin Board gives players Objectives.

Action:

```text
Draw 1 Objective Card.
```

Objectives are personal goals or scoring opportunities.

Objectives may be completed immediately or at end game, depending on the card.

If Objective Cards are not ready for the first playtest, skip this location or use a small placeholder deck.

---

## 14. Promoter’s Booth Action

The Promoter’s Booth gives players Promotions.

Action:

```text
Draw 1 Promotion Card.
```

Promotions are temporary shop boosts, adverts, events, or sale modifiers.

Promotions may affect:

* Coin rewards
* Reputation rewards
* Specific item types
* Specific tags
* Selling Cards
* Public Visitors

If Promotion Cards are not ready for the first playtest, skip this location or use a small placeholder deck.

---

## 15. Stables Action

The Stables improves future Adventure movement.

Action:

```text
Gain +2 movement during your next Adventure Phase.
```

Suggested prototype version:

```text
Your first Adventure turn next Adventure Phase has +2 movement.
```

Track this with a Stable token.

Discard the Stable token after it is used.

If the board feels too large during playtesting, test the stronger version:

```text
Each of your Adventure turns next Adventure Phase has +2 movement.
```

---

## 16. End of Town Phase

The Town Phase ends when each player has taken 5 Town actions.

After the Town Phase ends, continue to the next phase of the round.

In the current prototype structure, this is usually the Selling Phase.

---

## 17. Current Prototype Assumptions

The current Town Phase assumptions are:

* Each player takes 5 Town actions per round.
* Each Town turn uses 1 location.
* Town locations are always available.
* Location blocking is not active.
* The Town board has 10 locations.
* Barracks is used for Training.
* Market Square draws Resources.
* Workshop handles Crafts and Artifacts.
* Guild Hall handles Professionals.
* Tavern handles equipment.
* Bulletin Board handles Objectives.
* Promoter’s Booth handles Promotions.
* Stables improves next Adventure movement.

---

## 18. Playtest Notes

Things to check during playtesting:

* Are 5 Town actions enough?
* Are any Town locations obviously stronger than the others?
* Are any Town locations too weak or too situational?
* Does Training compete well with drawing Resources?
* Does Auction House provide useful emergency Coins?
* Does Alchemist make Reputation too easy or too slow?
* Does Stables matter on a 10x8 board with 4 movement?
* Do players understand the difference between Objectives and Promotions?
* Do Workshop and Tavern need more card support before they become useful?
* Should repeated use of the same Town location become more expensive later?
