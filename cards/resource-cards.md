# Resource Cards

This document defines the Basic Resource Deck for Shopkeeper Showdown.

Resource Cards represent the everyday goods players can gather, buy, trade, discover, or use to fulfil basic selling opportunities.

This deck does not include Crafted Goods, Artifacts, or Black Market Goods. Those are separate decks with their own card lists and rules.

---

## 1. Purpose of the Basic Resource Deck

The Basic Resource Deck is the main economy deck.

It should provide players with reliable goods that can be used for:

* Selling Cards
* Crafting
* Town actions
* Shop upgrades
* Quests
* Trading or conversion effects

The deck should be broad enough to support all four main item types while remaining easy to understand.

---

## 2. Deck Size

Current target deck size:

| Item Type   | Number of Cards |
| ----------- | --------------: |
| Armaments   |              24 |
| Consumables |              24 |
| Trinkets    |              24 |
| Trade Goods |              24 |
| **Total**   |          **96** |

This number is intended to support a 4–6 player game where players may gain several resources during the Adventure and Town phases.

---

## 3. Main Item Types

Every Resource Card has exactly one main item type.

The four main item types are:

1. Armament
2. Consumable
3. Trinket
4. Trade Good

These types are used by Selling Cards, crafting, quests, upgrades, and other game effects.

---

## 4. Tags on Resource Cards

Resource Cards may have tags, but the Basic Resource Deck should use tags lightly.

The most common tags in this deck should be:

| Tag          | Use                                               |
| ------------ | ------------------------------------------------- |
| Common       | A standard, reliable item.                        |
| Rare         | A more valuable or harder-to-find item.           |
| Magical      | An item with magical properties.                  |
| Monster Part | An item taken from a creature or dangerous beast. |
| Exotic       | A rare, strange, far-travelled, luxury item       |
| Cursed       | High value, but comes with risky effects          |
| Elegant      | A luxurious item that has vlaue to nobles         |
| Contraband   | A stolen or Black market item or object           |
| Sacred       | An ornate item with religious or clerical value   |
| Food         | An item that is classified as Food                |
| Material     | An item used in Crafting                          |
| Herb         | An item that is a plant or substance              |
| Potion       | An alchemical creation that can be ingested       |
| Reagent      | An alchemical item used in alchemy                |

The Basic Resource Deck should generally avoid tags like **Crafted**, **Artifact**, and **Stolen**, because those belong more naturally to separate decks.

---

## 5. Resource Card Anatomy

Each Resource Card should include:

| Field     | Purpose                                       |
| --------- | --------------------------------------------- |
| Card Name | The name of the resource.                     |
| Item Type | Armament, Consumable, Trinket, or Trade Good. |
| Tags      | Any additional qualities the card has.        |
| Value     | The card’s base coin value.                   |
| Effect    | Any special rule, if the card has one.        |
| Notes     | Design notes, balance notes, or source notes. |
| Asset     | File path for the card image, if designed.    |

Example:

```text
Name: Iron Sword
Item Type: Armament
Tags: Common
Value: 3
Effect: None
Notes: Basic low-value Armament.
Asset: assets/card-drafts/resource-cards/armaments/iron-sword.png
```

---

## 6. Value Bands

Resource Cards should generally sit within simple value bands.

| Value | Meaning                                                         |
| ----: | --------------------------------------------------------------- |
|   1–2 | Very low-value filler item                                      |
|   3–4 | Standard basic item                                             |
|   5–6 | Strong basic item or lightly tagged item                        |
|   7–8 | Rare or magical item                                            |
|    9+ | Usually reserved for Crafted Goods, Artifacts, or special decks |

The Basic Resource Deck should mostly contain values from **2 to 6**, with only a small number of cards reaching **7 or 8**.

---

## 7. Suggested Distribution Per Item Type

Each item type currently has 24 cards.

Suggested spread per type:

| Category                              | Cards Per Type |
| ------------------------------------- | -------------: |
| Common/basic items                    |             14 |
| Rare items                            |              4 |
| Magical items                         |              3 |
| Monster Part / creature-related items |              3 |
| **Total**                             |         **24** |

Across the full 96-card deck, this gives:

| Category                              | Total Cards |
| ------------------------------------- | ----------: |
| Common/basic items                    |          56 |
| Rare items                            |          16 |
| Magical items                         |          12 |
| Monster Part / creature-related items |          12 |
| **Total**                             |      **96** |

---

## 8. Armament Resource Cards

Armaments are weapons, armour, shields, tools, and combat equipment.

Target count: **24 cards**

| Card Name            | Tags         | Value | Effect | Notes                          | Asset                                                                |
| -------------------- | ------------ | ----: | ------ | ------------------------------ | -------------------------------------------------------------------- |
| Iron Sword           | Common       |     3 | None   | Basic Armament.                | assets/card-drafts/resource-cards/armaments/iron-sword.png           |
| Wooden Shield        | Common       |     2 | None   | Cheap defensive item.          | assets/card-drafts/resource-cards/armaments/wooden-shield.png        |
| Hunter’s Bow         | Common       |     4 | None   | Standard ranged weapon.        | assets/card-drafts/resource-cards/armaments/hunters-bow.png          |
| Travelling Spear     | Common       |     3 | None   | Basic adventurer weapon.       | assets/card-drafts/resource-cards/armaments/travelling-spear.png     |
| Leather Armour       | Common       |     4 | None   | Basic armour.                  | assets/card-drafts/resource-cards/armaments/leather-armour.png       |
| Rusted Axe           | Common       |     2 | None   | Low-value weapon.              | assets/card-drafts/resource-cards/armaments/rusted-axe.png           |
| Guard’s Helmet       | Common       |     3 | None   | Basic defensive gear.          | assets/card-drafts/resource-cards/armaments/guards-helmet.png        |
| Bundle of Arrows     | Common       |     2 | None   | Cheap adventuring supplies.    | assets/card-drafts/resource-cards/armaments/bundle-of-arrows.png     |
| Steel Dagger         | Common       |     4 | None   | Small but reliable weapon.     | assets/card-drafts/resource-cards/armaments/steel-dagger.png         |
| Chainmail Vest       | Common       |     5 | None   | Higher-value basic armour.     | assets/card-drafts/resource-cards/armaments/chainmail-vest.png       |
| Reinforced Buckler   | Common       |     4 | None   | Defensive Armament.            | assets/card-drafts/resource-cards/armaments/reinforced-buckler.png   |
| Adventurer’s Kit     | Common       |     5 | None   | Flexible adventuring gear.     | assets/card-drafts/resource-cards/armaments/adventurers-kit.png      |
| Silvered Blade       | Rare, Elegant|     6 | None   | Useful for special orders.     | assets/card-drafts/resource-cards/armaments/silvered-blade.png       |
| Elven Longbow        | Rare, Elegant|     7 | None   | High-value ranged weapon.      | assets/card-drafts/resource-cards/armaments/elven-longbow.png        |
| Dwarven Warhammer    | Rare         |     7 | None   | High-value weapon.             | assets/card-drafts/resource-cards/armaments/dwarven-warhammer.png    |
| Knight’s Shield      | Rare         |     6 | None   | High-value defensive item.     | assets/card-drafts/resource-cards/armaments/knights-shield.png       |
| Emberblade           | Magical      |     7 | None   | Magical weapon.                | assets/card-drafts/resource-cards/armaments/emberblade.png           |
| Frostguard Mail      | Magical      |     8 | None   | Magical armour.                | assets/card-drafts/resource-cards/armaments/frostguard-mail.png      |
| Wand of Sparks       | Magical      |     6 | None   | Magical combat tool.           | assets/card-drafts/resource-cards/armaments/wand-of-sparks.png       |
| Basilisk Fang Dagger | Monster Part |     6 | None   | Made from a creature part.     | assets/card-drafts/resource-cards/armaments/basilisk-fang-dagger.png |
| Wyvern-Scale Shield  | Monster Part |     7 | None   | Creature-based defensive item. | assets/card-drafts/resource-cards/armaments/wyvern-scale-shield.png  |
| Manticore Spine Whip | Monster Part |     7 | None   | Creature-based weapon.         | assets/card-drafts/resource-cards/armaments/manticore-spine-whip.png |
| Spare Armament Slot  | TBD          |   TBD | TBD    | Placeholder.                   | TBD                                                                  |
| Spare Armament Slot  | TBD          |   TBD | TBD    | Placeholder.                   | TBD                                                                  |

---

## 9. Consumable Resource Cards

Consumables are potions, food, medicine, scrolls, bombs, oils, and other items that are used up.

Target count: **24 cards**

| Card Name             | Tags         | Value | Effect | Notes                        | Asset                                                                  |
| --------------------- | ------------ | ----: | ------ | ---------------------------- | ---------------------------------------------------------------------- |
| Healing Potion        | Common       |     3 | None   | Basic Consumable.            | assets/card-drafts/resource-cards/consumables/healing-potion.png       |
| Ration Pack           | Common       |     2 | None   | Cheap supply item.           | assets/card-drafts/resource-cards/consumables/ration-pack.png          |
| Lantern Oil           | Common       |     2 | None   | Utility consumable.          | assets/card-drafts/resource-cards/consumables/lantern-oil.png          |
| Smoke Bomb            | Common       |     4 | None   | Adventuring tool.            | assets/card-drafts/resource-cards/consumables/smoke-bomb.png           |
| Antidote Vial         | Common       |     3 | None   | Medicine.                    | assets/card-drafts/resource-cards/consumables/antidote-vial.png        |
| Trail Biscuits        | Common       |     2 | None   | Low-value food.              | assets/card-drafts/resource-cards/consumables/trail-biscuits.png       |
| Fire Flask            | Common       |     5 | None   | High-value basic Consumable. | assets/card-drafts/resource-cards/consumables/fire-flask.png           |
| Stamina Tonic         | Common       |     4 | None   | Adventuring consumable.      | assets/card-drafts/resource-cards/consumables/stamina-tonic.png        |
| Bandage Roll          | Common       |     2 | None   | Cheap medical item.          | assets/card-drafts/resource-cards/consumables/bandage-roll.png         |
| Preserved Meat        | Common       |     3 | None   | Food supply.                 | assets/card-drafts/resource-cards/consumables/preserved-meat.png       |
| Torch Bundle          | Common       |     3 | None   | Exploration supply.          | assets/card-drafts/resource-cards/consumables/torch-bundle.png         |
| Chalk and Twine       | Common       |     2 | None   | Dungeon supply item.         | assets/card-drafts/resource-cards/consumables/chalk-and-twine.png      |
| Dwarven Ale Keg       | Rare         |     6 | None   | Rare drink.                  | assets/card-drafts/resource-cards/consumables/dwarven-ale-keg.png      |
| Moonberry Wine        | Rare         |     7 | None   | Rare luxury drink.           | assets/card-drafts/resource-cards/consumables/moonberry-wine.png       |
| Phoenix Pepper Sauce  | Rare         |     6 | None   | Rare food item.              | assets/card-drafts/resource-cards/consumables/phoenix-pepper-sauce.png |
| Royal Remedy          | Rare         |     7 | None   | High-value medicine.         | assets/card-drafts/resource-cards/consumables/royal-remedy.png         |
| Scroll of Sparks      | Magical      |     6 | None   | Magical scroll.              | assets/card-drafts/resource-cards/consumables/scroll-of-sparks.png     |
| Bottled Breeze        | Magical      |     7 | None   | Magical utility item.        | assets/card-drafts/resource-cards/consumables/bottled-breeze.png       |
| Glowcap Tonic         | Magical      |     7 | None   | Magical potion.              | assets/card-drafts/resource-cards/consumables/glowcap-tonic.png        |
| Troll Fat Salve       | Monster Part |     5 | None   | Creature-based medicine.     | assets/card-drafts/resource-cards/consumables/troll-fat-salve.png      |
| Slime Jelly Jar       | Monster Part |     5 | None   | Creature ingredient.         | assets/card-drafts/resource-cards/consumables/slime-jelly-jar.png      |
| Powdered Harpy Claw   | Monster Part |     6 | None   | Monster ingredient.          | assets/card-drafts/resource-cards/consumables/powdered-harpy-claw.png  |
| Spare Consumable Slot | TBD          |   TBD | TBD    | Placeholder.                 | TBD                                                                    |
| Spare Consumable Slot | TBD          |   TBD | TBD    | Placeholder.                 | TBD                                                                    |

---

## 10. Trinket Resource Cards

Trinkets are jewellery, charms, curios, relics, keepsakes, and small valuable items.

Target count: **24 cards**

| Card Name              | Tags         | Value | Effect | Notes                        | Asset                                                                 |
| ---------------------- | ------------ | ----: | ------ | ---------------------------- | --------------------------------------------------------------------- |
| Silver Ring            | Common       |     3 | None   | Basic Trinket.               | assets/card-drafts/resource-cards/trinkets/silver-ring.png            |
| Lucky Charm            | Common       |     2 | None   | Cheap charm.                 | assets/card-drafts/resource-cards/trinkets/lucky-charm.png            |
| Brass Locket           | Common       |     3 | None   | Basic keepsake.              | assets/card-drafts/resource-cards/trinkets/brass-locket.png           |
| Painted Idol           | Common       |     4 | None   | Decorative trinket.          | assets/card-drafts/resource-cards/trinkets/painted-idol.png           |
| Glass Beads            | Common       |     2 | None   | Low-value trinket.           | assets/card-drafts/resource-cards/trinkets/glass-beads.png            |
| Merchant’s Brooch      | Common       |     4 | None   | Practical status item.       | assets/card-drafts/resource-cards/trinkets/merchants-brooch.png       |
| Bone Dice              | Common       |     3 | None   | Game/gambling trinket.       | assets/card-drafts/resource-cards/trinkets/bone-dice.png              |
| Tiny Music Box         | Common       |     5 | None   | Higher-value common trinket. | assets/card-drafts/resource-cards/trinkets/tiny-music-box.png         |
| Copper Bracelet        | Common       |     2 | None   | Cheap jewellery.             | assets/card-drafts/resource-cards/trinkets/copper-bracelet.png        |
| Polished Shell Charm   | Common       |     3 | None   | Decorative charm.            | assets/card-drafts/resource-cards/trinkets/polished-shell-charm.png   |
| Wax Seal Stamp         | Common       |     4 | None   | Merchant-themed trinket.     | assets/card-drafts/resource-cards/trinkets/wax-seal-stamp.png         |
| Pocket Sundial         | Common       |     5 | None   | Useful small device.         | assets/card-drafts/resource-cards/trinkets/pocket-sundial.png         |
| Sapphire Pendant       | Rare         |     7 | None   | Valuable jewellery.          | assets/card-drafts/resource-cards/trinkets/sapphire-pendant.png       |
| Noble’s Signet         | Rare         |     6 | None   | High-status trinket.         | assets/card-drafts/resource-cards/trinkets/nobles-signet.png          |
| Pearl Comb             | Rare         |     6 | None   | Luxury trinket.              | assets/card-drafts/resource-cards/trinkets/pearl-comb.png             |
| Golden Prayer Bead     | Rare         |     7 | None   | Rare religious item.         | assets/card-drafts/resource-cards/trinkets/golden-prayer-bead.png     |
| Whispering Amulet      | Magical      |     7 | None   | Magical jewellery.           | assets/card-drafts/resource-cards/trinkets/whispering-amulet.png      |
| Floating Coin          | Magical      |     6 | None   | Magical curiosity.           | assets/card-drafts/resource-cards/trinkets/floating-coin.png          |
| Glowstone Charm        | Magical      |     6 | None   | Magical charm.               | assets/card-drafts/resource-cards/trinkets/glowstone-charm.png        |
| Gryphon Feather Brooch | Monster Part |     6 | None   | Creature-derived trinket.    | assets/card-drafts/resource-cards/trinkets/gryphon-feather-brooch.png |
| Kraken Tooth Pendant   | Monster Part |     7 | None   | Sea monster trinket.         | assets/card-drafts/resource-cards/trinkets/kraken-tooth-pendant.png   |
| Cockatrice Eye Marble  | Monster Part |     6 | None   | Creature-based curio.        | assets/card-drafts/resource-cards/trinkets/cockatrice-eye-marble.png  |
| Spare Trinket Slot     | TBD          |   TBD | TBD    | Placeholder.                 | TBD                                                                   |
| Spare Trinket Slot     | TBD          |   TBD | TBD    | Placeholder.                 | TBD                                                                   |

---

## 11. Trade Good Resource Cards

Trade Goods are raw materials, cargo, ingredients, supplies, and bulk goods.

Target count: **24 cards**

| Card Name             | Tags         | Value | Effect | Notes                        | Asset                                                                |
| --------------------- | ------------ | ----: | ------ | ---------------------------- | -------------------------------------------------------------------- |
| Crate of Ore          | Common       |     3 | None   | Basic Trade Good.            | assets/card-drafts/resource-cards/trade-goods/crate-of-ore.png       |
| Bundle of Cloth       | Common       |     2 | None   | Basic material.              | assets/card-drafts/resource-cards/trade-goods/bundle-of-cloth.png    |
| Sack of Grain         | Common       |     2 | None   | Basic food cargo.            | assets/card-drafts/resource-cards/trade-goods/sack-of-grain.png      |
| Timber Planks         | Common       |     3 | None   | Building material.           | assets/card-drafts/resource-cards/trade-goods/timber-planks.png      |
| Leather Bundle        | Common       |     3 | None   | Crafting material.           | assets/card-drafts/resource-cards/trade-goods/leather-bundle.png     |
| Spice Jar             | Common       |     4 | None   | Valuable common cargo.       | assets/card-drafts/resource-cards/trade-goods/spice-jar.png          |
| Wool Bale             | Common       |     2 | None   | Basic cargo.                 | assets/card-drafts/resource-cards/trade-goods/wool-bale.png          |
| Beeswax Blocks        | Common       |     3 | None   | Crafting material.           | assets/card-drafts/resource-cards/trade-goods/beeswax-blocks.png     |
| Salted Fish Crate     | Common       |     3 | None   | Food cargo.                  | assets/card-drafts/resource-cards/trade-goods/salted-fish-crate.png  |
| Clay Jugs             | Common       |     2 | None   | Low-value cargo.             | assets/card-drafts/resource-cards/trade-goods/clay-jugs.png          |
| Iron Ingots           | Common       |     5 | None   | Strong common material.      | assets/card-drafts/resource-cards/trade-goods/iron-ingots.png        |
| Herb Bundle           | Common       |     4 | None   | Alchemy/cooking material.    | assets/card-drafts/resource-cards/trade-goods/herb-bundle.png        |
| Silk Roll             | Rare         |     6 | None   | Rare material.               | assets/card-drafts/resource-cards/trade-goods/silk-roll.png          |
| Saffron Pouch         | Rare         |     7 | None   | Rare spice.                  | assets/card-drafts/resource-cards/trade-goods/saffron-pouch.png      |
| Moonstone Chunk       | Rare         |     7 | None   | Rare mineral.                | assets/card-drafts/resource-cards/trade-goods/moonstone-chunk.png    |
| Deepwood Resin        | Rare         |     6 | None   | Rare crafting material.      | assets/card-drafts/resource-cards/trade-goods/deepwood-resin.png     |
| Arcane Ink            | Magical      |     6 | None   | Magical crafting material.   | assets/card-drafts/resource-cards/trade-goods/arcane-ink.png         |
| Glowmoss Crate        | Magical      |     7 | None   | Magical plant cargo.         | assets/card-drafts/resource-cards/trade-goods/glowmoss-crate.png     |
| Starfallen Dust       | Magical      |     8 | None   | High-value magical material. | assets/card-drafts/resource-cards/trade-goods/starfallen-dust.png    |
| Basilisk Hide         | Monster Part |     6 | None   | Creature material.           | assets/card-drafts/resource-cards/trade-goods/basilisk-hide.png      |
| Troll Bone Bundle     | Monster Part |     5 | None   | Creature material.           | assets/card-drafts/resource-cards/trade-goods/troll-bone-bundle.png  |
| Wyvern Venom Gland    | Monster Part |     7 | None   | Creature ingredient.         | assets/card-drafts/resource-cards/trade-goods/wyvern-venom-gland.png |
| Spare Trade Good Slot | TBD          |   TBD | TBD    | Placeholder.                 | TBD                                                                  |
| Spare Trade Good Slot | TBD          |   TBD | TBD    | Placeholder.                 | TBD                                                                  |

---

## 12. Notes for Future Revision

Things to review after testing:

* Whether 96 Basic Resource Cards is enough for 4–6 players.
* Whether the deck needs duplicate cards or all unique cards.
* Whether values are too flat or too generous.
* Whether Monster Part cards should remain in the Basic Resource Deck or move mostly into Monster rewards.
* Whether Rare and Magical cards should appear often enough.
* Whether Selling Cards ask for item types too often or tags too often.
* Whether Trade Goods are too broad compared to the other item types.
* Whether basic cards need small effects, or whether effects should be reserved for special decks.
