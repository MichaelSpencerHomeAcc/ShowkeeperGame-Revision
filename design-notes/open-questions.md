# Open Questions

This file tracks unresolved design questions for the Shopkeeper Showdown revision.

When a question is answered and becomes a confirmed design direction, move the answer into `design-decisions.md` and update the relevant rules or design document.

---

# How to Use This File

Each question should have:

* A clear question
* Why it matters
* Current thinking, if there is any
* Status

Possible statuses:

* **Open**
* **In Discussion**
* **Needs Playtesting**
* **Answered**
* **Deferred**

---

# 1. Core Game Structure

## Q001 – What is the main player identity?

**Question:**
Are players primarily shopkeepers, adventurers, or shopkeepers who control adventurers?

**Why it matters:**
This affects the language of the game, player boards, character cards, upgrades, and the overall fantasy.

**Current thinking:**
Players are shopkeepers who control adventurers. The shopkeeper is the main identity, while the adventurer is how players access quests, danger, and resources.

**Status:** In Discussion

---

## Q002 – Should Cleanup be presented as a full phase?

**Question:**
Should Cleanup be described as a fourth phase, or should it simply be a procedural step at the end of each round?

**Why it matters:**
The design currently talks about three main phases: Adventure, Town, and Selling. Cleanup is mechanically needed, but it may not need to feel like a player-facing phase.

**Current thinking:**
Cleanup should be procedural, not a main phase.

**Status:** In Discussion

---

## Q003 – Is 3 rounds the final game length?

**Question:**
Is the game definitely 3 rounds, or is this only the current test structure?

**Why it matters:**
Round count affects pacing, action economy, upgrade strength, selling limits, and scoring.

**Current thinking:**
Current version is built around 3 rounds, with each round feeling like a larger chapter of play.

**Status:** Needs Playtesting

---

# 2. Player Components

## Q004 – What does each player start with?

**Question:**
What are the exact starting components for each player?

Possible starting components:

* 1 Adventurer card
* 1 Shop board
* Starting resources
* Starting coins
* Starting Selling Cards
* Starting skill
* Starting shop upgrade
* Player marker

**Why it matters:**
Starting setup defines how quickly players can engage with Adventure, Town, and Selling.

**Current thinking:**
Each player should start with an adventurer, a shop board, a small inventory, and at least one Selling Card.

**Status:** Open

---

## Q005 – Do players have unique adventurers?

**Question:**
Does each player choose a unique adventurer with different skills and progression options?

**Why it matters:**
Unique adventurers create asymmetry and replayability, but add complexity.

**Current thinking:**
Likely yes. Adventurers should help support different playstyles.

**Status:** Open

---

## Q006 – Do players have unique shop boards?

**Question:**
Are all shop boards identical, or does each player/shop have a unique ability or layout?

**Why it matters:**
This affects player asymmetry and how much identity comes from the shop versus the adventurer.

**Current thinking:**
Start with identical shop boards, then let players specialise through upgrades.

**Status:** Open

---

# 3. Adventure Phase

## Q007 – What type of board does the Adventure phase use?

**Question:**
Is the Adventure board grid-based, path-based, modular, card-based, or made from region tiles?

**Why it matters:**
This defines movement, exploration, quest placement, and player interaction.

**Current thinking:**
The current concept suggests an adventure board with distinct regions such as forest, desert, and ruins.

**Status:** Open

---

## Q008 – How does movement work?

**Question:**
How far can an adventurer move on an Adventure turn?

**Why it matters:**
Movement determines how quickly players can reach quests, monsters, and resources.

**Current thinking:**
Each Adventure turn could be: move up to a fixed number of spaces, then interact.

**Status:** Open

---

## Q009 – How are quests placed and revealed?

**Question:**
Are quests visible from the start, hidden until reached, or placed face-down as markers?

**Why it matters:**
This affects planning, risk, surprise, and competition.

**Current thinking:**
A mix may work: some public quests, some hidden encounters.

**Status:** Open

---

## Q010 – How is combat resolved?

**Question:**
When an adventurer encounters a monster, how do they fight it?

Possible options:

* Roll a die against a target number
* Compare adventurer stat vs monster stat
* Spend resources to boost the attempt
* Use skills to modify the result

**Why it matters:**
Combat needs to be quick enough not to slow down Adventure, but meaningful enough to support combat-focused characters.

**Current thinking:**
Use a simple dice check with ways to modify the result.

**Status:** Open

---

## Q011 – What happens when a player fails an Adventure check?

**Question:**
What are the consequences for failing quests, monsters, hazards, or exploration checks?

Possible consequences:

* Lose resources
* Lose coins
* Take injury
* Lose an Adventure turn
* Give another player an opportunity
* Monster remains
* Gain a smaller reward

**Why it matters:**
Failure needs to create risk without making players feel blocked.

**Current thinking:**
Failure should hurt, but should rarely mean “nothing happens.”

**Status:** Open

---

## Q012 – How much player interaction exists in Adventure?

**Question:**
Can players block, race, steal, sabotage, fight, or interfere with each other during Adventure?

**Why it matters:**
This affects how competitive and antagonistic the game feels.

**Current thinking:**
There should be some competition, but not enough to fully stop player progress.

**Status:** Open

---

# 4. Town Phase

## Q013 – How many Town locations are there?

**Question:**
What are the final Town locations on the Town board?

Current possible locations:

* Training Grounds
* Workshop
* Black Market
* Alchemist
* Market Square
* Guild Hall
* Bank
* Guard Post
* Warehouse

**Why it matters:**
Town locations define the main strategy options and action economy.

**Current thinking:**
Start with 6–8 core locations for the first prototype.

**Status:** Open

---

## Q014 – Can multiple players use the same Town location?

**Question:**
Are Town locations blocked after use, limited by spaces, or always available?

**Why it matters:**
This defines how competitive the Town phase feels.

**Current thinking:**
Limited spaces or increasing costs may be better than hard blocking.

**Status:** Open

---

## Q015 – How does training work?

**Question:**
What does a player gain when they train their adventurer?

Possible options:

* Unlock a skill
* Improve a stat
* Gain a one-use ability
* Advance on a training track
* Choose from a skill tree

**Why it matters:**
Training needs to matter within a 3-round game.

**Current thinking:**
Training should unlock abilities quickly, possibly after one or two training actions.

**Status:** Open

---

## Q016 – How do shop upgrades work?

**Question:**
How do players gain, place, and use shop upgrades?

Possible options:

* Buy from a shared market
* Craft using resources
* Unlock through Town actions
* Attach to shop board slots
* Draw from an upgrade deck

**Why it matters:**
Shop upgrades are likely one of the main ways players specialise.

**Current thinking:**
Upgrades should give immediate or next-phase value because the game only lasts 3 rounds.

**Status:** Open

---

## Q017 – How risky is the Black Market?

**Question:**
What risk does a player take when using Black Market actions?

Possible risks:

* Fines
* Guard exposure
* Reputation loss
* Contraband penalties
* Failed steal attempts
* Other players can report or expose them

**Why it matters:**
The Black Market should feel powerful and tempting, but not free.

**Current thinking:**
Black Market actions should offer strong rewards with clear risk.

**Status:** Open

---

# 5. Selling Phase

## Q018 – Are Selling Cards public, private, or both?

**Question:**
Do players hold private Selling Cards, complete cards from a shared market, or both?

**Why it matters:**
This defines planning, competition, and interaction in the Selling phase.

**Current thinking:**
A mix may work: players hold some private Selling Cards while also competing over public opportunities.

**Status:** Open

---

## Q019 – Are Visitors definitely a type of Selling Card?

**Question:**
Should Visitors remain folded into the Selling Card system, or should they return as a separate public customer system?

**Why it matters:**
This is one of the biggest structural decisions for Selling.

**Current thinking:**
Visitors are currently treated as a type of Selling Card.

**Status:** Needs Playtesting

---

## Q020 – Can players partially complete Selling Cards?

**Question:**
Can a player place resources onto a Selling Card over multiple rounds, or must they complete it all at once?

**Why it matters:**
Partial completion makes large orders possible, but adds tracking and reduces tension.

**Current thinking:**
Small and medium orders should likely be completed all at once. Larger business orders may allow partial completion.

**Status:** Open

---

## Q021 – How many Selling Cards can a player complete?

**Question:**
Is the default limit of 2 completed Selling Cards per Selling phase correct?

**Why it matters:**
This controls payoff, pacing, and how valuable preparation feels.

**Current thinking:**
Default is currently 2. Certain effects may increase this limit. Round 3 may need a larger cash-out.

**Status:** Needs Playtesting

---

## Q022 – Do Selling Cards expire?

**Question:**
Do uncompleted Selling Cards remain available, refresh every round, or expire after a set time?

**Why it matters:**
Expiration creates urgency but may frustrate planning.

**Current thinking:**
Some public cards may expire, while private cards may stay until completed or discarded.

**Status:** Open

---

## Q023 – Can players interfere during Selling?

**Question:**
Can players block, undercut, steal, expose, or sabotage another player’s sale?

**Why it matters:**
Selling is the payoff phase, so interaction here needs to be exciting but not miserable.

**Current thinking:**
Interference should exist, but probably be limited or telegraphed.

**Status:** Open

---

# 6. Resources and Economy

## Q024 – What are the core resources?

**Question:**
What resource types does the game use?

Possible categories:

* Common goods
* Crafted goods
* Rare goods
* Monster parts
* Magical materials
* Stolen goods
* Artifacts
* Alchemical ingredients

**Why it matters:**
Resources connect every part of the game: Adventure, Town, crafting, upgrading, and Selling.

**Current thinking:**
Start with a small set of flexible resource categories before adding complexity.

**Status:** Open

---

## Q025 – Are resources cards, tokens, or both?

**Question:**
Should resources be represented as cards, tokens, or a mix?

**Why it matters:**
This affects table space, hidden information, hand management, and production complexity.

**Current thinking:**
Tokens may be cleaner for common resources. Cards may be better for rare goods, artifacts, and special items.

**Status:** Open

---

## Q026 – Is there a storage limit?

**Question:**
How many resources or goods can each player keep?

**Why it matters:**
Storage limits make shop upgrades and planning more meaningful.

**Current thinking:**
Each shop board should likely have limited inventory/storage spaces.

**Status:** Open

---

# 7. Scoring

## Q027 – What is the final score made of?

**Question:**
What counts towards winning?

Possible scoring sources:

* Coins
* Reputation
* Completed Selling Cards
* Shop upgrades
* Rare resources
* Adventure achievements
* Artifacts
* End-game bonuses

**Why it matters:**
Scoring determines what players prioritise.

**Current thinking:**
Coins should matter most, but reputation and completed cards should also contribute.

**Status:** Open

---

## Q028 – How does reputation work?

**Question:**
Is reputation a scoring track, a currency, a multiplier, or a requirement for better Selling Cards?

**Why it matters:**
Reputation could become a major strategy path, but needs a clear purpose.

**Current thinking:**
Reputation should likely unlock better sales or provide end-game points.

**Status:** Open

---

## Q029 – How should leftover resources score?

**Question:**
Are unused resources worth anything at the end of the game?

**Why it matters:**
This affects whether players hoard or aggressively convert resources into sales.

**Current thinking:**
Most leftover resources should be worth little or nothing, unless they are rare goods or artifacts.

**Status:** Open

---

# 8. Interaction and Competition

## Q030 – How antagonistic should the game be?

**Question:**
How much should players be able to directly harm or disrupt each other?

**Why it matters:**
The original game had stealing, clashing, and antagonistic powers. The revision needs to decide how much of that identity stays.

**Current thinking:**
The game should remain competitive and cheeky, but not so punishing that players lose their whole plan.

**Status:** Open

---

## Q031 – Is stealing still a core mechanic?

**Question:**
Can players steal resources, cards, coins, or completed goods from each other?

**Why it matters:**
Stealing supports the thief/black-market fantasy, but can feel frustrating if overused.

**Current thinking:**
Stealing should exist, but likely needs limits, protection, or risk.

**Status:** Open

---

## Q032 – How can players protect themselves?

**Question:**
What protection options exist against stealing, sabotage, or Black Market effects?

Possible options:

* Guard Post
* Shop upgrades
* Reputation effects
* Security tokens
* Hidden storage
* Insurance
* Adventurer skills

**Why it matters:**
If the game allows interference, players need ways to defend themselves.

**Current thinking:**
Protection should be available through Town actions and shop upgrades.

**Status:** Open

---

# 9. Prototype Priorities

## Q033 – What is the minimum playable prototype?

**Question:**
What components and rules are needed for the first playable test?

**Why it matters:**
The game should be tested with the smallest possible version before too many systems are added.

**Current thinking:**
The minimum prototype likely needs:

* 3 rounds
* Basic Adventure board
* 4–6 Town locations
* Small resource set
* Basic Selling Cards
* Simple scoring
* 2–4 adventurers
* Basic shop boards

**Status:** Open

---

## Q034 – Which systems should be tested first?

**Question:**
Should the first test focus on the full game loop, or one phase at a time?

**Why it matters:**
Testing too much at once can make it hard to identify what is working.

**Current thinking:**
Test the full Adventure → Town → Selling loop in a simplified form first.

**Status:** Open

---

## Q035 – What makes a successful first playtest?

**Question:**
What should the first playtest prove?

Possible success measures:

* The 3-phase loop makes sense.
* Players understand what they are trying to do.
* Players can complete at least one sale in Round 1.
* Different strategies start to emerge.
* Downtime feels manageable.
* Selling feels like a payoff.
* The game creates funny or exciting moments.

**Why it matters:**
Clear success criteria make playtesting more useful.

**Status:** Open
