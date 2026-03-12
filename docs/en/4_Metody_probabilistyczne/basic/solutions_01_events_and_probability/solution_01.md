# Task 1 — Coin Tossing

## Description of the experiment

We consider a random experiment consisting of tossing a **fair coin**.  
Each toss can result in one of two outcomes:

- **H** — Heads
- **T** — Tails

The **order of outcomes matters**, meaning that sequences such as `(H,T)` and `(T,H)` are considered **different elementary outcomes**.

---

# 1. Sample space for one coin toss

The **sample space** contains all possible outcomes of the experiment.

For a single coin toss we have two possible outcomes.

$$
\Omega_1 = \{H, T\}
$$

### Table representation

| Outcome | Description |
| ------- | ----------- |
| `H`     | Heads       |
| `T`     | Tails       |

### Number of elementary outcomes

$$
|\Omega_1| = 2
$$

---

# 2. Sample space for two coin tosses

When tossing the coin **twice**, the result is an **ordered pair** of outcomes.

### Tree diagram

```
Start
 ├── H
 │    ├── H → (H,H)
 │    └── T → (H,T)
 │
 └── T
      ├── H → (T,H)
      └── T → (T,T)
```

### Sample space

$$
\Omega_2 =
\{(H,H), (H,T), (T,H), (T,T)\}
$$

### Table representation

| Outcome | Description    |
| ------- | -------------- |
| `(H,H)` | two heads      |
| `(H,T)` | head then tail |
| `(T,H)` | tail then head |
| `(T,T)` | two tails      |

### Number of elementary outcomes

$$
|\Omega_2| = 4
$$

---

# 3. Sample space for three coin tosses

For three tosses the outcome is an **ordered triple**.

### Tree diagram

```
Start
 ├── H
 │    ├── H
 │    │    ├── H → (H,H,H)
 │    │    └── T → (H,H,T)
 │    │
 │    └── T
 │         ├── H → (H,T,H)
 │         └── T → (H,T,T)
 │
 └── T
      ├── H
      │    ├── H → (T,H,H)
      │    └── T → (T,H,T)
      │
      └── T
           ├── H → (T,T,H)
           └── T → (T,T,T)
```

### Sample space

$$
\Omega_3 =
\{(H,H,H), (H,H,T), (H,T,H), (H,T,T),
(T,H,H), (T,H,T), (T,T,H), (T,T,T)\}
$$

### Table representation

| Outcome   | Description      |
| --------- | ---------------- |
| `(H,H,H)` | three heads      |
| `(H,H,T)` | head, head, tail |
| `(H,T,H)` | head, tail, head |
| `(H,T,T)` | head, tail, tail |
| `(T,H,H)` | tail, head, head |
| `(T,H,T)` | tail, head, tail |
| `(T,T,H)` | tail, tail, head |
| `(T,T,T)` | three tails      |

### Number of elementary outcomes

$$
|\Omega_3| = 8
$$

---

# 4. Number of elementary outcomes

| Experiment   | Number of outcomes |
| ------------ | ------------------ |
| One toss     | 2                  |
| Two tosses   | 4                  |
| Three tosses | 8                  |

In general, for **n coin tosses**:

$$
|\Omega_n| = 2^n
$$

because each toss has **two possible outcomes**.

---

# 5. Meaning of an elementary outcome

An **elementary outcome** represents one **complete possible result** of the experiment.

Examples:

| Experiment   | Elementary outcome | Meaning                             |
| ------------ | ------------------ | ----------------------------------- |
| One toss     | `H`                | the coin shows heads                |
| Two tosses   | `(H,T)`            | first toss heads, second toss tails |
| Three tosses | `(T,H,H)`          | tail, then two heads                |

Therefore, an elementary outcome is a **specific ordered sequence of results** for the entire experiment.
