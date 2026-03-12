# Task 2 — Rolling a Die

## Description of the experiment

We consider a random experiment consisting of rolling a **fair six-sided die**.

Each roll can result in one of the following outcomes:

- **1**
- **2**
- **3**
- **4**
- **5**
- **6**

The **order of outcomes matters** when the die is rolled multiple times.

---

# 1. Sample space for one roll of the die

The **sample space** contains all possible outcomes of the experiment.

For a single roll we have:

$$
\Omega_1 = \{1,2,3,4,5,6\}
$$

### Table representation

| Outcome | Description |
| ------- | ----------- |
| 1       | die shows 1 |
| 2       | die shows 2 |
| 3       | die shows 3 |
| 4       | die shows 4 |
| 5       | die shows 5 |
| 6       | die shows 6 |

### Number of elementary outcomes

$|\Omega_1| = 6$

---

# 2. Sample space for two consecutive rolls

When rolling the die **twice**, the outcome is an **ordered pair**.

### Tree diagram

```
Start
 ├── 1 → (1,1) (1,2) (1,3) (1,4) (1,5) (1,6)
 ├── 2 → (2,1) (2,2) (2,3) (2,4) (2,5) (2,6)
 ├── 3 → (3,1) (3,2) (3,3) (3,4) (3,5) (3,6)
 ├── 4 → (4,1) (4,2) (4,3) (4,4) (4,5) (4,6)
 ├── 5 → (5,1) (5,2) (5,3) (5,4) (5,5) (5,6)
 └── 6 → (6,1) (6,2) (6,3) (6,4) (6,5) (6,6)
```

### Sample space

$$
\Omega_2 =
\{(1,1),(1,2),(1,3),(1,4),(1,5),(1,6),
(2,1),(2,2),(2,3),(2,4),(2,5),(2,6),
(3,1),(3,2),(3,3),(3,4),(3,5),(3,6),
(4,1),(4,2),(4,3),(4,4),(4,5),(4,6),
(5,1),(5,2),(5,3),(5,4),(5,5),(5,6),
(6,1),(6,2),(6,3),(6,4),(6,5),(6,6)\}
$$

### Number of elementary outcomes

$|\Omega_2| = 6^2 = 36$

---

# 3. Sample space for three consecutive rolls

When rolling the die **three times**, the outcome is an **ordered triple**.

Examples of elementary outcomes:

- `(1,1,1)`
- `(2,3,5)`
- `(6,4,2)`
- `(3,3,6)`

### Sample space

$$
\Omega_3 =
\{(i,j,k) \mid i,j,k \in \{1,2,3,4,5,6\}\}
$$

This means that each position of the triple can take any value from 1 to 6.

### Number of elementary outcomes

$|\Omega_3| = 6^3 = 216$

---

# 4. Number of elementary outcomes

| Experiment  | Number of outcomes |
| ----------- | ------------------ |
| One roll    | 6                  |
| Two rolls   | 36                 |
| Three rolls | 216                |

In general, for **n rolls of a die**:

$$
|\Omega_n| = 6^n
$$

because each roll has **six possible outcomes**.

---

# 5. Meaning of an elementary outcome

An **elementary outcome** represents one **complete possible result** of the experiment.

Examples:

| Experiment  | Elementary outcome | Meaning                         |
| ----------- | ------------------ | ------------------------------- |
| One roll    | `4`                | the die shows 4                 |
| Two rolls   | `(2,5)`            | first roll 2, second roll 5     |
| Three rolls | `(3,1,6)`          | the die shows 3, then 1, then 6 |

Therefore, an elementary outcome is a **specific ordered sequence of results** for the entire experiment.
