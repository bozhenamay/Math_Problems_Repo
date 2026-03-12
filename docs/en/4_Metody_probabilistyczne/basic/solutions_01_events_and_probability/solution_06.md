# Task 6 — Events and Probabilities in Coin Tossing

In this experiment we consider tossing a **fair coin**.

Possible outcomes:

- **H** — Heads
- **T** — Tails

Since the coin is fair, **all elementary outcomes are equally likely**.

---

# 1. Probabilities of elementary outcomes

## One coin toss

Sample space:

$$
\Omega_1 = \{H, T\}
$$

Each outcome has probability:

$$
P(H) = P(T) = \frac{1}{2}
$$

---

## Two coin tosses

Sample space:

$$
\Omega_2 = \{(H,H),(H,T),(T,H),(T,T)\}
$$

Since there are 4 equally likely outcomes:

$$
P(\omega) = \frac{1}{4} \quad \text{for each } \omega \in \Omega_2
$$

---

## Three coin tosses

Sample space:

$$
\Omega_3 =
\{(H,H,H),(H,H,T),(H,T,H),(H,T,T),
(T,H,H),(T,H,T),(T,T,H),(T,T,T)\}
$$

There are 8 outcomes, therefore:

$$
P(\omega) = \frac{1}{8}
$$

for each elementary outcome.

---

# 2. Events for one coin toss

### Event A₁ — the result is heads

$$
A_1 = \{H\}
$$

Probability:

$$
P(A_1) = \frac{1}{2}
$$

---

### Event B₁ — the result is tails

$$
B_1 = \{T\}
$$

Probability:

$$
P(B_1) = \frac{1}{2}
$$

---

### Event C₁ — the result is not tails

This event is equivalent to getting heads.

$$
C_1 = \{H\}
$$

Probability:

$$
P(C_1) = \frac{1}{2}
$$

---

# 3. Events for two coin tosses

Sample space:

$$
\Omega_2 = \{(H,H),(H,T),(T,H),(T,T)\}
$$

---

### Event A₂ — exactly one head occurs

Possible outcomes:

$$
A_2 = \{(H,T),(T,H)\}
$$

Number of favorable outcomes: **2**

$$
P(A_2) = \frac{2}{4} = \frac{1}{2}
$$

---

### Event B₂ — at least one head occurs

Possible outcomes:

$$
B_2 = \{(H,H),(H,T),(T,H)\}
$$

Number of favorable outcomes: **3**

$$
P(B_2) = \frac{3}{4}
$$

---

### Event C₂ — both tosses give the same result

Possible outcomes:

$$
C_2 = \{(H,H),(T,T)\}
$$

Number of favorable outcomes: **2**

$$
P(C_2) = \frac{2}{4} = \frac{1}{2}
$$

---

# 4. Events for three coin tosses

Sample space contains **8 outcomes**.

---

### Event A₃ — exactly two heads occur

Possible outcomes:

$$
A_3 =
\{(H,H,T),(H,T,H),(T,H,H)\}
$$

Number of favorable outcomes: **3**

$$
P(A_3) = \frac{3}{8}
$$

---

### Event B₃ — at least one tail occurs

The only outcome without tails is:

`(H,H,H)`

Therefore:

$$
B_3 = \Omega_3 \setminus \{(H,H,H)\}
$$

Number of favorable outcomes: **7**

$$
P(B_3) = \frac{7}{8}
$$

---

### Event C₃ — all three tosses give the same result

Possible outcomes:

$$
C_3 = \{(H,H,H),(T,T,T)\}
$$

Number of favorable outcomes: **2**

$$
P(C_3) = \frac{2}{8} = \frac{1}{4}
$$

---

# 5. Additional event

Define the event:

**D₃ — exactly one head occurs**

Possible outcomes:

$$
D_3 =
\{(H,T,T),(T,H,T),(T,T,H)\}
$$

Number of favorable outcomes: **3**

$$
P(D_3) = \frac{3}{8}
$$
