# Selling Cards

This document defines the structure and purpose of Selling Cards in Shopkeeper Showdown.

Selling Cards are the main way players turn items into Coins, Reputation, and other rewards.

These rules are for Version 0.1.2 and are intentionally simple for the first playable prototype.

---

## 1. Purpose

Selling Cards give players clear goals for what their shop is trying to sell.

They create demand for different item types, tags, rarities, and combinations.

Selling Cards should reward players for:

* Collecting the right goods
* Planning around future sales
* Choosing useful Order piles
* Completing private Orders
* Using leftover items efficiently
* Building a shop identity

---

## 2. Selling Card Categories

Selling Cards are split into two broad categories:

* Private Orders
* Public Visitors

Private Orders are the main planned selling system.

Public Visitors are the fallback selling system for leftover goods.

---

## 3. Private Orders

Private Orders are Selling Cards placed in a player’s shop.

Each Private Order uses one Order slot.

Private Orders usually require the player to sell specific item types, tags, rarities, or combinations.

Example requirements:

```text
Sell any 2 Consumables.
```

```text
Sell 1 Armament and 1 Trinket.
```

```text
Sell any 1 Magical item.
```

```text
Sell 1 Rare Trinket.
```

When a player completes a Private Order, they gain the listed rewards and move the completed Order to their completed Orders pile.

---

## 4. Public Visitors

Public Visitors are shared buyers available to all players.

Public Visitors do not use Order slots.

Public Visitors are not completed like Private Orders.

Instead, they buy eligible leftover goods during the Selling Phase after players have completed any Private Orders they want to complete.

Public Visitors are intended to help players turn spare goods into Coins without replacing the main Private Order system.

---

## 5. Order Slots

Each player has a number of Order slots in their shop.

Order slots determine how many Private Orders a player may have available at once.

At the start of the game, each player has 3 Order slots.

The current prototype Order slot progression is:

| Round | Order Slots |
| ----: | ----------: |
|     1 |           3 |
|     2 |           4 |
|     3 |           5 |

A player cannot have more Private Orders available than their current number of Order slots.

---

## 6. Starting Private Orders

During setup, each player chooses 3 starting Private Orders from the available Private Order piles.

Players may choose which piles to draw from.

Example starting choices:

* 3 Visitor Orders
* 2 Craft Requests and 1 Hero Order
* 1 Business Order, 1 Luxury Commission, and 1 Black Market Deal

Each chosen Order is placed face up in that player’s shop.

These 3 Orders fill the player’s starting Order slots.

---

## 7. Private Order Piles

Private Orders may be separated into different piles by type.

Possible Private Order piles include:

* Visitor Orders
* Craft Requests
* Business Orders
* Hero Orders
* Black Market Deals
* Luxury Commissions

When a player draws a new Private Order, they may choose which available Order pile to draw from unless a rule or effect says otherwise.

This lets players shape their shop strategy throughout the game.

---

## 8. Completing Private Orders

During the Selling Phase, a player may complete any number of Private Orders they can fulfil.

To complete a Private Order:

1. Choose one of your Private Orders.
2. Pay or discard the required items.
3. Gain the listed rewards.
4. Resolve any effects on the Order.
5. Move the completed Order to your completed Orders pile.
6. Leave that Order slot empty until the refill step.

A player may complete Private Orders in any order.

A player is not required to complete an Order, even if they can.

Unless an Order says otherwise, items used to complete an Order are discarded.

---

## 9. Selling Card Anatomy

A Private Order should include:

| Field             | Purpose                                   |
| ----------------- | ----------------------------------------- |
| Card Name         | The name of the Order.                    |
| Selling Type      | The type of Order.                        |
| Requirements      | What must be sold to complete it.         |
| Reward Coins      | Coins gained when completed.              |
| Reward Reputation | Reputation gained when completed.         |
| Effect            | Any special effect.                       |
| Tags              | Optional design or mechanical tags.       |
| Status            | Prototype, testing, confirmed, or cut.    |
| Balance Notes     | Notes for playtesting and future changes. |

Example Private Order:

```text
Card Name: Knight’s Emergency Kit
Selling Type: Hero Order
Requirements: Sell 1 Armament and 1 Consumable
Reward Coins: 9
Reward Reputation: 1
Effect: None
```

---

## 10. Selling Requirements

Private Orders may care about item types, tags, rarities, values, or deck source.

Examples:

```text
Sell any 2 Trinkets.
```

```text
Sell any 3 Trade Goods.
```

```text
Sell 1 Rare item.
```

```text
Sell 1 Magical Consumable.
```

```text
Sell 1 Armament worth at least 6 Coins.
```

```text
Sell 1 Crafted Good.
```

Selling requirements should be clear enough that players can quickly check whether they can complete an Order.

---

## 11. Public Visitor Anatomy

A Public Visitor should include:

| Field        | Purpose                                 |
| ------------ | --------------------------------------- |
| Visitor Name | The name of the buyer.                  |
| Buys         | What item types or tags they buy.       |
| Rate         | How much they pay.                      |
| Limit        | Maximum Coins paid per individual card. |
| Special Rule | Any extra restriction or effect.        |

Example Public Visitor:

```text
The King
Buys: Trinkets or Armaments
Rate: Face value
Limit: 10 Coins per individual card
```

---

## 12. Selling to Public Visitors

After completing Private Orders, a player may sell eligible leftover goods to the Public Visitor.

Each Public Visitor lists:

* What item types or tags they buy
* The payment rate
* The maximum coin limit per individual card

A player may sell any number of eligible cards to the Public Visitor.

Each card is sold separately.

If a card’s value is higher than the Visitor’s limit, the player only gains Coins up to that limit.

Sold cards are discarded after payment is received.

---

## 13. Public Visitor Example

Example Public Visitor:

```text
The King
Buys: Trinkets or Armaments
Rate: Face value
Limit: 10 Coins per individual card
```

Example sale:

| Card           | Type       |       Value | Coins Gained |
| -------------- | ---------- | ----------: | -----------: |
| Silver Ring    | Trinket    |           4 |            4 |
| Polished Sword | Armament   |           7 |            7 |
| Royal Blade    | Armament   |          12 |           10 |
| Healing Potion | Consumable | Cannot sell |            0 |

The Royal Blade is worth 12, but The King has a limit of 10 Coins per individual card, so the player gains 10 Coins for it.

The Healing Potion cannot be sold to The King because he only buys Trinkets or Armaments.

---

## 14. Selling Order

Players must resolve Private Orders before selling to the Public Visitor.

The Selling order is:

1. Complete any Private Orders you want to complete.
2. Sell any eligible leftover goods to the Public Visitor.
3. Stop selling.

Once a player starts selling to the Public Visitor, they may not go back and complete more Private Orders during that same Selling Phase.

This keeps Private Orders as the main strategic selling puzzle and Public Visitors as the fallback outlet for leftover goods.

---

## 15. Refilling Order Slots

Empty Order slots are not refilled immediately.

At the end of the Selling Phase, each player refills empty Order slots up to their current Order slot limit.

When refilling an Order slot, the player chooses which available Private Order pile to draw from.

At the end of Round 1 and Round 2, shops also gain 1 additional Order slot before refilling.

Order slot progression:

| Timing                      | Order Slot Limit |
| --------------------------- | ---------------: |
| Start of game               |                3 |
| After Round 1 Selling Phase |                4 |
| After Round 2 Selling Phase |                5 |

In the final round, players do not need to refill or expand Order slots unless a playtest specifically requires it.

---

## 16. Current Prototype Assumptions

The current Selling Card assumptions are:

* Selling Cards include Private Orders and Public Visitors.
* Private Orders use Order slots.
* Public Visitors do not use Order slots.
* Players start with 3 Order slots.
* Shops expand to 4 Order slots after Round 1.
* Shops expand to 5 Order slots after Round 2.
* Players choose which Private Order piles to draw from.
* Players may complete any number of Private Orders during the Selling Phase.
* Public Visitors buy leftover eligible goods after Private Orders.
* Public Visitors pay per individual card sold.
* Public Visitors may have a per-card coin limit.
* The first prototype uses 1 Public Visitor.

---

## 17. Playtest Notes

Things to check during playtesting:

* Are Private Orders clear and easy to complete?
* Do players understand the difference between Private Orders and Public Visitors?
* Does choosing Order piles give players enough strategy?
* Is choosing Order piles too flexible?
* Does the 3 / 4 / 5 Order slot progression feel good?
* Does unlimited Private Order completion create exciting turns or runaway turns?
* Does the Public Visitor feel useful without becoming the best selling option?
* Is the Public Visitor’s per-card coin limit easy to understand?
* Should Public Visitors refresh between rounds?
* Should some Private Orders be harder but much more rewarding?
* Do Order piles need different difficulty levels or identities?
