# Task 3 — Drawing Cards

## Description of the experiment

We consider a random experiment consisting of drawing cards from a **standard 52-card deck**.

A standard deck contains:

- **13 ranks**: A, 2, 3, 4, 5, 6, 7, 8, 9, 10, J, Q, K
- **4 suits**: hearts (♥), diamonds (♦), clubs (♣), spades (♠)

Thus the deck contains:

$$
52 = 13 \times 4
$$

distinct cards.

The **order of outcomes matters**, meaning that sequences such as `(A♠, K♦)` and `(K♦, A♠)` are considered different.

---

# 1. Sample space for drawing one card

The sample space contains all **52 possible cards** in the deck.

$$
\Omega_1 = \{\text{all 52 cards of the deck}\}
$$

### Example outcomes

| Card | Description       |
| ---- | ----------------- |
| A♠   | Ace of spades     |
| 7♦   | Seven of diamonds |
| Q♥   | Queen of hearts   |
| 10♣  | Ten of clubs      |

### Number of elementary outcomes

$|\Omega_1| = 52$

---

# 2. Sample space for two draws **with replacement**

With **replacement**, the card is returned to the deck before the second draw.

Therefore the second draw again has **52 possible outcomes**.

An outcome is an **ordered pair of cards**.

Example outcomes:

- `(A♠, K♦)`
- `(10♣, 10♣)`
- `(7♥, Q♠)`

### Number of elementary outcomes

$$
|\Omega_2| = 52 \times 52 = 52^2 = 2704
$$

---

# 3. Sample space for two draws **without replacement**

Without replacement, the first card is **not returned** to the deck.

Therefore:

- first draw → 52 possibilities
- second draw → 51 possibilities

Example outcomes:

- `(A♠, K♦)`
- `(10♣, 7♠)`
- `(Q♥, 3♦)`

Note that outcomes like `(A♠, A♠)` are **not possible**, because the same physical card cannot appear twice.

### Number of elementary outcomes

$$
|\Omega_2'| = 52 \times 51 = 2652
$$

---

# 4. Comparison of the number of outcomes

| Experiment                      | Number of outcomes |
| ------------------------------- | ------------------ |
| One card                        | 52                 |
| Two cards (with replacement)    | 2704               |
| Two cards (without replacement) | 2652               |

The difference occurs because **without replacement the deck becomes smaller after the first draw**.

---

# 5. Meaning of an elementary outcome

An **elementary outcome** represents one **complete ordered sequence of drawn cards**.

Examples:

| Experiment                      | Elementary outcome | Meaning                                                  |
| ------------------------------- | ------------------ | -------------------------------------------------------- |
| One draw                        | `A♠`               | the card drawn is the ace of spades                      |
| Two draws (with replacement)    | `(10♣, 10♣)`       | the same card appears in both draws                      |
| Two draws (without replacement) | `(K♦, 7♥)`         | first card king of diamonds, second card seven of hearts |

Therefore, an elementary outcome is a **specific ordered sequence of cards drawn from the deck**.
