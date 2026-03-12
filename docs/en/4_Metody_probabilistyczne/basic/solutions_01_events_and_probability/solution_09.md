# Task 9 — Events and Probabilities in Weekly Weather Observation

We observe the weather for **seven consecutive days**.

Each day can be in one of three states:

- **S** — Sunny
- **C** — Cloudy
- **R** — Rainy

Each state occurs with probability:

$$
\frac{1}{3}
$$

The weather on different days is assumed to be **independent**.

---

# Sample space

Each day has **3 possible outcomes**.

For seven days:

$$
|\Omega_7| = 3^7 = 2187
$$

Each elementary outcome therefore has probability:

$$
\frac{1}{3^7}
$$

---

# Event A — the entire weekend is sunny

Weekend = **Saturday and Sunday**.

Probability that one day is sunny:

$$
P(S) = \frac{1}{3}
$$

Since the days are independent:

$$
P(A) = \frac{1}{3} \times \frac{1}{3}
$$

$$
P(A) = \frac{1}{9}
$$

---

# Event B — Wednesday, Thursday and Friday are rainy

Three specific days must be rainy.

$$
P(B) =
\left(\frac{1}{3}\right)^3
$$

$$
P(B) = \frac{1}{27}
$$

---

# Event C — at least one day during the week is sunny

It is easier to compute the complement.

Complement: **no sunny days occur**.

Possible states per day without sun:

- C
- R

Probability per day:

$$
\frac{2}{3}
$$

Probability for the entire week:

$$
\left(\frac{2}{3}\right)^7
$$

Thus:

$$
P(C) =
1 - \left(\frac{2}{3}\right)^7
$$

---

# Event D — no rainy day occurs during the entire week

Allowed states:

- S
- C

Probability per day:

$$
\frac{2}{3}
$$

Therefore:

$$
P(D) =
\left(\frac{2}{3}\right)^7
$$

---

# Event E — exactly two days during the week are sunny

We choose **2 sunny days out of 7**.

Number of possibilities:

$$
\binom{7}{2} = 21
$$

Probability that two chosen days are sunny:

$$
\left(\frac{1}{3}\right)^2
$$

Probability that the other five days are not sunny:

$$
\left(\frac{2}{3}\right)^5
$$

Thus:

$$
P(E) =
\binom{7}{2}
\left(\frac{1}{3}\right)^2
\left(\frac{2}{3}\right)^5
$$

---

# Additional event

Define event **F — all seven days have the same weather**.

Possible outcomes:

- `(S,S,S,S,S,S,S)`
- `(C,C,C,C,C,C,C)`
- `(R,R,R,R,R,R,R)`

There are **3 such outcomes**.

Each has probability:

$$
\left(\frac{1}{3}\right)^7
$$

Therefore:

$$
P(F) =
3 \times \left(\frac{1}{3}\right)^7
= \frac{3}{3^7}
= \frac{1}{3^6}
$$
