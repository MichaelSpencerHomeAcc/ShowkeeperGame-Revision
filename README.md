# Shopkeeper Showdown Revision

This repository contains the working design documents for the revised version of **Shopkeeper Showdown**.

The purpose of this repo is to keep the game design organised, versioned, and easy to update as the rules evolve.

---

## Current Design Version

**Version:** 0.1
**Status:** Working Draft
**Core Loop:** Adventure → Town → Selling
**Current Game Length:** 3 rounds

---

## Game Overview

Shopkeeper Showdown is a competitive fantasy shopkeeping game where players send adventurers into dangerous locations, gather valuable resources, develop their shops, and complete profitable deals.

Each round is split into three main phases:

1. **Adventure** – explore dangerous areas, uncover quests, face monsters, and gather resources.
2. **Town** – train, craft, upgrade, steal, prepare, and specialise your shop.
3. **Selling** – complete selling cards, fulfil deals, and convert preparation into coins, reputation, and score.

Cleanup happens at the end of each round as a procedural step.

---

## Design Goals

The revised game aims to:

* Create a stronger fantasy shopkeeper identity.
* Let players build towards different playstyles.
* Keep downtime low through short, repeated turns within each phase.
* Make each round feel meaningful within a 3-round structure.
* Make selling feel like the payoff for earlier decisions.
* Support direct competition without making the game feel overly punishing.
* Let players develop their own style of shop.

---

## Current Round Structure

The game currently lasts **3 rounds**.

Each round gives every player:

* **3 Adventure turns**
* **4 Town actions**
* **Up to 2 completed Selling Cards**

Across the full game, before upgrades or special effects, each player has:

* **9 Adventure turns**
* **12 Town actions**
* **Up to 6 standard Selling Card completions**

---

## Desired Player Fantasies

The design should support different shopkeeper identities, including:

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

---

## Repository Structure

```text
ShowkeeperGame-Revision/
│
├── README.md
├── core-design-document.md
├── CHANGELOG.md
├── design-decisions.md
│
├── rules/
│   ├── rules-skeleton.md
│   ├── setup.md
│   ├── round-structure.md
│   ├── scoring.md
│   └── glossary.md
│
├── phases/
│   ├── adventure-phase.md
│   ├── town-phase.md
│   ├── selling-phase.md
│   └── cleanup.md
│
├── components/
│   ├── card-types.md
│   ├── resources.md
│   ├── player-boards.md
│   ├── adventure-board.md
│   ├── town-board.md
│   └── tokens-and-trackers.md
│
├── cards/
│   ├── adventure-cards.md
│   ├── quest-cards.md
│   ├── monster-cards.md
│   ├── town-event-cards.md
│   ├── selling-cards.md
│   ├── upgrade-cards.md
│   └── example-cards.md
│
├── playtesting/
│   ├── playtest-template.md
│   ├── balance-notes.md
│   └── session-notes/
│       └── playtest-001.md
│
├── design-notes/
│   ├── open-questions.md
│   ├── discarded-ideas.md
│   └── future-ideas.md
│
└── assets/
    ├── sketches/
    ├── board-drafts/
    └── card-drafts/
```

---

## Key Documents

### `core-design-document.md`

The main design document for the current version of the game.

This should contain the current agreed direction, core systems, phase structure, player components, card types, and scoring assumptions.

---

### `CHANGELOG.md`

Tracks all notable changes to the design.

Use this whenever the game changes in a meaningful way.

---

### `design-decisions.md`

Records confirmed design decisions and the reasons behind them.

This is useful for remembering why a system was chosen, especially after several rounds of changes.

---

### `design-notes/open-questions.md`

Tracks unresolved questions that still need to be answered.

Once an answer becomes a confirmed design decision, it should be moved into `design-decisions.md`.

---

## Versioning

The project uses simple design versioning.

### Current Version

`0.1` is the first structured working draft.

### Future Versions

Use minor versions for meaningful design changes:

* `0.2` – Adventure phase redesigned
* `0.3` – Selling Cards reworked
* `0.4` – Shop upgrades added
* `0.5` – First playable prototype ruleset

Use patch versions for smaller edits:

* `0.1.1` – Clarified wording
* `0.1.2` – Updated terminology
* `0.1.3` – Fixed contradictions

---

## Changelog Rules

When making a meaningful change:

1. Update the relevant design document.
2. Add the change to `CHANGELOG.md`.
3. Add a decision to `design-decisions.md` if the change confirms a design direction.
4. Move any answered questions out of `open-questions.md`.

---

## Current Working Assumptions

* The game lasts 3 rounds.
* The main phase loop is Adventure → Town → Selling.
* Cleanup happens after Selling.
* Each player has an adventurer and a shop.
* Adventure rewards should feed into Town and Selling.
* Town is the main specialisation phase.
* Selling Cards are the main selling system.
* Visitors are currently treated as a type of Selling Card.
* Players can complete up to 2 Selling Cards per Selling phase by default.

---

## Development Notes

This repository is currently for design documentation only.

The priority is to define the bare-bones skeleton of the revised game before creating a full rulebook, prototype files, final cards, or production-ready assets.

The design should stay flexible while the core systems are being tested.
