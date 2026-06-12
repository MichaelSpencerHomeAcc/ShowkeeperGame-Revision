# Items and Tags

This document defines the item system for Shopkeeper Showdown.

Items are the main goods players gather, craft, steal, trade, and sell. Each item has one main item type and may also have one or more tags.

The main item type keeps the economy simple. Tags add flavour, special uses, and mechanical variety.

Items may come from several decks: Basic Resources, Crafted Goods, Artifacts, and Black Market Goods. 
All item cards still use the same four main item types: Armament, Consumable, Trinket, and Trade Good. 
Special decks add stronger tags, higher values, or riskier rules.

---

## 1. Purpose of the Item System

The item system should:

* Keep the core economy easy to understand.
* Support different shopkeeper strategies.
* Allow Selling Cards to ask for broad or specific requirements.
* Give Adventure rewards and Town actions useful outputs.
* Allow special orders, Black Market deals, crafting, and rare goods without needing too many separate resource types.

---

## 2. Item Card Structure

Each item card should include:

| Field     | Purpose                                              |
| --------- | ---------------------------------------------------- |
| Name      | The name of the item.                                |
| Main Type | One of the four core item types.                     |
| Tags      | Special qualities or categories the item belongs to. |
| Value     | The base coin value of the item.                     |
| Effect    | Any special rule the item has, if applicable.        |
| Source    | Where the item usually comes from, if relevant.      |

Example item card structure:

```text
Name: Dragonbone Spear
Main Type: Armament
Tags: Crafted, Rare, Monster Part
Value: 7
Effect: None
Source: Crafted / Monster reward
```

---

## 3. Main Item Types

Every item has exactly one main item type.

The four main item types are:

1. Armament
2. Consumable
3. Trinket
4. Trade Good

These are the broad categories used by Selling Cards, crafting, Adventure rewards, and Town actions.

---

## 4. Armaments

Armaments are weapons, armour, shields, tools, and equipment used by adventurers, guards, soldiers, and travelling heroes.

Examples:

* Sword
* Shield
* Bow
* Throwing knives
* Armour
* Enchanted blade
* Adventuring gear
* Monsterbone spear

Common uses:

* Hero Orders
* Guard contracts
* Combat-focused Selling Cards
* Crafting recipes
* Adventure-related upgrades

Example Selling Card requirements:

```text
Requires: 1 Armament
Requires: 2 Armaments
Requires: 1 Crafted Armament
Requires: 1 Rare Armament
```

---

## 5. Consumables

Consumables are items that are used up, eaten, drunk, thrown, burned, or activated.

Examples:

* Potion
* Food
* Medicine
* Scroll
* Bomb
* Oil
* Elixir
* Rations
* Antidote

Common uses:

* Adventurer supply orders
* Alchemy Orders
* Emergency requests
* Healing or utility effects
* Fast, flexible sales

Example Selling Card requirements:

```text
Requires: 1 Consumable
Requires: 2 Consumables
Requires: 1 Magical Consumable
Requires: 1 Crafted Consumable
```

---

## 6. Trinkets

Trinkets are jewellery, charms, curios, relics, magical oddities, and small valuable items.

Examples:

* Ring
* Amulet
* Charm
* Music box
* Lucky coin
* Cursed locket
* Crystal pendant
* Decorative idol

Common uses:

* Noble commissions
* Collector requests
* Reputation-focused sales
* Magical orders
* Luxury goods

Example Selling Card requirements:

```text
Requires: 1 Trinket
Requires: 2 Trinkets
Requires: 1 Rare Trinket
Requires: 1 Magical Trinket
Requires: 1 Luxury Trinket
```

---

## 7. Trade Goods

Trade Goods are raw materials, cargo, bulk goods, supplies, ingredients, and practical resources.

Examples:

* Ore
* Cloth
* Wood
* Spices
* Grain
* Leather
* Monster hide
* Coral crate
* Alchemical ingredients

Common uses:

* Business Orders
* Crafting
* Bulk contracts
* Upgrade costs
* Town actions
* Resource conversion

Example Selling Card requirements:

```text
Requires: 1 Trade Good
Requires: 3 Trade Goods
Requires: 1 Rare Trade Good
Requires: 1 Monster Part Trade Good
```

---

## 8. Tags

Tags are additional labels that define special qualities, restrictions, or synergies.

An item may have no tags, one tag, or multiple tags.

Tags allow Selling Cards, Town actions, Adventure rewards, and shop upgrades to refer to more specific kinds of items.

For example:

```text
Requires: Any Stolen item
Requires: 1 Crafted Armament
Requires: 1 Rare Trinket
Requires: Any 2 Monster Part items
Requires: 1 Magical Consumable and 1 Luxury Trinket
```

---

## 9. Starting Tags

The first prototype should use a small number of tags.

Recommended starting tags:

| Tag          | Meaning                                                      |
| ------------ | ------------------------------------------------------------ |
| Crafted      | The item was made or improved through crafting.              |
| Rare         | The item is harder to find and usually more valuable.        |
| Magical      | The item has magical properties.                             |
| Monster Part | The item came from a defeated monster or dangerous creature. |
| Artifact     | The item is especially unusual, ancient, or valuable.        |

---

## 10. Future Tags

These tags may be added later if needed.

| Tag          | Possible Use                                          |
| ------------ | ----------------------------------------------------- |
| Black Market | Wanted by shady buyers or criminal contacts.          |
| Luxury       | Desired by nobles, collectors, and wealthy customers. |
| Contraband   | Risky to hold or sell.                                |
| Common       | Basic, reliable, low-value items.                     |
| Perishable   | May expire or lose value.                             |
| Cursed       | Powerful but risky.                                   |
| Regional     | Linked to a specific Adventure region.                |
| Sacred       | Useful for temples, clerics, or holy orders.          |

Future tags should only be added if they create meaningful gameplay.

---

## 11. Tag Rules

Current assumptions:

* Each item has exactly one main item type.
* Each item may have any number of tags.
* Tags do not replace the main item type.
* Tags can be used by Selling Cards, quests, upgrades, and Town actions.
* Tags should be easy to understand from the card name and artwork.
* Tags should not be added unless they matter mechanically.

Example:

```text
Cursed Silver Locket
Main Type: Trinket
Tags: Stolen, Magical
Value: 6
```

This item counts as:

* A Trinket
* A Stolen item
* A Magical item

It could satisfy any requirement asking for:

```text
1 Trinket
1 Stolen item
1 Magical item
1 Magical Trinket
1 Stolen Trinket
```

---

## 12. Selling Card Requirement Examples

Selling Cards can ask for broad item types:

```text
Requires: 2 Consumables
Requires: 1 Armament and 1 Trinket
Requires: 3 Trade Goods
```

Selling Cards can ask for tags:

```text
Requires: Any 1 Stolen item
Requires: Any 2 Rare items
Requires: Any 1 Artifact
```

Selling Cards can ask for type and tag combinations:

```text
Requires: 1 Crafted Armament
Requires: 1 Magical Consumable
Requires: 1 Rare Trinket
Requires: 1 Monster Part Trade Good
```

Selling Cards can also mix requirements:

```text
Requires: 1 Armament and 1 Monster Part item
Requires: 1 Magical item and 1 Trade Good
Requires: 1 Stolen Trinket and 1 Consumable
```

---

## 13. Example Items

| Item                   | Main Type  | Tags                        | Value |
| ---------------------- | ---------- | --------------------------- | ----- |
| Iron Sword             | Armament   | None                        | 3     |
| Dragonbone Spear       | Armament   | Crafted, Rare, Monster Part | 7     |
| Healing Potion         | Consumable | Crafted                     | 3     |
| Glowcap Tonic          | Consumable | Crafted, Magical            | 5     |
| Silver Ring            | Trinket    | None                        | 3     |
| Cursed Silver Locket   | Trinket    | Stolen, Magical             | 6     |
| Crate of Ore           | Trade Good | None                        | 3     |
| Basilisk Hide          | Trade Good | Monster Part, Rare          | 6     |
| Ancient Coin           | Trinket    | Artifact, Rare              | 8     |
| Black Market Fireworks | Consumable | Stolen, Magical             | 6     |

---

## 14. Design Notes

The four main item types should remain stable unless playtesting shows they are not broad enough.

Tags are where most of the flexibility should come from.

This structure should allow the game to support simple sales, special orders, crafting paths, Black Market deals, and rare item strategies without requiring a large number of different resource categories.

---

## 15. Related Documents

Related files:

* `cards/selling-cards.md`
* `components/player-boards.md`
* `phases/adventure-phase.md`
* `phases/town-phase.md`
* `phases/selling-phase.md`
* `design-decisions.md`
* `CHANGELOG.md`
