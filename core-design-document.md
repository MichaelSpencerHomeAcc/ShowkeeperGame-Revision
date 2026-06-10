# Shopkeeper Showdown – Core Design Document

## Document Status

**Version:** 0.2
**Status:** Working Draft
**Repository:** https://github.com/MichaelSpencerHomeAcc/ShowkeeperGame-Revision
**Last Updated:** 10/06/26
**Owner:** Michael Spencer / Amber Spencer

---

# 1. Game Vision

Shopkeeper Showdown is a competitive fantasy shopkeeping game where players send adventurers into dangerous locations, gather valuable resources, develop their shops, and complete profitable deals.

The game is built around three main phases:

1. Adventure
2. Town
3. Selling

Each phase gives players a different type of decision.

The **Adventure phase** creates risk, discovery, quests, monsters, and resource rewards.

The **Town phase** allows players to prepare, train, craft, upgrade, steal, and specialise their shop.

The **Selling phase** is the payoff, where players convert their preparation into coins, reputation, completed deals, and final scoring opportunities.

The aim is to create a game where each player can build towards a distinct fantasy. One player might become a master crafter, another might run a shady black-market operation, another might focus on fulfilling huge orders, and another might rely heavily on questing and adventurer skills.

---

# 2. Core Design Goals

The revised game should aim to:

* Create a stronger fantasy shopkeeper identity.
* Let players build towards different playstyles.
* Keep downtime low through short, repeated turns within each phase.
* Make each round feel meaningful.
* Make selling feel like the payoff for earlier decisions.
* Give players enough time to develop a strategy within a shorter 3-round structure.
* Support direct competition without making the game feel overly punishing.
* Let the board and available choices evolve as the game progresses.
* Make each player feel like they are building their own style of shop.

---

# 3. Desired Player Fantasies

Players should be able to build towards different identities across the game.

Possible player fantasies include:

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

These identities should emerge through a combination of adventurer skills, town actions, shop upgrades, gathered resources, and chosen selling cards.

---

# 4. Game Length

The game currently lasts **3 rounds**.

Because there are only 3 rounds, each round should feel more substantial than in a shorter action cycle. Players need enough turns within each phase to gather resources, make meaningful choices, build towards a strategy, and see that strategy pay off.

Each round should feel like a full chapter of play:

* **Round 1:** Establish
* **Round 2:** Specialise
* **Round 3:** Cash Out

---

# 5. Core Game Loop

Each round follows the same structure:

1. Adventure Phase
2. Town Phase
3. Selling Phase
4. Cleanup

The flow of the game is:

> Go out into danger, bring back opportunities, prepare your shop, then make profit.

Players should not be waiting for one player to take a long full turn. Instead, each phase is handled in smaller turns, with players acting one after another.

---

# 6. Round Overview

Each round currently gives every player:

* **3 Adventure turns**
* **4 Town actions**
* **Up to 2 completed Selling Cards**

Across the full game, before upgrades or special effects, this gives each player:

* **9 Adventure turns**
* **12 Town actions**
* **Up to 6 standard Selling Card completions**

Certain skills, upgrades, events, or card effects may increase these limits.

This structure should give players enough room to make progress without extending the game too far.

---

# 7. Phase One: Adventure

## Purpose

The Adventure phase creates risk, exploration, discovery, and resource gain.

This is where players send their adventurers out into dangerous areas to uncover quests, face monsters, gather materials, and find opportunities that will support their shop later in the round.

The Adventure phase should feel active, competitive, and quick. Players take short turns, then play passes to the next player.

---

## Adventure Phase Structure

At the start of the Adventure phase:

1. Refresh or reveal the active Adventure board.
2. Place quests, monsters, resources, or encounter markers.
3. Starting with the first player, players take Adventure turns one at a time.
4. Continue until each player has taken 3 Adventure turns.

---

## Adventure Turn Structure

On an Adventure turn, a player may:

1. Move their adventurer.
2. Reveal or interact with a space.
3. Resolve a quest, monster, resource, or event.
4. Roll dice or use an adventurer skill if required.
5. Gain rewards or suffer consequences.
6. Pass play to the next player.

---

## Adventure Board Concept

The Adventure board may be made up of distinct regions or dungeon-style areas.

Possible areas include:

* Forest
* Desert
* Ruins
* Caves
* Coast
* Swamp
* Mountain
* Ancient Dungeon

The board may open up or change over time, allowing later rounds to feel more dangerous or more rewarding.

The Adventure board should create the feeling that players are leaving town to seek opportunity, danger, and rare goods.

---

## Adventure Rewards

Adventure rewards should feed directly into the later phases of the round.

Possible rewards include:

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

Adventure should not feel disconnected from the shopkeeping side of the game. What players gain here should influence what they can do in Town and Selling.

---

# 8. Phase Two: Town

## Purpose

The Town phase lets players prepare, specialise, and improve their shop.

This is where the fantasy shopkeeper identity becomes clear. Players use town locations to train, craft, steal, upgrade, prepare, manipulate the market, or pursue specific selling strategies.

The Town phase should give players enough options to build towards different styles without becoming too slow or overwhelming.

---

## Town Phase Structure

At the start of the Town phase:

1. Reveal 1 Town Event.
2. Refresh town locations.
3. Starting with the first player, players take Town actions one at a time.
4. Continue until each player has taken 4 Town actions.

---

## Town Turn Structure

On a Town turn, a player chooses one available town location and takes one action there.

Possible Town actions include:

* Train your adventurer.
* Craft goods.
* Visit the Black Market.
* Draw or swap Selling Cards.
* Upgrade your shop.
* Convert resources.
* Gain reputation.
* Protect your shop.
* Launder stolen goods.
* Prepare for a specific order.

---

## Town Events

A Town Event is revealed at the start of each Town phase.

Town Events create variety between rounds and stop the game from feeling too scripted.

Town Events may affect:

* Resource prices
* Selling rewards
* Black Market risk
* Crafting bonuses
* Available town locations
* Reputation gains
* Player interaction
* Taxes, fines, guards, or market demand

Town Events should generally last for the current round only, then clear during Cleanup.

---

## Town Locations

The Town board contains locations that allow players to take specific actions.

Possible locations include:

| Location         | Possible Action                              |
| ---------------- | -------------------------------------------- |
| Training Grounds | Train your adventurer and unlock skills      |
| Workshop         | Craft resources into valuable goods          |
| Black Market     | Steal, launder, or make shady deals          |
| Alchemist        | Convert resources or create special goods    |
| Market Square    | Draw or swap Selling Cards                   |
| Guild Hall       | Take contracts or gain reputation            |
| Bank             | Gain coins, take loans, or protect valuables |
| Guard Post       | Protect your shop or expose stolen goods     |
| Warehouse        | Increase storage or manage inventory         |

Locations may have limited spaces, scaling costs, or other restrictions to create competition without completely blocking players from participating.

---

## Training

Training allows players to improve their adventurer.

Training should unlock skills quickly enough to matter within a 3-round game.

Adventurer skills may improve:

* Movement
* Combat
* Quest success
* Resource gathering
* Crafting support
* Stealing
* Selling
* Reputation gain
* Player interaction

Training should help a player define their strategy rather than simply act as a small bonus.

---

## Shop Upgrades

Shop upgrades allow players to improve their shop and specialise their playstyle.

Possible shop upgrades include:

* Extra storage
* Better crafting tools
* Hidden compartments
* Improved display windows
* Alchemy bench
* Security system
* Reputation displays
* Black Market access
* Order desk
* Premium goods shelf

Because the game lasts only 3 rounds, shop upgrades should either give an immediate benefit or become useful by the next phase or next round.

---

## Black Market

The Black Market should support a more aggressive or risky playstyle.

Black Market actions may allow players to:

* Steal goods
* Gain illegal resources
* Launder stolen goods
* Complete shady deals
* Hide contraband
* Sabotage opponents
* Access high-value Selling Cards

Black Market play should be powerful, but it should carry some form of risk, cost, or exposure.

---

# 9. Phase Three: Selling

## Purpose

The Selling phase is where players convert their preparation into profit and scoring.

This is the payoff for the round. Players use the resources, crafted goods, upgrades, stolen items, and selling opportunities they prepared during Adventure and Town.

Selling should feel satisfying, but limited enough that decisions matter.

---

## Selling Phase Structure

During the Selling phase, players complete Selling Cards by spending the required resources or goods and gaining the listed rewards.

Each player may currently complete **up to 2 Selling Cards per Selling phase**.

Certain effects may increase this limit, such as:

* Shop upgrades
* Reputation bonuses
* Adventurer skills
* Town Event effects
* Specific Selling Card rewards

---

## Completing a Selling Card

To complete a Selling Card:

1. Choose a Selling Card you are eligible to complete.
2. Spend the required resources or goods.
3. Gain the listed rewards.
4. Place the completed card in your completed sales area.
5. Discard, replace, or refresh cards as instructed.

---

## Selling Cards

Selling Cards are currently the main selling system.

They represent different ways players can make money and score points.

Possible Selling Card types include:

* Visitor Requests
* Craft Requests
* Business Orders
* Hero Orders
* Black Market Deals
* Alchemy Orders
* Luxury Commissions

---

## Visitors

Visitors are currently treated as a type of Selling Card rather than a completely separate system.

A Visitor represents a customer who wants a specific type of item or set of items.

Visitors may be:

* Public
* Private
* Short-term
* High-value
* Reputation-based
* Linked to specific resources or crafted goods

This keeps the selling system flexible while preserving the original visitor/customer fantasy from Shopkeeper Showdown.

---

## Selling Card Examples

Possible selling opportunities include:

* A citizen wants a simple crafted item.
* A hero needs equipment before leaving town.
* A business needs a large bulk order fulfilled.
* A noble wants a rare luxury item.
* A shady contact wants stolen goods.
* An alchemist needs strange monster parts.
* A traveller wants supplies from a dangerous region.
* A collector wants an artifact.

---

# 10. Cleanup

## Purpose

Cleanup resets temporary effects and prepares the next round.

Cleanup should be quick and mostly procedural.

---

## Cleanup Structure

At the end of each round:

1. Clear temporary effects.
2. Discard expired cards.
3. Refill Adventure, Town, and Selling markets as needed.
4. Refresh town locations.
5. Rotate the first player marker.
6. Advance the round tracker.
7. Check for game end.

The game ends after the Selling phase of Round 3, followed by final scoring.

---

# 11. Player Components

Each player currently needs:

* 1 Adventurer card
* 1 Shop board
* Player marker or adventurer meeple
* Inventory or storage spaces
* Coin tracker or coin tokens
* Reputation tracker or tokens
* Skill markers
* Completed Selling Card area
* Shop upgrade slots
* Possible hidden storage or Black Market storage

---

# 12. Shared Components

The shared game currently needs:

* Adventure board or adventure tiles
* Town board
* Selling card market
* Round tracker
* First player marker
* Dice
* Resource cards or tokens
* Quest cards
* Monster cards
* Town Event cards
* Selling Cards
* Upgrade cards
* Black Market cards or tokens

---

# 13. Card Type Definitions

## Adventure Cards

Cards used during the Adventure phase.

Adventure Cards may include:

* Quests
* Monsters
* Hazards
* Treasures
* Resource discoveries
* Strange events
* Region-specific encounters

---

## Quest Cards

Quest Cards are adventure objectives that players can complete for rewards.

Quests may require:

* Movement
* Dice checks
* Resources
* Combat
* Specific adventurer skills
* Visiting certain spaces
* Taking risks

Quest rewards should help players prepare for Town or Selling.

---

## Monster Cards

Monster Cards are threats that players can fight during Adventure.

Defeating monsters may reward:

* Coins
* Reputation
* Monster parts
* Rare resources
* Selling Cards
* Artifacts
* Special bonuses

Monsters should create risk and give combat-focused adventurers a reason to exist.

---

## Town Event Cards

Town Event Cards are global events that affect the Town phase for one round.

They may change prices, risks, rewards, available actions, or market behaviour.

---

## Selling Cards

Selling Cards are completed during the Selling phase.

They represent customers, commissions, contracts, visitors, shady deals, and other sales opportunities.

Selling Cards are one of the main ways players convert their preparation into points, coins, reputation, or other rewards.

---

## Upgrade Cards

Upgrade Cards or tiles permanently improve a player’s shop or adventurer.

Upgrades should support specialisation and help players build towards a distinct playstyle.

---

# 14. Resources

Resources are the goods players gather, craft, trade, steal, and sell.

The exact resource list is still to be defined, but resources should support multiple playstyles.

Possible resource categories include:

* Common goods
* Crafted goods
* Rare goods
* Monster parts
* Magical materials
* Stolen goods
* Artifacts
* Alchemical ingredients

Resources should be useful across multiple systems, including quests, crafting, upgrades, and selling.

---

# 15. Scoring

The player with the highest final score after 3 rounds wins.

Potential scoring sources include:

* Coins
* Reputation
* Completed Selling Cards
* Shop upgrades
* Rare resources
* Adventure achievements
* Artifacts
* End-game bonuses

Selling should remain one of the main ways to score, but players should be able to reach strong scores through different strategies.

---

# 16. Three-Round Balance Principles

Because the game only lasts 3 rounds, the design needs faster progression.

Important balance principles:

* Players should gain useful resources from the first Adventure phase.
* Players should be able to complete at least one meaningful sale in Round 1.
* Training should unlock abilities quickly enough to matter.
* Shop upgrades should provide value immediately or by the next round.
* Selling Cards should not require too much setup unless the reward is very high.
* Players should not need several rounds before their strategy starts working.
* Round 3 should create opportunities for a satisfying final cash-out.

---

# 17. Suggested Round Feel

## Round 1: Establish

Players gather starting resources, take early quests, train or craft, and complete smaller sales.

Round 1 should help players understand their options and begin shaping their strategy.

---

## Round 2: Specialise

Players lean into their chosen strategy, unlock stronger skills, complete better sales, and begin competing more directly.

Round 2 should be where player identities become more visible.

---

## Round 3: Cash Out

Players make their biggest deals, complete final contracts, use powerful upgrades, and convert everything into final score.

Round 3 should feel like the final opportunity to make profit, fulfil key orders, and complete a chosen strategy.

---

# 18. Design Decisions Log

| Date     | Decision                                                                    | Reason                                                                      |
| -------- | --------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| 10/06/26 | Game uses three main phases: Adventure, Town, and Selling.                  | Creates a clear and repeatable structure.                                   |
| 10/06/26 | Game length is currently 3 rounds.                                          | Creates a tighter experience with bigger, more meaningful rounds.           |
| 10/06/26 | Each player takes 3 Adventure turns per round.                              | Gives players enough exploration in a shorter game.                         |
| 10/06/26 | Each player takes 4 Town actions per round.                                 | Gives players enough room to build a strategy before the game ends.         |
| 10/06/26 | Selling Cards are being explored as the main selling system.                | Allows more variety than relying on a single Visitor system.                |
| 10/06/26 | Visitors are currently treated as a type of Selling Card.                   | Keeps the customer fantasy while simplifying the overall selling structure. |
| 10/06/26 | Each player can currently complete up to 2 Selling Cards per Selling phase. | Gives selling a clear limit while still allowing meaningful payoff.         |

---

# 19. Changelog

## Version 0.1

### Added

* Created first structured version of the Core Design Document.
* Defined the core phase loop: Adventure, Town, Selling, Cleanup.
* Added initial player fantasies.
* Added early component lists.
* Added first phase summaries.

---

## Version 0.2

### Changed

* Changed assumed game length from 5 rounds to 3 rounds.
* Increased Adventure turns to 3 per player per round.
* Increased Town actions to 4 per player per round.
* Added the assumption that players may complete up to 2 Selling Cards per Selling phase.
* Reframed each round as a larger chapter of play rather than a smaller cycle.

### Added

* Added three-round balance principles.
* Added suggested round feel: Establish, Specialise, Cash Out.
* Added clearer Selling Card categories.
* Added Visitors as a type of Selling Card.
* Added more detail around Town locations, Training, Shop Upgrades, and the Black Market.

### Removed

* Removed open questions from the main design document so they can be handled separately as design discussions.
