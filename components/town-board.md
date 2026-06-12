# Town Board

This document defines the Town board for the first playable prototype of Shopkeeper Showdown.

The Town board is where players prepare for future rounds, improve their adventurer, gain resources, complete crafts, equip gear, and create scoring opportunities.

These rules are for Version 0.1.2 and are intentionally simple for the first playable prototype.

---

## 1. Purpose

The Town board gives players strategic choices between Adventure and Selling.

During the Town Phase, players use Town locations to improve their position before the next Selling Phase or future Adventure Phases.

Town locations should help players:

* Gain resources
* Train their adventurer
* Craft or restore valuable goods
* Convert resources into reputation
* Equip their adventurer
* Gain objectives
* Gain promotions
* Sell resources quickly
* Prepare for future movement
* Use specialist effects

---

## 2. Prototype Town Board

The first playable prototype uses 10 Town locations:

| Location         | Main Purpose                                |
| ---------------- | ------------------------------------------- |
| Barracks         | Train your Adventurer.                      |
| Workshop         | Complete a Craft or Artifact.               |
| Alchemist        | Convert a Resource into Reputation.         |
| Guild Hall       | Use a Professional.                         |
| Market Square    | Draw Resource Cards.                        |
| Auction House    | Sell Resources for quick Coins.             |
| Tavern           | Equip your Adventurer.                      |
| Bulletin Board   | Draw an Objective.                          |
| Promoter’s Booth | Draw a Promotion.                           |
| Stables          | Gain movement for the next Adventure Phase. |

---

## 3. Location Access

For the first playable prototype, Town locations are always available.

Players do not block each other from using the same Town location.

Multiple players may use the same Town location in the same round.

This keeps the first prototype focused on testing the core action economy rather than location denial.

---

## 4. Town Location Pressure

Location pressure may be added in a future version.

Possible future rules include:

* First player to use a location gets the best reward.
* Later players pay +1 coin to use an occupied location.
* Each location has limited spaces.
* Some locations become unavailable after use.
* Players can interfere with shops at certain locations.

For Version 0.1.2, do not use location pressure unless specifically testing it.

---

## 5. Barracks

The Barracks is used to train an adventurer.

Prototype action:

```text
Gain 1 Training.
```

Training increases the number of dice an adventurer rolls.

| Training Level | Adventure Roll |
| -------------: | -------------- |
|   0–1 Training | 1d6 + 1        |
|   2–3 Training | 2d6 + 1        |
|    4+ Training | 3d6 + 1        |

The flat +1 bonus does not increase through training.

---

## 6. Workshop

The Workshop is used to complete crafted goods or restore artifacts.

Prototype action:

```text
Complete 1 Craft or make progress on 1 Artifact.
```

The Workshop supports:

* Crafted Goods
* Artifact restoration
* Resource upgrading
* Future item improvement systems

For the first prototype, a Craft or Artifact card should define its own requirements.

Example:

```text
Spend 1 Armament and 1 Material Resource to complete this Craft.
```

If Artifact restoration needs progress, use progress markers.

Suggested simple prototype rule:

```text
Use the Workshop to place 1 progress marker on an Artifact, or complete a Craft if you can pay its full requirement.
```

---

## 7. Alchemist

The Alchemist converts resources into Reputation based on rarity.

Prototype action:

```text
Discard 1 Resource. Gain Reputation based on its Rarity.
```

Suggested prototype conversion:

| Resource Rarity                    | Reputation Gained |
| ---------------------------------- | ----------------: |
| Common                             |                 1 |
| Uncommon / Rare                    |                 2 |
| Magical / Exotic / Cursed / Sacred |                 3 |

If the current Resource data uses different rarity names, use the closest matching rarity band.

The Alchemist gives players a way to turn unwanted Resources into end-game value.

---

## 8. Guild Hall

The Guild Hall allows players to use a Professional.

Prototype action:

```text
Use 1 Professional effect.
```

Professionals are one-use specialist effects.

Example Professional effects may include:

| Professional | Example Effect                                          |
| ------------ | ------------------------------------------------------- |
| Scout        | Move 1 Mystery Token or reveal the top Adventure Card.  |
| Appraiser    | Increase the sale value of 1 Resource by +2 this round. |
| Guard        | Protect 1 Resource from loss or theft.                  |
| Courier      | Complete a small delivery for coins.                    |
| Broker       | Draw 2 Selling Cards, keep 1.                           |
| Trainer      | Gain +1 to your next Adventure roll.                    |

Professional rules may be expanded in a future version.

For Version 0.1.2, Professional effects can be kept as simple one-use cards or a small shared list.

---

## 9. Market Square

The Market Square is the main way to gain basic Resources.

Prototype action:

```text
Draw 2 Resource Cards.
```

Unless a future hand limit or storage limit is added, keep both cards.

The Market Square should primarily draw from the Basic Resource Deck.

---

## 10. Auction House

The Auction House lets players sell Resources quickly for Coins.

Prototype action:

```text
Choose 1 or more Resources to auction. Roll to determine the sale bonus or penalty, then gain Coins.
```

Suggested simple prototype rule:

1. Choose 1 Resource to auction.
2. Roll 1d6.
3. Gain Coins equal to the Resource value plus the auction result modifier.
4. Discard the Resource.

Suggested auction modifier:

| d6 Result | Auction Result       |
| --------: | -------------------- |
|         1 | Bad sale: -2 Coins   |
|       2–3 | Poor sale: -1 Coin   |
|       4–5 | Fair sale: +0 Coins  |
|         6 | Great sale: +2 Coins |

A Resource cannot sell for less than 1 Coin.

The Auction House gives players a way to turn unwanted Resources into quick money.

---

## 11. Tavern

The Tavern is used to equip an adventurer.

Prototype action:

```text
Equip 1 eligible item to your Adventurer.
```

Eligible gear items are:

* Armaments
* Consumables
* Trinkets

Trade Goods cannot normally be equipped as gear unless a card specifically says otherwise.

Gear is not a separate card type. It is a use for certain item types.

Current working assumption:

```text
Training improves dice.
Gear improves the flat bonus or provides Adventure effects.
Skills provide unique effects.
```

For Version 0.1.2, equipped items may provide simple bonuses such as:

* +1 to Adventure rolls
* +1 to Monster damage
* Reroll 1 die on a specific Adventure Card type
* Ignore 1 Trap Effect
* Prevent 1 Monster retaliation
* Gain +1 movement during an Adventure turn

---

## 12. Bulletin Board

The Bulletin Board provides Objectives.

Prototype action:

```text
Draw 1 Objective Card.
```

Objectives are personal scoring goals or side goals.

Objectives may reward players for:

* Completing certain Selling Cards
* Collecting certain item types
* Gaining Reputation
* Defeating Monsters
* Completing Quests
* Using Town locations
* Ending the game with certain resources

Objective Cards are not fully defined in Version 0.1.2, but the Bulletin Board reserves a clear location for them.

---

## 13. Promoter’s Booth

The Promoter’s Booth provides Promotions.

Prototype action:

```text
Draw 1 Promotion Card.
```

Promotions represent advertising, hype, public demand, shop events, or temporary sales boosts.

Promotions may affect:

* Selling value
* Reputation gain
* Visitor demand
* Public Visitor interactions
* Sale bonuses
* Specific item types or tags

Example Promotion effects:

```text
Your next Trinket sale gains +2 Coins.
```

```text
Gain +1 Reputation the next time you complete a Visitor.
```

```text
The next Resource you sell with the Elegant tag gains +3 Coins.
```

Promotion Cards are not fully defined in Version 0.1.2, but the Promoter’s Booth reserves a clear location for them.

---

## 14. Stables

The Stables improve movement during the next Adventure Phase.

Prototype action:

```text
Gain +2 movement during your next Adventure Phase.
```

Suggested tracking:

* Take a Stable token.
* During your next Adventure Phase, your first Adventure turn has +2 movement.
* Discard the Stable token after use.

Alternative stronger version for testing:

```text
Gain +2 movement on each of your Adventure turns during the next Adventure Phase.
```

For the first test, use the weaker version unless movement feels too slow.

---

## 15. Current Prototype Assumptions

The current Town board assumptions are:

* The Town board has 10 locations.
* Each player takes 5 Town actions per round.
* Locations are always available.
* Players do not block each other from using locations.
* Location pressure is not active yet.
* Barracks is the main Training location.
* Market Square is the main Resource draw location.
* Workshop supports Crafting and Artifacts.
* Tavern supports Adventurer equipment.
* Bulletin Board and Promoter’s Booth introduce future card systems.
* Stables gives movement support for the next Adventure Phase.

---

## 16. Playtest Notes

Things to check during playtesting:

* Are 10 Town locations too many, too few, or about right?
* Are 5 Town actions enough?
* Is Barracks worth using compared with gaining Resources?
* Does Market Square provide enough Resources?
* Does Auction House feel useful or too random?
* Does Alchemist make Reputation too easy to gain?
* Does Workshop need clearer Craft and Artifact requirements?
* Does Tavern need real gear cards before it becomes useful?
* Are Objectives and Promotions ready for testing, or should they be added later?
* Is Stables strong enough with +2 movement?
* Should Town locations have blocking, costs, or pressure in a future version?
