![Latest Release](https://img.shields.io/github/v/release/btigi/iiProjectileR?color=blue)

---

# Projectile Retrieval

 Projectile Retrieval  has a simple aim - to allow the player to retrieve used projectiles. Primarily intended for arrows (though bolts and bullets are supported), the fact that projectile can be retrieved from the environment after use increases the realism of the game (and besides, it's cool to pick up your spent arrows from the bodies of your fallen enemies).


Players can install the retrieval option for any combination of projectiles. Items that count as projectiles, in regards to this mod, are arrows, bolts, bullets, darts, throwing daggers and throwing axes.
Players can choose the percentage chance of a projectile being retrievable - (values are clamped at 0 and 100). NOTE: Only items making a successful hit can be retrieved. Items which miss the target are lost forever.
Players can then further choose which category of the item will be retrievable, with the following options:


Normal items
Only the default item-type will be retrievable, e.g. a plain, non enchanted arrow will be retrievable, whereas an Arrow of Detonation will not be.

All items as normal items
All items will be retrievable as the default item-type, e.g. a plain, non enchanted arrow will be retrievable as a plain, non enchanted arrow, and an Arrow of Detonation will also be retrievable as a plain, non enchanted arrow.

All items as all items
All items will be retrievable as their actual item-type, e.g. a plain, non enchanted arrow will be retrievable as a plain, non enchanted arrow, whereas an Arrow of Detonation will be retrievable as an Arrow of Detonation.

Degrading Enchantment
Based on the THAC0 of the magical item it will be retrieved as the next lowest magical item or plain item.
    An Arrow of Piercing will be retrieved as an Arrow +2
    An Arrow +2 will be retrieved as an Arrow +1
    An Arrow +1 will be retrieved as a plain arrow
    A plain arrow will be retrieved as a plain arrow

Player's secondary choices are:
  1. Plain non-magical items only retrieved as plain non-magical items
  2. Magical & Plain items retrieved as plain non-magical items
  3. Each item retrieved as itself
  4. Magical items retrieved as a lower magical item and ultimately retrieved as a plain non-magical item.
