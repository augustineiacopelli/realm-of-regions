# Realm of Regions

**A browser RPG designed and created by Simon Iacopelli.**

Built entirely from Simon's hand-written design notes — every enemy, boss, region, item, and rule comes directly from his original vision.

---

## How to Play

1. Enter your name and begin your adventure with 10 gold and 3 Potions.
2. Travel through four regions: **Forest**, **Mountain**, **Lava**, and **Frost**.
3. Fight enemies to earn XP and gold, level up, and grow stronger.
4. Defeat each region's boss to unlock the next region.
5. Defeat the **Frost Wizard** to complete the game — then keep exploring if you want!

---

## Battle System

Each turn you choose one of six actions:

- **Attack** — deal damage using your ATK stat
- **Magic** — spend 5 MP for a harder hit using your MAG stat
- **Defend** — block all incoming damage and reflect 10 damage back (limited to 10 uses per battle)
- **Item** — choose a healing item from your bag; the enemy gets confused and misses their turn
- **ACT** — learn about the enemy and make them miss their turn; also unlocks Spare
- **Spare** — after using ACT, let a regular enemy flee peacefully (bosses will instantly KO you for trying)

---

## Features

- **4 Regions** with unique enemies, each with their own HP and attack power
- **8 Bosses** — one regular boss and one secret boss per region, each with dramatic last words when defeated
- **Secret Boss unlock** — defeat 3 enemies in a region without dying to unlock the secret boss
- **11 Level system** — XP curve doubles each level; each level up restores full HP and grants +20 max HP
- **4 Player stats** — Attack, Magic, Power, and Defense
- **Full Item Store** with 14 items including weapons, armor, and healing food
- **Item picker in battle** — choose exactly which item to use mid-fight
- **Inn** — rest for 15g to fully restore HP and MP
- **Sound effects** — Web Audio API sounds for every battle action
- **Save system** — progress saved to localStorage
- **Post-game play** — after beating the game, keep grinding enemies and bosses (Frost and Void Wizards rest in peace)

---

## Regions & Bosses

| Region | Enemies | Boss | Secret Boss |
|--------|---------|------|-------------|
| Forest | Slime, Lizard, Forest Skeleton, Rose, Tree Imp, Flower Petal | Forest Wizard (36 HP) | Shadow Wizard (80 HP) |
| Mountain | Skeleton, Cloud, Sky Knight, Mountain Lion | Mountain Wizard (44 HP) | Storm Wizard (100 HP) |
| Lava | Flame, Obsidian Golem, Flame Dragon, Fire Knight | Flare Wizard (60 HP) | Inferno Wizard (120 HP) |
| Frost | Ice Slime, Frozen Skeleton, Igloo, Ice Golem, Ice Dragon | Frost Wizard (250 HP) | Void Wizard (300 HP) |

---

## Item Store

| Item | Cost | Effect |
|------|------|--------|
| Potion | 20g | Recover 10 HP |
| Sword | 50g | +5 Attack |
| Potion Ultimate | 50g | Recover 30 HP |
| Bagel | 80g | Recover 15 HP |
| Chest Plate | 120g | +5 Defense |
| Hotdog | 200g | Recover 45 HP |
| Cheddar | 150g | Recover 20 HP |
| Iron Sword | 70g | +5 Attack |
| Magic Tome 1 | 150g | +4 Magic |
| Magic Tome 2 | 250g | +7 Magic |
| Magic Tome 3 | 390g | +13 Magic |
| Dragon Plate | 40g | +10 Defense |
| Dum Dum | 60g | Recover 50 HP |

---

## Credits

**Game Design:** Simon Iacopelli
**Development:** Built with HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies
