**PyLooter** is a 2D space-themed roguelite, bullet-hell looter built with **Python + Pygame**.

Fight through increasingly dangerous enemy waves, collect loot, gain experience, level up, and build your character through an inventory and stat system.

---

## 🎮 Game Overview

PyLooter combines:

- 🚀 **2D Space Shooter Combat**
- 👾 **Wave-Based Enemy Encounters**
- 🔫 **Bullet-Hell Gameplay**
- 💎 **Loot Drops & Rarities**
- 🎒 **Inventory & Equipment**
- 📈 **XP & Level Progression**
- 🛡️ **Shield & HP Management**
- ⚡ **Dash Movement**
- 🎯 **Homing Projectiles**
- 💥 **Explosive Attacks**
- 🔥 **Damage-over-Time Effects**
- ☄️ **Beam Weapons**
- 🍀 **Luck-Based Loot**
- 🌌 **Procedural Space Background**
- 🔊 **Combat & Gameplay Audio**

---

## 🕹️ Gameplay

The goal is simple:

> **Survive the waves, kill enemies, collect loot, level up, and become increasingly powerful.**

Enemies continuously spawn as part of the wave system. Defeat them to earn XP and potentially receive loot.

As you level up, your character becomes stronger through the game's inventory and stat systems.

Eventually, the waves become too much and you get absolutely fucking obliterated.

Then you start again.

---

## ⚔️ Combat

Combat is centered around fast movement and projectile-based attacks.

### Player Attacks

The game supports several types of offensive mechanics:

- Standard projectiles
- Piercing projectiles
- Explosive projectiles
- Homing projectiles
- Beam attacks
- Damage-over-time effects
- On-hit effects
- On-kill effects

Projectiles can interact with enemies individually, while explosive attacks can damage multiple enemies within an area.

Homing projectiles automatically steer toward nearby enemies.

---

## 🛡️ Player Survival

The player has two primary defensive resources:

### Shield

The shield absorbs incoming damage before HP is affected.

The shield can regenerate after a delay.

### HP

If the player's HP reaches zero, the run ends and the game enters the **Game Over** state.

---

## 📈 XP & Leveling

Enemies provide XP when defeated.

XP is displayed through the HUD and contributes toward the player's next level.

When the player gains a level:

- The player's level increases
- Player stats are recalculated
- A level-up notification appears
- A level-up sound effect is played

---

## 💎 Loot System

Enemies have a chance to drop loot when killed.

Loot is affected by the player's **Luck** stat.

The game supports different item rarities, with rarity determining the quality/category of the dropped item.

Dropped items appear in the game world and can be collected by the player.

The inventory system can also automatically pick up eligible loot.

---

## 🎒 Inventory

PyLooter includes a dedicated inventory system.

The inventory allows collected items to affect the player's statistics.

Opening the inventory pauses normal gameplay interaction with the player while the inventory UI is active.

Press:

```text
TAB
```

to open or close the inventory.

---

## 🌊 Wave System

Enemies are controlled through a dedicated **Wave Manager**.

Each wave tracks the current progression of the run and is displayed on the HUD.

The game is designed around surviving progressively challenging waves of enemies.

---

## 🎯 Projectile Mechanics

The game contains several projectile behaviors.

### Homing

Homing projectiles search for nearby living enemies and gradually steer toward their target.

### Piercing

Piercing projectiles can continue through multiple enemies instead of disappearing after the first hit.

### Explosive

Explosive projectiles deal additional area damage when they hit.

### Beam

The player can use a beam attack that damages enemies intersecting its path.

---

## 🔥 Status Effects

Enemies can receive damage-over-time effects.

The current combat system includes a **burn** mechanic where burning enemies continuously lose HP for the duration of the effect.

---

## 🍀 Luck

Luck influences the loot system.

Higher effective Luck can influence:

- Whether an enemy drops an item
- Which item is selected
- The resulting loot quality

Enemy-specific drop luck can also contribute to the calculation.

---

## 📊 HUD

The HUD displays important run information including:

- Current Level
- Current XP
- XP required for the next level
- Shield
- HP
- Shield regeneration status
- Current Wave
- Kill Count
- Current Damage
- Inventory summary

---

## 🎮 Controls

| Key | Action |
|---|---|
| `WASD` | Player movement |
| `SHIFT` | Dash |
| `SPACE` | Dash |
| `TAB` | Open / close inventory |
| `ESC` | Pause / resume |
| `R` | Restart after Game Over |
| `F1` | Toggle hitboxes |

> Mouse input is also used by the player for aiming/interaction during gameplay.

---

## 🧰 Technology

PyLooter is built using:

- **Python**
- **Pygame CE 2.5.8**
- Object-oriented game architecture
- Modular entity systems
- Modular inventory systems
- Dedicated wave management
- Dedicated loot management
- Dedicated audio management
- Procedural rendering

---

## 🚧 Project Status

PyLooter is an actively developed project.

The current foundation includes:

- Core gameplay loop
- Player combat
- Enemy waves
- Projectile systems
- Collision detection
- XP progression
- Leveling
- Loot drops
- Inventory
- Player stat calculation
- Shield mechanics
- HP system
- Dash mechanics
- Audio
- Procedural space background
- HUD
- Pause system
- Game-over/restart system

More enemies, items, weapons, progression mechanics, and gameplay systems can be added as development continues.

---

## 📜 License

ALL RIGHTS RESERVED

```text
© 2026 NGeorge
```
