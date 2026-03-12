# Task 4 — Weekly Weather Observation

## Description of the experiment

We observe the **weather once per day for seven consecutive days**.

Each day can be classified into exactly one of the following states:

- **S** — Sunny
- **C** — Cloudy
- **R** — Rainy

Since the weather is recorded every day, the outcome of the experiment is an **ordered sequence of daily weather observations**.

The **order matters**, because different sequences correspond to different weather patterns.

---

# 1. Sample space for one day

For a single day, the weather can be in one of three states.

$$
\Omega_1 = \{S, C, R\}
$$

### Table representation

| Outcome | Meaning |
| ------- | ------- |
| S       | Sunny   |
| C       | Cloudy  |
| R       | Rainy   |

### Number of elementary outcomes

$|\Omega_1| = 3$

---

# 2. Sample space for two consecutive days

When observing the weather for **two days**, the outcome is an **ordered pair**.

Examples of possible outcomes:

- `(S,S)`
- `(S,R)`
- `(C,S)`
- `(R,C)`

### Sample space

$$
\Omega_2 =
\{(S,S),(S,C),(S,R),
(C,S),(C,C),(C,R),
(R,S),(R,C),(R,R)\}
$$

### Number of elementary outcomes

$|\Omega_2| = 3^2 = 9$

---

# 3. Sample space for seven consecutive days

When observing the weather for **seven days**, the outcome is an **ordered sequence of seven symbols**, each representing the weather on a given day.

Example outcomes:

- `(S,S,C,R,S,C,S)`
- `(R,R,C,S,S,R,C)`
- `(C,C,C,S,R,S,R)`

### Sample space

$$
\Omega_7 =
\{(x_1,x_2,x_3,x_4,x_5,x_6,x_7) \mid x_i \in \{S,C,R\}\}
$$

Each position in the sequence can take one of the three values:

- S
- C
- R

---

# 4. Number of elementary outcomes

Since each day has **3 possible weather states**, the total number of possible weekly sequences is:

$$
|\Omega_7| = 3^7 = 2187
$$

### Summary

| Observation period | Number of outcomes |
| ------------------ | ------------------ |
| One day            | 3                  |
| Two days           | 9                  |
| Seven days         | 2187               |

---

# 5. Meaning of an elementary outcome

An **elementary outcome** represents one **complete weather sequence for the entire week**.

Examples:

| Observation | Elementary outcome | Meaning                                          |
| ----------- | ------------------ | ------------------------------------------------ |
| One day     | `S`                | the day is sunny                                 |
| Two days    | `(C,R)`            | cloudy on the first day, rainy on the second day |
| Seven days  | `(S,C,R,S,S,C,R)`  | specific weather pattern for the entire week     |

Therefore, an elementary outcome is a **specific ordered sequence of weather states observed during the week**.
