# Changelog

All notable changes to the Shopkeeper Showdown revision design will be documented in this file.

This changelog tracks design changes, rule changes, structural changes, and major wording changes made during development.

---

## Version 0.1 – 10/06/26

### Added

* Created the first structured version of the Core Design Document.
* Defined the core game vision.
* Defined the primary phase loop:

  * Adventure
  * Town
  * Selling
  * Cleanup
* Set the current game length at 3 rounds.
* Defined the current action economy:

  * 3 Adventure turns per player per round
  * 4 Town actions per player per round
  * Up to 2 completed Selling Cards per player per Selling phase
* Added the first version of the game’s design goals.
* Added the initial desired player fantasies:

  * Master Crafter
  * Black-Market Dealer
  * Order-Filling Merchant
  * Alchemist
  * Quest-Focused Adventurer
  * Reputation-Based Shopkeeper
  * Thief or Saboteur
  * High-Risk Opportunist
  * Bulk Order Specialist
  * Rare Goods Trader
* Added the first phase summaries for Adventure, Town, Selling, and Cleanup.
* Added the first player component list.
* Added the first shared component list.
* Added the first card type definitions.
* Added the first scoring assumptions.
* Added the first design decisions log.
* Added three-round balance principles.
* Added suggested round identities:

  * Round 1: Establish
  * Round 2: Specialise
  * Round 3: Cash Out
* Added initial Selling Card categories:

  * Visitor Requests
  * Craft Requests
  * Business Orders
  * Hero Orders
  * Black Market Deals
  * Alchemy Orders
  * Luxury Commissions
* Added Visitors as a type of Selling Card.
* Added early detail around Town locations, Training, Shop Upgrades, and the Black Market.

### Notes

* This is the first official working version of the revised Shopkeeper Showdown design.
* Open questions have intentionally been kept out of the main Core Design Document so they can be handled through separate design discussions and future decision logs.
* Future changes should be recorded as Version 0.2, 0.3, and so on.

---

## Version 0.1.1 – 10/06/26

### Added

* Added a `rules` folder.
* Added `rules/rules-skeleton.md` as the first playable rules outline.
* Added a `data` folder for source-of-truth CSV card data.
* Added `data/lookup-data.csv` for controlled spreadsheet values, including decks, item types, tags, rarity, status, sources, selling types, and visibility.
* Added `data/resource-cards.csv` as the first Basic Resource Deck data file.
* Added `data/crafted-goods.csv` as the first Crafted Goods Deck data file.
* Added `components/items-and-tags.md` to define the shared item system.
* Added support for item cards coming from multiple item decks:

  * Basic Resources
  * Crafted Goods
  * Artifacts
  * Black Market Goods
* Added the CSV/spreadsheet workflow as the direction for managing actual card data.
* Added the working item type system:

  * Armament
  * Consumable
  * Trinket
  * Trade Good
* Added an expanded tag list for item variation, including tags such as Common, Rare, Magical, Monster Part, Exotic, Cursed, Elegant, Contraband, Sacred, Food, Material, Herb, Potion, Reagent, Bulk, Luxury, Regional, Perishable, Forged, Refined, and Volatile.
* Added the first Crafted Goods card concepts, including stronger crafted items with higher values, reputation rewards, and effects such as bonus rolls, movement, rerolls, range, retaliation prevention, skill refreshes, and free interactions.
* Added early Adventure system decisions:

  * Adventure uses one shared Adventure Deck.
  * Adventure board encounters are represented by Mystery Tokens.
  * Adventure Card types are hidden until revealed.
  * Adventure cards may be Monsters, Quests, Traps, or Discoveries.

### Changed

* Changed `cards/resource-cards.md` so it now acts as a rules/design reference rather than a full card list.
* Moved actual card entries out of Markdown and into CSV data files.
* Clarified that Markdown files should explain rules and card structures, while CSV files should hold the actual card data.
* Updated the Resource Card structure to support spreadsheet-based fields such as Card ID, Item Deck, Main Type, Tags, Value, Reputation, Rarity, Effect, Art Notes, Asset File, Status, and Balance Notes.
* Expanded the item system so all item decks can use the same four main item types while varying through deck source, tags, value, rarity, and effects.
* Intentionally increased the phase action economy from the earlier design assumption:

  * Adventure turns increased from 3 to 5 per player.
  * Town actions increased from 4 to 5 per player.
* Updated the prototype direction so each of the 3 rounds gives players more room to explore, prepare, craft, upgrade, and sell.
* Updated Selling so players can complete as many Selling Cards as they can fulfil, instead of being limited to 2 by default.
* Added the idea that Public Selling Cards can receive resources for additional coins.
* Expanded the Town action list to include options such as:

  * Training
  * Crafting
  * Upgrading resources
  * Visiting the Black Market
  * Drawing or swapping Selling Cards
  * Converting resources through alchemy
  * Using a Town Professional
  * Auctioning resources
  * Upgrading the shop
  * Promoting
  * Equipping the adventurer
  * Drawing objectives
* Updated scoring assumptions to include:

  * Coins
  * Reputation
  * Completed Selling Cards
  * Shop upgrades
  * Adventurer strength
  * Objectives
  * Artifacts

### Notes

* CSV files are now being treated as the source of truth for card data.
* Google Sheets can be used as the editing workspace, but exported CSV files should be committed to GitHub for version history.
* The increase to 5 Adventure turns and 5 Town actions is intentional. The current prototype is testing a larger, more substantial round structure within the 3-round game.
* The Adventure system is moving towards hidden encounters: players interact with Mystery Tokens on the board, then reveal the next card from one shared Adventure Deck.
* Monster, Quest, Trap, and Discovery cards are intended to work differently while still fitting within the same Adventure phase structure.
* Markdown files should explain rules and design intent, while CSV files should hold actual card entries.

---

## Changelog Format for Future Updates

Use this format when adding future versions:

```markdown
## Version X.X – DD/MM/YY

### Added

- New features, rules, systems, cards, components, or sections.

### Changed

- Updates to existing rules, structures, wording, systems, or assumptions.

### Removed

- Features, rules, systems, cards, or assumptions that have been removed.

### Fixed

- Clarifications or corrections to confusing, broken, or contradictory rules.

### Notes

- Any extra design reasoning, playtest findings, or context worth keeping.
```

---

## Version Numbering Guide

Use simple version numbers while the game is still in design.

### Major versions

Use a major version when the game structure changes significantly.

Example:

* `1.0` – First playable ruleset
* `2.0` – Major redesign after playtesting

### Minor versions

Use a minor version when a meaningful system changes.

Example:

* `0.2` – Adventure phase redesigned
* `0.3` – Selling Cards reworked
* `0.4` – Shop upgrades added

### Patch versions

Use a patch version for smaller edits, clarifications, or wording updates.

Example:

* `0.1.1` – Clarified Town action wording
* `0.1.2` – Updated component names
* `0.1.3` – Fixed inconsistent terminology

```
```
