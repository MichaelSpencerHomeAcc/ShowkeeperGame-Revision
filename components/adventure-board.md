# Adventure Board

This document defines the Adventure board for the first playable prototype of Shopkeeper Showdown.

The Adventure board is where players move their adventurers, discover Mystery Tokens, and reveal Adventure Cards.

---

## 1. Current Prototype Board

The first playable prototype uses a **10x8 Forest Adventure board**.

The Forest is the only Adventure map currently used in Version 0.1.2.

Future versions may add additional Adventure maps, regions, or board layouts.

---

## 2. Board Size

The current board is:

* **10 columns**
* **8 rows**

Suggested coordinate layout:

* Columns: **A–J**
* Rows: **1–8**

This creates 80 total spaces.

Example coordinate:

```text
C4
```

---

## 3. Forest Map

The current Adventure board represents a Forest.

The Forest may include spaces such as:

* Clearings
* Paths
* Ruins
* Streams
* Dense trees
* Campsites
* Hidden shrines
* Monster lairs
* Old roads
* Resource sites

For the first prototype, the Forest does not need detailed terrain rules unless added later.

All valid spaces can be treated as normal spaces unless a specific board feature says otherwise.

---

## 4. Starting Space

Players begin the Adventure Phase at the **Town Gate**.

The Town Gate is the shared starting space for adventurers entering the Forest.

For the first prototype, the Town Gate should be placed on the edge of the board.

Suggested location:

```text
E8 or F8
```

All players may occupy the Town Gate at the same time.

---

## 5. Mystery Tokens

Mystery Tokens represent unknown points of interest on the Adventure board.

A Mystery Token might reveal:

* A Monster
* A Quest
* A Trap
* A Discovery

Players do not know what type of Adventure Card will be revealed until they interact with the Mystery Token.

---

## 6. Placing Mystery Tokens

At the start of each Adventure Phase, place **2 Mystery Tokens per player** on empty valid spaces of the Adventure board.

Example:

| Player Count | Mystery Tokens |
| ------------ | -------------: |
| 2 players    |       4 tokens |
| 3 players    |       6 tokens |
| 4 players    |       8 tokens |
| 5 players    |      10 tokens |
| 6 players    |      12 tokens |

---

## 7. Random Mystery Token Placement

Mystery Tokens should be placed randomly.

For a 10x8 board, the recommended method is:

1. Roll a d10 for the column.
2. Roll a d8 for the row.
3. Place the Mystery Token on that coordinate.

Column mapping:

| d10 Result | Column |
| ---------: | ------ |
|          1 | A      |
|          2 | B      |
|          3 | C      |
|          4 | D      |
|          5 | E      |
|          6 | F      |
|          7 | G      |
|          8 | H      |
|          9 | I      |
|         10 | J      |

Row mapping:

| d8 Result | Row |
| --------: | --- |
|         1 | 1   |
|         2 | 2   |
|         3 | 3   |
|         4 | 4   |
|         5 | 5   |
|         6 | 6   |
|         7 | 7   |
|         8 | 8   |

If the selected space is occupied by another Mystery Token or is not a valid space, reroll or place the token on the nearest empty valid space.

---

## 8. Refilling Mystery Tokens

Whenever a Mystery Token is removed from the board, immediately place a new Mystery Token on an empty valid space.

This keeps the Adventure board active throughout the Adventure Phase.

The new token is placed using the normal Mystery Token placement rules.

---

## 9. Player Movement

On an Adventure turn, a player may move up to their movement value.

Current prototype movement value:

```text
3 spaces
```

Unless a card, skill, boon, or effect says otherwise, players move orthogonally.

Orthogonal movement means:

* Up
* Down
* Left
* Right

Diagonal movement is not currently allowed.

---

## 10. Interacting with Mystery Tokens

If a player moves onto a space containing a Mystery Token, they may pause their movement to interact with it.

When a player interacts with a Mystery Token:

1. Remove the Mystery Token from the board.
2. Reveal the top card of the Adventure Deck.
3. Resolve the Adventure Card.
4. Place a new Mystery Token on the board.
5. If the player has movement remaining, they may continue moving.

A player may only interact with **one Mystery Token per Adventure turn** unless a card, skill, or boon says otherwise.

---

## 11. Player Occupancy

Multiple players may occupy the same board space.

Players do not block movement.

Players may move through spaces occupied by other players.

---

## 12. Current Prototype Assumptions

The current Adventure board assumptions are:

* The board is 10x8.
* The map is the Forest.
* Mystery Tokens are placed randomly.
* 2 Mystery Tokens are placed per player at the start of each Adventure Phase.
* Mystery Tokens refill immediately when removed.
* Players move up to 3 spaces per Adventure turn.
* Players may interact with a Mystery Token during movement, then continue moving.
* Players may only interact with one Mystery Token per Adventure turn by default.
* Multiple players can share the same space.

---

## 13. Playtest Notes

Things to check during playtesting:

* Does the 10x8 board feel too large, too small, or about right?
* Is 3 movement enough?
* Are 2 Mystery Tokens per player enough?
* Does refilling Mystery Tokens keep the board active?
* Does mid-movement interaction feel smooth?
* Does limiting players to one interaction per Adventure turn feel correct?
* Does the Forest need terrain rules, or is a simple open grid enough for now?
