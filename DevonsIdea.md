# D2 — Full Game Design Document (GDD)
### A Team-Based Tactical Card Roguelite

---

## 1. Game Overview

### Summary
D2 is a team-based tactical card roguelite. Players assemble a squad of fixed-identity characters, each with unique abilities, passives, and roles. Instead of a single-hero deckbuilder, D2 uses shared action cards that any character can execute—with drastically different outcomes depending on who uses the card.

- Encounters occur on randomized roguelike maps.
- Runs consist of chapters (biomes), each with 6–10 nodes.
- Progression unlocks new characters, passives, and upgrades, while maintaining balance.

---

## 2. Core Pillars

- **Tactical Team Combat:** Control 2–4 characters; positioning affects effectiveness.  
- **Shared Action Cards:** Cards represent team actions; effects vary by user.  
- **Roguelike Map Structure:** Randomized, node-based progression.  
- **Strong Character Identity:** Each character has a defined role and kit.  
- **Replayability & Progression:** Highly variable runs, unlocks, and controlled buffs.

---

## 3. Core Gameplay Loop

1. Assemble Team: Pick 2–4 heroes with complementary roles.  
2. Start Run: Randomized map with branching nodes.  
3. Navigate Nodes: Choose between combat, events, shops, rests, artifacts, elites, bosses.  
4. Tactical Card Combat: Draw cards, assign to heroes, manage positioning.  
5. Earn Rewards: Choose cards, gain artifacts, upgrade cards, unlock bonuses.  
6. Continue Chapters: Difficulty escalates.  
7. Final Boss: Win the run.  
8. Account Progression: Unlock new characters, passives, skins, buffs, ascension levels.

---

## 4. Combat System

### 4.1 Turn Structure
- **Draw Phase:** Draw 3–5 cards (team traits affect count).  
- **Assignment Phase:** Choose which hero uses each card.  
- **Action Resolution:** Cards act based on character and position; enemies respond.  
- **Cleanup Phase:** Discard unused cards, apply end-of-turn passives.

### 4.2 Tactical Positioning
- **Frontline (positions 1–2):** Tanks gain defense.  
- **Backline (positions 3–4):** Supports gain effectiveness; rogues gain crit.  
- **Ranged:** Penalized in frontline.  
- **Enemies:** Follow positional rules (attack front, poison back, reposition team).

### 4.3 Card Types
- Universal Team Cards  
- Attack, Defense, Support, Utility, Wild Cards (random effects)

#### Example: “Strike” Card Effects

| Character     | Effect                                |
|---------------|----------------------------------------|
| Berserker     | Heavy damage, generates Fury           |
| Medic         | Light strike + minor heal              |
| Rogue         | Strike twice, low damage               |
| Elementalist  | Adds burn stacks                       |
| Guardian      | Applies shield equal to % of damage    |

### 4.4 Character Abilities
- 1 Passive Ability  
- 1 Signature Active Ability (cooldown-based)  
- Core Stats: HP, Power, Defense, Speed  
- Role Identity (e.g., Berserker, Guardian, Elementalist, Rogue, Medic)

---

## 5. Characters (Roster Identity)

- Fixed-kit champions (no talent trees or RPG stats)  
- Unlock alternate passives (e.g., “Gain 1 Fury when damaged” vs. “Gain 1 Fury when using a Support card”)  
- Alternate passives change playstyle, not identity.

---

## 6. Encounters & Map System

### 6.1 Chapter Structure
- Node-based map (6–10 nodes)  
- Branching options  

### 6.2 Node Types
- **Combat:** Standard, Elite, Boss  
- **Reward:** Treasure, Artifact Chamber, Ability Shrine, Card Forge  
- **Utility:** Rest Point, Tavern, Shop  
- **Event:** Mini story, RNG, risk/reward, party reactions

### 6.3 Map Shapes
- Linear  
- Branching  
- Webbed (Slay the Spire style)  
- Open  
- Multi-lane convergence  

### 6.4 Boss Encounters
- Unique mechanics, position manipulation, status effects, enrage timers, multiple phases  
- Rewards: Major artifacts, permanent boosts, unlocks  

---

## 7. Progression Systems

- **Short-term (Within Run):** Temporary boosts, artifacts, upgrades, synergy modifiers, event outcomes.  
- **Medium-term (Roster):** Unlock characters, passives, synergies, card variants, artifacts.  
- **Long-term (Meta):** Account-wide bonuses (e.g., HP bonuses, redraws, ascension difficulty).

---

## 8. Difficulty & Ascension System

- Ascension levels unlock after wins.  
- Modifiers: Harder AI, extra curses, deadlier elites, longer maps, boss modifications.  
- Ascension cap: **~20–25**.

---

## 9. Enemy Design

- **Types:** Bruisers, Poisoners, Multi-strikers, Casters, Summoners, Position manipulators, Shielders, Debuffers  
- **Elites:** Add modifiers, suppress synergies, drop high-tier artifacts  
- **Boss Mechanics:** Rotating shields, summon waves, reverse positions, punish repeated cards, burn deck  

---

## 10. Cards & Deck-Building

- Deck size: **10–15 cards**  
- Clean effects; complexity emerges from hero interactions  
- Acquisition: Choose 1 of 3 after fights, shop, events, boss rewards  
- Upgrades: Numerical boosts, optional added effects, positional modifiers  

---

## 11. Artifacts, Relics & Items

- Artifacts significantly alter runs  
- Types: team artifacts, character artifacts, positional artifacts, deck relics  
- Purpose: **flashy power moments**  

---

## 12. Economy & Rewards

- **Currencies:** Gold, meta-shards (permanent unlocks), cosmetic currency  

---

## 13. Visual & Audio Identity

- Stylized 2D/2.5D  
- Clean iconography, strong silhouettes  
- UX: Fast turns, clear UI, drag-and-drop/tap card assignment, tactical grid  

---

## 14. Future Roadmap

1. Combat prototype  
2. Map & node system  
3. Characters & synergy  
4. Boss & enemy design  
5. Meta progression  
6. UI/UX refinement  
7. Full content release  