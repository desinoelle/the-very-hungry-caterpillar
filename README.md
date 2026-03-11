# 🐛 The Very Hungry Caterpillar

A cutesy puzzle game based on the beloved children's book by Eric Carle, built in **PuzzleScript**.

The gameplay is similar to Snake, except the caterpillar's body expands on *every move* — not just
when eating. Players must consume all fruit on the board without running into walls or trapping
themselves, all within a limited number of moves.

The game features two modes: **Story Mode** (lighthearted, introductory) and **Hard Mode**
(challenging mechanics that build on everything learned in Story Mode).

🎮 **[[Play it here](#)] -> (https://www.puzzlescript.net/play.html?p=46a8a407dd664985ab3f8e38170c0139)**

---

## 🕹️ Core Mechanics

- The caterpillar's body expands on every move
- All fruit must be consumed within a limited move count to progress

---

## ✨ Special Mechanics

| Mechanic | Description |
|---|---|
| **Directional Eating** | Certain fruit must be eaten from a specific direction — cherries from the left, pears from the top |
| **Growth Plums** | Eating a plum makes the caterpillar grow wider — eat too early and you may block yourself in |
| **Ripening Fruit** | Some fruit must be waited on before they can be eaten — bananas ripen in 3 moves, apples in 5 |

---

## 📋 Level Progression

### Story Mode
| Level | Objective | Move Limit |
|---|---|---|
| 1 | Consume 1 apple | 11 |
| 2 | Consume 2 pears | 21 |
| 3 | Consume 3 plums | 24 |
| 4 | Consume 4 strawberries | 35 |
| 5 | Consume 5 oranges | 35 |
| 6 | Consume various junk foods | 39 |
| 7 | Consume 1 leaf | 35 |

### Hard Mode
| Level | Objective | Move Limit |
|---|---|---|
| 1 | 1 cherry (left), 1 pear (top), 3 strawberries | 35 |
| 2 | 1 growth plum, 2 strawberries | 35 |
| 3 | 1 ripening banana, 1 ripening apple | 27 |
| 4 | 1 ripening banana, 1 ripening apple, 3 cherries (left), 2 pears (top) | 33 |
| 5 | 1 ripening apple, 1 strawberry, 1 growth plum, 1 pear (top), 1 cherry (left) | 33 |
| 6 | 1 ripening banana, 1 ripening apple, 1 growth plum, 1 cherry (left), 1 pear (top) | 33 |

---

## 🛠️ Built With

- [PuzzleScript](https://www.puzzlescript.net/) — an open-source HTML5 puzzle
