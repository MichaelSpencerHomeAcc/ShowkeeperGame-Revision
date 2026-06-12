# Resource Cards

This document defines the purpose, structure, and design rules for the Basic Resource Deck in Shopkeeper Showdown.

The actual Resource Card list should be maintained in the card database spreadsheet, not in this Markdown file.

This file explains how Resource Cards work.
The spreadsheet stores the individual card entries.

---

## 1. Purpose of the Basic Resource Deck

The Basic Resource Deck is the main economy deck.

Resource Cards represent everyday goods that players can gather, buy, trade, discover, or use to fulfil basic selling opportunities.

The deck should provide reliable goods that can be used for:

* Selling Cards
* Crafting
* Town actions
* Shop upgrades
* Quests
* Trading or conversion effects

The Basic Resource Deck should be broad enough to support all four main item types while remaining easy to understand.

---

## 2. Relationship to Other Item Decks

The Basic Resource Deck does not include every possible item in the game.

Other item decks may exist separately:

| Deck                | Purpose                                      |
| ------------------- | -------------------------------------------- |
| Basic Resource Deck | Everyday goods and the main item economy.    |
| Crafted Goods Deck  | Items created or improved through crafting.  |
| Artifact Deck       | Rare, ancient, high-value, or unusual items. |
| Black Market Deck   | Stolen, illegal, shady, or risky goods.      |

All item decks may still use the same four main item types:

* Armament
* Consumable
* Trinket
* Trade Good

The difference between decks is how the cards enter play and what kind of gameplay they support.

---

## 3. Deck Size

Current target deck size for the Basic Resource Deck:

| Item Type   | Number of Cards |
| ----------- | --------------: |
| Armaments   |              24 |
| Consumables |              24 |
| Trinkets    |              24 |
| Trade Goods |              24 |
| **Total**   |          **96** |

This number is intended to support a 4–6 player game where players may gain several resources during the Adventure and Town phases.

The exact card count may change after testing.

---

## 4. Main Item Types

Every Resource Card has exactly one main item type.

The four main item types are:

1. Armament
2. Consumable
3. Trinket
4. Trade Good

These types are used by Selling Cards, crafting, quests, upgrades, and other game effects.

---

## 5. Armaments

Armaments are weapons, armour, shields, tools, and combat equipment.

They represent goods wanted by adventurers, guards, soldiers, monster hunters, and travelling heroes.

Example Armament concepts:

* Swords
* Shields
* Bows
* Armour
* Daggers
* Adventuring gear
* Magical weapons
* Monster-bone weapons

Common uses:

* Hero Orders
* Guard contracts
* Combat-focused Selling Cards
* Crafting recipes
* Adventure-related upgrades

---

## 6. Consumables

Consumables are items that are used up, eaten, drunk, thrown, burned, or activated.

They represent practical supplies, potions, food, medicines, and single-use magical goods.

Example Consumable concepts:

* Potions
* Food
* Medicine
* Scrolls
* Bombs
* Oils
* Rations
* Antidotes
* Alchemical mixtures

Common uses:

* Adventurer supply orders
* Alchemy Orders
* Emergency requests
* Healing or utility effects
* Fast, flexible sales

---

## 7. Trinkets

Trinkets are jewellery, charms, curios, relics, keepsakes, and small valuable items.

They represent goods wanted by nobles, collectors, mages, temples, travellers, and wealthy visitors.

Example Trinket concepts:

* Rings
* Lockets
* Charms
* Brooches
* Music boxes
* Prayer beads
* Lucky coins
* Decorative idols
* Magical curios

Common uses:

* Noble commissions
* Collector requests
* Reputation-focused sales
* Magical orders
* Luxury goods

---

## 8. Trade Goods

Trade Goods are raw materials, cargo, ingredients, supplies, and bulk goods.

They represent the practical backbone of the economy and are often used for crafting, upgrades, and large contracts.

Example Trade Good concepts:

* Ore
* Cloth
* Wood
* Grain
* Leather
* Spices
* Herbs
* Ingots
* Monster hides
* Alchemical ingredients

Common uses:

* Business Orders
* Crafting
* Bulk contracts
* Upgrade costs
* Town actions
* Resource conversion

---

## 9. Tags on Resource Cards

Resource Cards may have tags, but the Basic Resource Deck should use tags carefully.

Tags add extra meaning to a card and allow Selling Cards, quests, upgrades, and Town actions to ask for more specific items.

Example requirements using tags:

* Any 1 Rare item
* Any 2 Magical items
* 1 Elegant Trinket
* 1 Food Consumable
* 1 Material Trade Good
* 1 Sacred item

---

## 10. Current Tag List

The current working tag list includes:

| Tag          | Meaning                                                          |
| ------------ | ---------------------------------------------------------------- |
| Common       | A standard, reliable item.                                       |
| Rare         | A more valuable or harder-to-find item.                          |
| Magical      | An item with magical properties.                                 |
| Monster Part | An item taken from a creature or dangerous beast.                |
| Exotic       | A rare, strange, far-travelled, or unusual item.                 |
| Cursed       | A high-value or unusual item that may carry risk.                |
| Elegant      | A luxurious or refined item valued by nobles and wealthy buyers. |
| Contraband   | A risky, illegal, stolen, or black-market item.                  |
| Sacred       | An ornate or holy item with religious or clerical value.         |
| Food         | An item classified as food.                                      |
| Material     | An item used in crafting or construction.                        |
| Herb         | A plant, herb, or natural substance.                             |
| Potion       | An alchemical creation that can be ingested or used.             |
| Reagent      | An alchemical item used in recipes or rituals.                   |

The Basic Resource Deck should generally avoid tags like **Crafted**, **Artifact**, and **Stolen**, because those belong more naturally to separate decks.

Contraband may appear rarely in the Basic Resource Deck, but should mostly belong to the Black Market Deck.

---

## 11. Resource Card Anatomy

Each Resource Card should include the following fields in the spreadsheet:

| Field         | Purpose                                                   |
| ------------- | --------------------------------------------------------- |
| Card ID       | Unique code for tracking the card.                        |
| Card Name     | The name of the resource.                                 |
| Deck          | Basic Resource, Crafted Goods, Artifact, or Black Market. |
| Item Type     | Armament, Consumable, Trinket, or Trade Good.             |
| Tags          | Any additional qualities the card has.                    |
| Value         | The card’s base coin value.                               |
| Rarity        | Common, Uncommon, Rare, or Special.                       |
| Source        | Where the card usually comes from.                        |
| Effect        | Any special rule, if the card has one.                    |
| Selling Notes | Notes on what orders or customers may want this item.     |
| Art Notes     | Visual notes or art direction.                            |
| Asset File    | File path for the card image, if designed.                |
| Status        | Idea, Drafted, Designed, Tested, or Final.                |
| Balance Notes | Notes from testing or review.                             |

Example spreadsheet row:

| Card ID     | Card Name  | Deck           | Item Type | Tags   | Value | Rarity | Source             | Effect | Status  |
| ----------- | ---------- | -------------- | --------- | ------ | ----: | ------ | ------------------ | ------ | ------- |
| RES-ARM-001 | Iron Sword | Basic Resource | Armament  | Common |     3 | Common | Adventure / Market | None   | Drafted |

---

## 12. Value Bands

Resource Cards should generally sit within simple value bands.

| Value | Meaning                                                          |
| ----: | ---------------------------------------------------------------- |
|   1–2 | Very low-value filler item.                                      |
|   3–4 | Standard basic item.                                             |
|   5–6 | Strong basic item or lightly tagged item.                        |
|   7–8 | Rare, magical, elegant, or monster-part item.                    |
|    9+ | Usually reserved for Crafted Goods, Artifacts, or special decks. |

The Basic Resource Deck should mostly contain values from **2 to 6**, with only a smaller number of cards reaching **7 or 8**.

---

## 13. Suggested Distribution Per Item Type

Each item type currently targets 24 cards.

Suggested spread per type:

| Category                              | Cards Per Type |
| ------------------------------------- | -------------: |
| Common/basic items                    |             12 |
| Rare items                            |              3 |
| Magical items                         |              2 |
| Monster Part / creature-related items |              2 |
| Elegant / luxury-style items          |              2 |
| Material / practical-use items        |              2 |
| Flexible or experimental tag slot     |              1 |
| **Total**                             |         **24** |

Across the full 96-card Basic Resource Deck, this gives:

| Category                              | Total Cards |
| ------------------------------------- | ----------: |
| Common/basic items                    |          48 |
| Rare items                            |          12 |
| Magical items                         |           8 |
| Monster Part / creature-related items |           8 |
| Elegant / luxury-style items          |           8 |
| Material / practical-use items        |           8 |
| Flexible or experimental tag slots    |           4 |
| **Total**                             |      **96** |

This distribution is only a starting point and should be adjusted after testing.

---

## 14. Spreadsheet as the Source of Truth

The spreadsheet should be the source of truth for the actual card list.

This Markdown file should not contain the full list of Resource Cards.

Use the spreadsheet for:

* Card names
* Card IDs
* Deck assignment
* Item types
* Tags
* Values
* Effects
* Rarity
* Status
* Balance notes
* Asset paths

Use this Markdown file for:

* Design rules
* Deck purpose
* Card anatomy
* Tag guidance
* Value guidance
* Distribution targets
* Notes for future revision

---

## 15. Asset Storage

Designed Resource Card images should be stored in:

```text
assets/card-drafts/resource-cards/
```

Suggested folders:

```text
assets/card-drafts/resource-cards/armaments/
assets/card-drafts/resource-cards/consumables/
assets/card-drafts/resource-cards/trinkets/
assets/card-drafts/resource-cards/trade-goods/
```

Example asset paths:

```text
assets/card-drafts/resource-cards/armaments/iron-sword.png
assets/card-drafts/resource-cards/consumables/healing-potion.png
assets/card-drafts/resource-cards/trinkets/silver-ring.png
assets/card-drafts/resource-cards/trade-goods/crate-of-ore.png
```

---

## 16. Notes for Future Revision

Things to review after testing:

* Whether 96 Basic Resource Cards is enough for 4–6 players.
* Whether the Basic Resource Deck needs duplicate cards or all unique cards.
* Whether the value bands are too flat or too generous.
* Whether Monster Part cards should remain in the Basic Resource Deck or move mostly into Monster rewards.
* Whether Rare and Magical cards appear often enough.
* Whether Selling Cards ask for item types too often or tags too often.
* Whether Trade Goods are too broad compared to the other item types.
* Whether basic cards need small effects, or whether effects should be reserved for special decks.
* Whether Contraband should appear in the Basic Resource Deck or only in the Black Market Deck.
* Whether Food, Potion, Herb, Material, and Reagent create enough useful variety without becoming too specific.

---

## 17. Related Documents

Related files:

* `components/items-and-tags.md`
* `cards/crafted-goods-cards.md`
* `cards/artifact-cards.md`
* `cards/black-market-cards.md`
* `cards/selling-cards.md`
* `data/Shopkeeper_Showdown_Card_Database.xlsx`
* `design-decisions.md`
* `CHANGELOG.md`
