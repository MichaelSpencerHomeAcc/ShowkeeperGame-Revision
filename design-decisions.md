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

## Decision 012 – Use One Adventure Deck and Mystery Tokens

**Date:** 10/06/26  
**Version:** 0.1.1  
**Status:** Confirmed  

### Decision

The Adventure phase will use one shared Adventure Deck.

All Adventure cards have the same generic card back. The card type is not visible before the card is revealed.

Adventure points on the board are represented by Mystery Tokens. When a player reaches and interacts with a Mystery Token, they remove that token and reveal the top card of the Adventure Deck.

The revealed card may be one of four Adventure Card types:

- Monster
- Quest
- Trap
- Discovery

### Reason

This keeps Adventure unpredictable and prevents players from avoiding specific card types before they are revealed.

Players know there is something worth exploring on the board, but they do not know exactly what they will encounter until they commit to the interaction.

This supports the feeling of exploration, risk, and discovery.

### Impact

Adventure cards should be designed as one mixed deck rather than separate decks by type.

Adventure tokens on the board should be generic Mystery Tokens, not type-specific tokens.

Card backs should not reveal whether a card is a Monster, Quest, Trap, or Discovery.

---

## Decision 013 – Define Four Distinct Adventure Card Behaviours

**Date:** 10/06/26  
**Version:** 0.1.1  
**Status:** Confirmed  

### Decision

Adventure Cards use four main types:

- Monster
- Quest
- Trap
- Discovery

Each type has a distinct mechanical identity.

Monsters are about speed. They have HP and armour, and players try to defeat them within 1, 2, or 3 attempts. Faster defeats give better rewards. If the Monster survives a combat roll, it retaliates, usually causing the player to lose cards, resources, or coins.

Quests use a straight roll for success level. The player gains a reward based on the highest threshold reached. If the player fails to reach the first threshold, they gain no reward. Quests usually do not retaliate.

Traps use a straight roll to avoid, disarm, or overcome danger. If the player fails, the Trap effect triggers. Trap effects usually reduce tempo, such as losing dice bonuses, movement, speed, or weakening a future roll.

Discoveries use a straight roll to determine reward quality. Discoveries always give a reward, even if the player fails to reach the first threshold. Higher results give better rewards.

### Reason

This keeps the Adventure system easy to understand while making each card type feel different.

Each type creates a different kind of tension:

- Monster = defeat it quickly or suffer retaliation.
- Quest = succeed for rewards, fail for nothing.
- Trap = avoid danger or lose tempo.
- Discovery = always gain something, but better rolls find better rewards.

### Impact

Adventure Cards should be designed around their type identity.

Monster cards need HP, armour, rewards based on defeat speed, and retaliation effects.

Quest cards need three success thresholds and no failure reward.

Trap cards need three success thresholds and a trap effect for failure.

Discovery cards need three success thresholds and a fallback reward for failure.

---

## Decision 014 – Increase Phase Actions for the First Prototype

**Date:** 10/06/26  
**Version:** 0.1.1  
**Status:** Confirmed  

### Decision

The first prototype will use a larger action economy than the original 0.1 assumption.

Each player currently receives:

- 5 Adventure turns per round
- 5 Town actions per round

The game still lasts 3 rounds.

### Reason

Because the game only lasts 3 rounds, each round needs to feel substantial. Increasing the number of Adventure and Town actions gives players more room to explore, gather resources, train, craft, upgrade, interact with the board, and build towards a selling strategy.

### Impact

The Core Design Document should be updated to replace the earlier assumption of 3 Adventure turns and 4 Town actions.

The Rules Skeleton is now the current source for the first prototype action economy.

This action count may need playtesting to check pacing, downtime, and total game length.

---

## Decision 015 – Confirm First Prototype Setup

**Date:** 10/06/26  
**Version:** 0.1.2  
**Status:** Confirmed  

### Decision

The first playable prototype setup is confirmed.

Each player starts with:

- 20 coins
- 0 reputation
- 0 training
- 1d6 adventurer dice
- 3 Resource Cards, kept from 5 dealt
- 2 private Selling Cards, kept from 3 dealt
- 0 shop upgrades

The shared setup includes:

- 1 public Visitor card
- 2 Mystery Tokens per player on the Adventure board
- Round tracker set to Round 1
- Randomly chosen first player

### Reason

This setup gives players enough starting money to interact with Town actions and recover from early setbacks, while the resource and Selling Card drafts provide early direction.

Using 1 public Visitor keeps the shared customer focus from the original game without overwhelming the table with too many public selling opportunities.

### Impact

The setup rules are now stable enough for the first playable prototype.

Future testing should check whether:

- 20 starting coins is too generous or too restrictive.
- 2 Mystery Tokens per player is enough for 5 Adventure turns.
- Starting with 3 Resource Cards and 2 private Selling Cards gives players enough early direction.

---

## Decision 016 – Use a 10x8 Forest Adventure Board with Refilled Mystery Tokens

**Date:** 10/06/26
**Version:** 0.1.2
**Status:** Confirmed

### Decision

The first playable prototype will use a 10x8 Adventure board.

The current Adventure map is the Forest.

Mystery Tokens are placed on the board to represent unknown Adventure encounters. At the start of each Adventure Phase, place 2 Mystery Tokens per player on empty valid spaces.

Whenever a Mystery Token is removed, immediately place a new Mystery Token on an empty valid space.

Players currently move up to 4 spaces on an Adventure turn.

If a player moves onto a space containing a Mystery Token, they may pause their movement to interact with it. After resolving the revealed Adventure Card, the player may continue moving if they have movement remaining.

A player may only interact with one Mystery Token per Adventure turn unless a card, skill, or boon says otherwise.

### Reason

A 10x8 board gives the Adventure phase more room to breathe, especially with 5 Adventure turns per player each round.

Starting with only the Forest map keeps the first prototype focused while leaving room for future maps or regions.

Allowing players to interact mid-movement and then continue moving makes Adventure turns feel smoother and less punishing.

Refilling Mystery Tokens keeps the Adventure board active throughout the phase.

### Impact

The Adventure phase now has a clearer prototype board structure.

Future testing should check:

* Whether 10x8 is too large or too spacious.
* Whether 2 Mystery Tokens per player is enough.
* Whether refilling Mystery Tokens keeps the board active.
* Whether allowing movement after interaction creates good flow or too much efficiency.
* Whether limiting players to one Mystery Token interaction per turn feels right.

---

## Decision 017 – Define Prototype Adventurer Dice and Training

**Date:** 10/06/26  
**Version:** 0.1.2  
**Status:** Confirmed  

### Decision

For the first playable prototype, all adventurers use the same basic dice progression.

Each adventurer starts with:

- 1d6 adventurer dice
- +1 to Adventure rolls
- 0 training

Training increases the number of dice rolled:

- 0 Training = roll 1d6 + 1
- 2 Training = roll 2d6 + 1
- 4 Training = roll 3d6 + 1

The flat +1 roll bonus does not increase through training.

In future versions, adventurer-specific boons will become unique skills that differ between adventurers. Gear may be used to improve the flat roll bonus.

### Reason

The first prototype needs a simple adventurer system that supports Adventure Card thresholds without adding too much character complexity too early.

Training should make adventurers stronger quickly enough to matter in a 3-round game.

Keeping the flat +1 separate from training creates a clean distinction between adventurer experience and adventurer gear.

### Impact

Adventure Cards should be balanced around players starting at 1d6 + 1 and potentially reaching 2d6 + 1 or 3d6 + 1 through training.

Town rules should include a Training action that increases training progress.

Future adventurer design can replace generic boons with unique adventurer skills.

---

## Decision 017 – Define Prototype Adventurer Dice and Training

**Date:** 10/06/26
**Version:** 0.1.2
**Status:** Confirmed

### Decision

For the first playable prototype, all adventurers use the same basic dice progression.

Each adventurer starts with:

* 1d6 adventurer dice
* +1 to Adventure rolls
* 0 training
* No unique skills

Training increases the number of dice rolled:

| Training Level | Adventure Roll |
| -------------: | -------------- |
|   0–1 Training | 1d6 + 1        |
|   2–3 Training | 2d6 + 1        |
|    4+ Training | 3d6 + 1        |

The flat +1 roll bonus does not increase through training.

In future versions, adventurer-specific boons will become unique skills that differ between adventurers. Gear may be used to improve the flat roll bonus.

### Reason

The first prototype needs a simple adventurer system that supports Adventure Card thresholds without adding too much character complexity too early.

Training should make adventurers stronger quickly enough to matter in a 3-round game.

Keeping the flat +1 separate from training creates a clean distinction between adventurer experience and adventurer gear:

* Training improves dice.
* Gear improves the flat bonus.
* Skills provide unique adventurer effects.

### Impact

Adventure Cards should be balanced around players starting at 1d6 + 1 and potentially reaching 2d6 + 1 or 3d6 + 1 through training.

Town rules should include a Training action that increases training progress.

Future adventurer design can replace generic boons with unique adventurer skills.

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

