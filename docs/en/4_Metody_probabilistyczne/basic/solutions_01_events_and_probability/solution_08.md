# Task 8 — Events and Probabilities in Card Drawing

We consider drawing cards from a **standard 52-card deck**.

The deck contains:

- **4 suits**: ♥ ♦ ♣ ♠
- **13 ranks**: A,2,3,4,5,6,7,8,9,10,J,Q,K

Thus:

$$
52 = 4 \times 13
$$

All ordered sequences of draws are assumed to be **equally likely**.

---

# 1. One card drawn

Sample space:

$$
|\Omega_1| = 52
$$

---

### Event A₁ — the card is a heart

There are **13 hearts** in the deck.

$$
P(A_1) = \frac{13}{52} = \frac{1}{4}
$$

---

### Event B₁ — the card is a king

There are **4 kings** in the deck.

$$
P(B_1) = \frac{4}{52} = \frac{1}{13}
$$

---

### Event C₁ — the card is not a face card

Face cards are:

- J
- Q
- K

There are:

$$
3 \times 4 = 12
$$

face cards.

Non-face cards:

$$
52 - 12 = 40
$$

Probability:

$$
P(C_1) = \frac{40}{52} = \frac{10}{13}
$$

---

# 2. Two cards drawn (with replacement)

Sample space:

$$
|\Omega_2| = 52^2 = 2704
$$

---

### Event A₂ — both cards are hearts

Probability of heart on one draw:

$$
\frac{13}{52} = \frac{1}{4}
$$

Since the card is replaced, the draws are **independent**:

$$
P(A_2) = \frac{1}{4} \times \frac{1}{4} = \frac{1}{16}
$$

---

### Event B₂ — both cards have the same rank

First card: any rank.

Second card must match the rank of the first.

For example, if the first card is **7**, there are **3 remaining sevens**.

Thus:

$$
P(B_2) = \frac{3}{52}
$$

---

### Event C₂ — at least one card is an ace

Probability that a card is **not an ace**:

$$
\frac{48}{52} = \frac{12}{13}
$$

Probability that **no ace appears**:

$$
\left(\frac{12}{13}\right)^2
$$

Therefore:

$$
P(C_2) =
1 - \left(\frac{12}{13}\right)^2
$$

---

# 3. Two cards drawn (without replacement)

Sample space:

$$
|\Omega_2'| = 52 \times 51 = 2652
$$

---

### Event A₃ — both cards are hearts

First draw:

$$
\frac{13}{52}
$$

Second draw (one heart removed):

$$
\frac{12}{51}
$$

Therefore:

$$
P(A_3) =
\frac{13}{52} \times \frac{12}{51}
= \frac{1}{17}
$$

---

### Event B₃ — both cards have the same rank

After drawing the first card, **3 cards of the same rank remain** among **51 cards**.

Thus:

$$
P(B_3) = \frac{3}{51} = \frac{1}{17}
$$

---

### Event C₃ — one card is a king and the other is a queen

Two possibilities:

- King then Queen
- Queen then King

Number of kings = 4  
Number of queens = 4

Probability:

$$
P(C_3) =
\frac{4}{52} \times \frac{4}{51}
+
\frac{4}{52} \times \frac{4}{51}
$$

$$
P(C_3) =
2 \times \frac{16}{2652}
= \frac{32}{2652}
= \frac{8}{663}
$$

---

# 4. Additional event

Define event **D₃ — both cards are aces** (without replacement).

First draw:

$$
\frac{4}{52}
$$

Second draw:

$$
\frac{3}{51}
$$

Thus:

$$
P(D_3) =
\frac{4}{52} \times \frac{3}{51}
= \frac{12}{2652}
= \frac{1}{221}
$$
