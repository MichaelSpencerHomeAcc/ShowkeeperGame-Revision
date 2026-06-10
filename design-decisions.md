# Design Decisions

This file records confirmed design decisions for the Shopkeeper Showdown revision.

The purpose of this document is to explain not just **what** changed, but **why** the decision was made. This should help keep the design consistent as the game develops.

---

# Decision Log

## Decision 001 – Use Three Main Game Phases

**Date:** 10/06/26
**Version:** 0.1
**Status:** Confirmed

### Decision

The game will use three main gameplay phases:

1. Adventure
2. Town
3. Selling

Cleanup exists as a procedural step at the end of each round, but the main player-facing structure is Adventure, Town, and Selling.

### Reason

This gives the game a clearer fantasy loop:

> Go out into danger, bring back opportunities, prepare your shop, then make profit.

Each phase has a different purpose:

* Adventure creates risk, discovery, quests, monsters, and resource rewards.
* Town creates preparation, training, crafting, upgrading, and specialisation.
* Selling creates payoff, coins, reputation, and completed deals.

### Impact

This becomes the core structure for all future rules, cards, boards, and player actions.

---

## Decision 002 – Set the Game Length at 3 Rounds

**Date:** 10/06/26
**Version:** 0.1
**Status:** Confirmed

### Decision

The game currently lasts 3 rounds.

Each round should feel like a larger chapter of play rather than a short repeated cycle.

The intended round feel is:

* Round 1: Establish
* Round 2: Specialise
* Round 3: Cash Out

### Reason

A 3-round structure creates a tighter experience and gives the game a clearer arc. It also makes each phase feel more important, because players have fewer chances to gather, prepare, and sell.

### Impact

Progression needs to be faster than in a longer game.

Training, shop upgrades, resource gathering, and Selling Cards should all matter quickly. Players should not need several rounds before their strategy starts working.

---

## Decision 003 – Increase Phase Actions to Support 3 Rounds

**Date:** 10/06/26
**Version:** 0.1
**Status:** Confirmed

### Decision

Because the game only lasts 3 rounds, each player currently gets:

* 3 Adventure turns per round
* 4 Town actions per round
* Up to 2 completed Selling Cards per Selling phase

Across the full game, this gives each player:

* 9 Adventure turns
* 12 Town actions
* Up to 6 standard Selling Card completions

### Reason

A shorter 3-round game needs enough actions for players to actually build towards a strategy.

The increased action economy should allow players to explore, gather resources, train, craft, upgrade, and sell without the game feeling too short.

### Impact

Each individual turn within a phase needs to stay quick to keep downtime low.

The game should avoid long, all-in-one player turns. Players should act one at a time within each phase, then pass to the next player.

---

## Decision 004 – Treat Selling Cards as the Main Selling System

**Date:** 10/06/26
**Version:** 0.1
**Status:** Working Decision

### Decision

Selling Cards are currently the main system for the Selling phase.

Players complete Selling Cards by spending the required resources or goods and gaining the listed rewards.

Possible Selling Card types include:

* Visitor Requests
* Craft Requests
* Business Orders
* Hero Orders
* Black Market Deals
* Alchemy Orders
* Luxury Commissions

### Reason

This gives the selling phase more variety than relying on one shared Visitor system.

Selling Cards allow different shopkeeper fantasies to exist at the same time. One player might fulfil craft requests, another might complete black-market deals, and another might focus on bulk orders or hero commissions.

### Impact

The Selling phase should be built around completing cards rather than only selling loose resources.

Selling Cards become one of the main ways players turn preparation into coins, reputation, and final scoring.

---

## Decision 005 – Treat Visitors as a Type of Selling Card

**Date:** 10/06/26
**Version:** 0.1
**Status:** Working Decision

### Decision

Visitors are currently treated as a type of Selling Card rather than a completely separate system.

A Visitor represents a customer who wants specific items, resources, crafted goods, or rare materials.

### Reason

This keeps the original customer/shopkeeper fantasy from Shopkeeper Showdown while simplifying the selling structure.

Instead of having both Visitors and Selling Cards as separate systems competing for attention, Visitors become one category within the broader Selling Card system.

### Impact

The game can still include customers and public demand, but the overall selling structure remains cleaner.

Future design work should decide how Visitors differ from other Selling Cards, such as Business Orders, Hero Orders, and Black Market Deals.

---

## Decision 006 – Build Around Distinct Shopkeeper Fantasies

**Date:** 10/06/26
**Version:** 0.1
**Status:** Confirmed

### Decision

The game should allow players to build towards different shopkeeper identities.

Current desired player fantasies include:

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

### Reason

The revised game should feel like more than resource collection and selling. Players should feel like they are developing their own shop, strategy, and identity.

### Impact

Adventurer skills, town locations, shop upgrades, resources, and Selling Cards should all support different routes through the game.

Future card and component design should be checked against these fantasies.

---

## Decision 007 – Use Short Turns Within Each Phase

**Date:** 10/06/26
**Version:** 0.1
**Status:** Confirmed

### Decision

Players should take short turns within each phase rather than completing a full round by themselves.

For example, during Adventure:

1. Player 1 takes one Adventure turn.
2. Player 2 takes one Adventure turn.
3. Player 3 takes one Adventure turn.
4. Continue until all players have taken their Adventure turns.

The same structure should apply to Town actions.

### Reason

This reduces downtime and keeps all players engaged.

It also supports more direct competition, because players can react to what others are doing within the same phase.

### Impact

Individual Adventure turns and Town actions need to resolve quickly.

Rules should avoid long chained actions unless they are rare, exciting, and clearly limited.

---

## Decision 008 – Make Adventure Rewards Feed Into Town and Selling

**Date:** 10/06/26
**Version:** 0.1
**Status:** Confirmed

### Decision

Adventure rewards should directly support later phases.

Possible Adventure rewards include:

* Basic resources
* Rare resources
* Monster parts
* Crafting materials
* Artifacts
* Coins
* Reputation
* Selling Cards
* Town bonuses
* Skill progress
* Special one-use items

### Reason

Adventure should not feel disconnected from the shopkeeping side of the game.

The purpose of adventuring is to bring back opportunities that help players prepare and profit.

### Impact

Quest, monster, and encounter design should always consider how the reward helps players during Town or Selling.

---

## Decision 009 – Town Phase Is the Main Specialisation Phase

**Date:** 10/06/26
**Version:** 0.1
**Status:** Confirmed

### Decision

The Town phase is where players prepare, specialise, and improve their shop.

Town actions may include:

* Training
* Crafting
* Visiting the Black Market
* Drawing or swapping Selling Cards
* Upgrading the shop
* Converting resources
* Gaining reputation
* Protecting the shop
* Laundering stolen goods
* Preparing for orders

### Reason

The revised game needs a clear space where players build towards a playstyle.

Adventure provides opportunities, but Town turns those opportunities into a plan.

### Impact

Town locations and actions should be designed to support different strategies.

Town actions should feel meaningful, especially because each player only has 12 standard Town actions across the full game.

---

## Decision 010 – Make Round 3 Feel Like a Final Cash-Out

**Date:** 10/06/26
**Version:** 0.1
**Status:** Confirmed

### Decision

Round 3 should feel like the final chance to convert resources, upgrades, and strategy into score.

The final Selling phase should be satisfying and may allow stronger sales, bigger contracts, or final cash-out opportunities.

### Reason

With only 3 rounds, the game needs a strong ending.

Players should feel that their earlier choices have built towards a final payoff.

### Impact

Future design should consider whether Round 3 has special rules, stronger Selling Cards, final contracts, or ways to convert leftover resources into points.

---

## Decision 011 – Use Four Main Item Types with Tags

**Date:** 10/06/26  
**Version:** 0.1  
**Status:** Confirmed  

### Decision

The game will keep four main item types:

1. Armament
2. Consumable
3. Trinket
4. Trade Good

Each item may also have one or more tags that define special qualities, uses, or restrictions.

Example tags include:

- Crafted
- Rare
- Magical
- Monster Part
- Artifact
- Black Market
- Luxury
- Contraband

### Reason

The four main item types keep the economy easy to understand, while tags add enough flexibility to support special orders, crafting, black-market deals, rare goods, and different shopkeeper strategies.

This avoids needing a large list of separate resource types while still allowing cards to feel flavourful and mechanically distinct.

### Impact

Selling Cards, quests, crafting, Black Market actions, and shop upgrades can refer to either item types, tags, or combinations of both.

Examples:

- Any 2 Consumables
- 1 Armament and 1 Trinket
- Any Stolen item
- 1 Crafted Armament
- 1 Rare Trinket
- Any 2 Monster Part items

---

# Future Decision Template

Use this template when adding new design decisions.

```markdown
## Decision XXX – [Decision Title]

**Date:** DD/MM/YY  
**Version:** X.X  
**Status:** Confirmed / Working Decision / Reversed  

### Decision

Describe the decision clearly.

### Reason

Explain why this decision was made.

### Impact

Explain what this changes or affects in the design.
```

