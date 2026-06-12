# Selling Phase

This document defines the Selling Phase for the first playable prototype of Shopkeeper Showdown.

The Selling Phase is where players complete private Orders, sell leftover goods to the Public Visitor, and prepare new Orders for the next round.

These rules are for Version 0.1.2 and are intentionally simple for the first playable prototype.

---

## 1. Purpose

The Selling Phase is the main payoff phase of each round.

Players use the Resources, Crafted Goods, Artifacts, and other items they have gained to complete Orders and earn Coins, Reputation, and other rewards.

The Selling Phase should reward players for:

* Planning around their private Orders
* Collecting the right item types and tags
* Completing valuable Orders
* Turning leftover goods into Coins
* Preparing their shop for the next round

---

## 2. Current Prototype Structure

Each Selling Phase follows this structure:

1. Complete private Orders.
2. Sell leftover eligible goods to the Public Visitor.
3. Expand Order slots if appropriate.
4. Refill empty Order slots.
5. End the Selling Phase.

Players resolve Selling one at a time, starting with the First Player and continuing clockwise.

---

## 3. Orders

Orders are private Selling Cards in a player’s shop.

Each Order lists:

* Requirements
* Rewards
* Any special effect
* Any tags or restrictions

Example Order requirement:

```text
Sell any 2 Consumables.
```

Example Order reward:

```text
Gain 8 Coins and 1 Reputation.
```

Orders are the main planned selling system.

Public Visitors are separate from private Orders.

---

## 4. Order Slots

Each player has a number of Order slots in their shop.

Order slots determine how many private Orders a player may have available at once.

At the start of the game, each player has **3 Order slots**.

The current prototype Order slot progression is:

| Round | Order Slots |
| ----: | ----------: |
|     1 |           3 |
|     2 |           4 |
|     3 |           5 |

A player cannot have more private Orders available than their current number of Order slots.

---

## 5. Starting Orders

During setup, each player chooses 3 starting private Orders from the available Order piles.

Players may choose which piles to draw from.

Example starting choices:

* 3 Visitor Orders
* 2 Craft Requests and 1 Hero Order
* 1 Business Order, 1 Luxury Commission, and 1 Black Market Deal

Each chosen Order is placed face up in that player’s shop.

These 3 Orders fill the player’s starting Order slots.

---

## 6. Private Order Piles

Private Orders may be separated into different piles by type.

Possible Order piles include:

* Visitor Orders
* Craft Requests
* Business Orders
* Hero Orders
* Black Market Deals
* Luxury Commissions

When a player draws a new private Order, they may choose which available Order pile to draw from unless a rule or effect says otherwise.

This lets players shape their shop strategy throughout the game.

---

## 7. Completing Private Orders

During the Selling Phase, a player may complete any number of private Orders they can fulfil.

To complete a private Order:

1. Choose one of your private Orders.
2. Pay or discard the required items.
3. Gain the listed rewards.
4. Resolve any effects on the Order.
5. Move the completed Order to your completed Orders pile.
6. Leave that Order slot empty until the refill step.

A player may complete private Orders in any order.

A player is not required to complete an Order, even if they can.

---

## 8. Selling Requirements

Private Orders may require specific item types, tags, rarities, or combinations.

Examples:

```text
Sell any 2 Trinkets.
```

```text
Sell 1 Armament and 1 Consumable.
```

```text
Sell any 1 Magical item.
```

```text
Sell 1 Rare Trinket.
```

```text
Sell any 3 Trade Goods.
```

Unless an Order says otherwise, items used to complete an Order are discarded after the Order is completed.

---

## 9. Public Visitor

The Public Visitor is a shared buyer available to all players.

Unlike private Orders, the Public Visitor is not completed.

The Public Visitor does not leave after one player sells to them unless a card specifically says otherwise.

The Public Visitor buys eligible leftover goods after the player has completed any private Orders they want to complete.

Public Visitors are intended as a flexible way to sell leftover goods, not as the main planned selling system.

---

## 10. Selling to the Public Visitor

After completing private Orders, a player may sell eligible leftover goods to the Public Visitor.

Each Public Visitor lists:

* What item types or tags they buy
* The payment rate
* The maximum coin limit per individual card

A player may sell any number of eligible cards to the Public Visitor.

Each card is sold separately.

If a card’s value is higher than the Visitor’s limit, the player only gains Coins up to that limit.

Sold cards are discarded after payment is received.

---

## 11. Public Visitor Example

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

## 12. Selling Order

Players must resolve private Orders before selling to the Public Visitor.

The Selling order is:

1. Complete any private Orders you want to complete.
2. Sell any eligible leftover goods to the Public Visitor.
3. Stop selling.

Once a player starts selling to the Public Visitor, they may not go back and complete more private Orders during that same Selling Phase.

This keeps private Orders as the main strategic selling puzzle and Public Visitors as the fallback outlet for leftover goods.

---

## 13. Empty Order Slots

When a player completes a private Order, that Order slot becomes empty.

Empty Order slots are not refilled immediately.

Empty Order slots are refilled during the Order refill step at the end of the Selling Phase.

This means players finish their selling before seeing their new Orders.

---

## 14. Expanding Order Slots

At the end of each Selling Phase, each player’s shop gains 1 additional Order slot, up to a maximum of 5 Order slots.

Order slot progression:

| Timing                      |            Order Slot Limit |
| --------------------------- | --------------------------: |
| Start of game               |                           3 |
| After Round 1 Selling Phase |                           4 |
| After Round 2 Selling Phase |                           5 |
| After Round 3 Selling Phase | No further expansion needed |

In the final round, players do not need to refill or expand Order slots unless a playtest specifically requires it.

---

## 15. Refilling Order Slots

After Order slots expand, each player refills all empty Order slots up to their current Order slot limit.

When refilling an Order slot, the player chooses which available private Order pile to draw from.

Example:

A player ends Round 1 with 1 private Order still in their shop.

They completed 2 Orders, so they have 2 empty Order slots.

At the end of Round 1:

1. Their Order slot limit increases from 3 to 4.
2. They now have 3 empty Order slots.
3. They draw 3 new private Orders from any available Order piles.
4. Their shop now has 4 private Orders ready for Round 2.

---

## 16. Public Visitor Refresh

For Version 0.1.2, the Public Visitor stays in play until a rule or effect changes it.

The Public Visitor is not discarded just because players sell to them.

Future versions may add rules for refreshing the Public Visitor between rounds.

Possible future rules include:

* Replace the Public Visitor at the end of each round.
* Replace the Public Visitor after a certain number of cards are sold.
* Allow a Town action to change the Public Visitor.
* Have multiple Public Visitors available.

For the first prototype, use 1 Public Visitor.

---

## 17. End of Selling Phase

The Selling Phase ends after:

1. Each player has completed private Orders and sold to the Public Visitor.
2. Order slots have expanded, if appropriate.
3. Empty Order slots have been refilled, if appropriate.

After the Selling Phase ends, proceed to the next round.

If the Selling Phase was the final Selling Phase of Round 3, proceed to final scoring instead.

---

## 18. Current Prototype Assumptions

The current Selling Phase assumptions are:

* Players complete private Orders first.
* Players may complete any number of private Orders they can fulfil.
* Public Visitors are used after private Orders.
* Public Visitors buy leftover eligible goods.
* Public Visitors do not get completed like private Orders.
* Public Visitors pay per individual card sold.
* Public Visitors may have a per-card coin limit.
* Each player starts with 3 Order slots.
* Shops expand to 4 Order slots after Round 1.
* Shops expand to 5 Order slots after Round 2.
* Players choose which private Order piles to draw from.
* Empty Order slots refill at the end of the Selling Phase.
* The first prototype uses 1 Public Visitor.

---

## 19. Playtest Notes

Things to check during playtesting:

* Does completing unlimited private Orders feel exciting or too explosive?
* Do players have enough goods to complete Orders?
* Does the Public Visitor feel useful without replacing private Orders?
* Is the Public Visitor too generous as a fallback sale option?
* Does the per-card coin limit work cleanly?
* Is choosing private Order piles too flexible or a good strategic choice?
* Does the 3 / 4 / 5 Order slot progression feel good?
* Do players understand the difference between private Orders and the Public Visitor?
* Should the Public Visitor refresh each round?
* Should Public Visitor sales happen before or after private Orders?
* Do players need a hand limit, shop limit, or storage limit?
