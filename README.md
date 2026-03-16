# CMPSC 421 – Homework 1

### JavaScript and DOM Manipulation

This project contains two browser-based games implemented using **JavaScript** and **DOM manipulation**:

* 🎲 **Pig (Dice Game)**
* 🃏 **Go Fish (Card Game)**

Both games are played between a **human player and a CPU opponent** and demonstrate JavaScript concepts such as event handling, randomness, conditional logic, and dynamic DOM updates.


# 🎲 Game 1 – Pig (25 pts)

## Overview

Pig is a turn-based dice game where players attempt to reach **100 points** by rolling a six-sided die.

## Rules

* Players take turns rolling a **six-sided die (1–6)**.
* If a player rolls **2–6**, the value is added to their **turn score**.
* If the player rolls **1**, the turn ends and **all points from that turn are lost**.
* The player can choose to:

  * **Roll again**
  * **Pass**, which adds the turn total to their overall score.

## Example

**Example 1**

```
Rolls: 3 → 5 → 6
Turn total = 14
Player passes
Score +14
```

**Example 2**

```
Rolls: 6 → 2 → 1
Turn ends immediately
Points gained = 0
```

## Gameplay

* Human player chooses whether to **roll or pass**.
* CPU randomly decides whether to **roll again or end its turn**.
* The first player to reach **100 points wins**.

---

# 🃏 Game 2 – Go Fish (75 pts)

## Overview

Go Fish is a card game where players request cards of a specific **rank** from their opponent.

## Setup

* **2 players**: Human vs CPU
* Each player starts with **5 cards**.
* Remaining cards are placed in a **draw pile**.

## Rules

1. On a turn, a player asks the opponent for a card rank.

Example:

```
Do you have any sevens?
```

2. If the opponent **has the requested cards**:

   * They must give **all matching cards** to the player.

3. If the opponent **does not have the cards**:

   * The player must **draw a card from the deck** ("Go Fish").

4. CPU behavior:

   * The CPU **randomly chooses a card rank** to request.

5. If additional cards are needed, **multiple decks may be used**.

## Winning Condition

The **first player to have zero cards remaining** wins the game.

---

# 🖥️ Technologies Used

* **HTML**
* **CSS**
* **JavaScript**
* **DOM Manipulation**

Optional:

* **jQuery** (if implemented)

---

# 🃏 Card Assets

Playing card images can be obtained from:

https://github.com/hayeah/playing-cards-assets

---
