
#  TinySwords: Final Project PBO

**TinySwords** is a 2D Action RPG developed in **Unreal Engine 5**. Created as a final project for Object-Oriented Programming (PBO), this game serves as a comprehensive demonstration of OOP architecture applied to complex game logic, state management, and combat systems.

##  Gameplay Overview
Set in a vibrant pixel-art world, players survive waves of enemies, utilizing class-specific skills and strategic power-ups to progress.

###  Choose Your Hero
Players can select from three distinct classes, each possessing **3 unique skills** tailored to different playstyles:
* **The Knight:** A melee powerhouse with high durability and close-range combat skills.
* **The Mage:** A master of elements who controls the battlefield with AoE (Area of Effect) spells.
* **The Archer:** A ranged specialist focusing on precision and keeping distance from threats.

###  Tactical Enemy AI
Face off against **3 unique Goblin variants**, each challenging the player with distinct bomb-throwing abilities and attack patterns. Players must learn to dodge and counter specific bomb types to survive.

###  Roguelite Progression
* **Round-Based Survival:** Survive waves of enemies to advance.
* **Power-Up System:** At the end of every round, players are presented with a choice of random power-ups to upgrade their stats or abilities, making every run unique.

---

##  Technical Implementation: Complete OOP Showcase
This project goes beyond basic scripting to demonstrate a robust **Object-Oriented Programming** architecture:

* **Inheritance:** Utilizes a hierarchical class structure for `BaseCharacter` (parent) extended into `Knight`, `Mage`, and `Archer` (children), sharing core logic while specializing attributes. Similarly applied to `BaseEnemy` and the specific Goblin types.
* **Polymorphism:** Implements method overriding for the Skill System. A generic `CastSkill()` function behaves differently depending on whether the instance is a Knight (swing sword), Archer (shoot arrow), or Mage (cast spell).
* **Encapsulation:** Player stats (Health, Mana, Stamina) and Game State are strictly protected, accessible only through defined getters and setters to prevent invalid states and ensure data integrity.
* **Abstraction:** Uses abstract classes and interfaces to handle complex systems like the *Damage Interface* and *Power-Up Manager*, decoupling the implementation details from the high-level game logic.

---

##  Built With

* **Engine:** Unreal Engine 5
* **Core Logic:** C++ & Blueprints (Hybrid OOP Approach)
* **Visual Assets:** Tiny Swords

---
