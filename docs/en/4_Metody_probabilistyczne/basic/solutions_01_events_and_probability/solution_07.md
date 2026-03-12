# Task 7 — Events and Probabilities in Die Rolling

In this experiment we roll a **fair six-sided die**.

Possible outcomes:

$$
\Omega_1 = \{1,2,3,4,5,6\}
$$

Since the die is fair, each outcome has probability:

$$
P(i) = \frac{1}{6}, \quad i \in \{1,2,3,4,5,6\}
$$

---

# 1. One die roll

### Event A₁ — the result is even

Possible outcomes:

$$
A_1 = \{2,4,6\}
$$

Number of favorable outcomes: **3**

$$
P(A_1) = \frac{3}{6} = \frac{1}{2}
$$

---

### Event B₁ — the result is greater than 4

Possible outcomes:

$$
B_1 = \{5,6\}
$$

Number of favorable outcomes: **2**

$$
P(B_1) = \frac{2}{6} = \frac{1}{3}
$$

---

### Event C₁ — the result is at most 3

Possible outcomes:

$$
C_1 = \{1,2,3\}
$$

Number of favorable outcomes: **3**

$$
P(C_1) = \frac{3}{6} = \frac{1}{2}
$$

---

# 2. Two die rolls

Sample space contains:

$$
|\Omega_2| = 6^2 = 36
$$

equally likely ordered pairs.

---

### Event A₂ — the sum of the results equals 7

Possible outcomes:

- `(1,6)`
- `(2,5)`
- `(3,4)`
- `(4,3)`
- `(5,2)`
- `(6,1)`

Number of favorable outcomes: **6**

$$
P(A_2) = \frac{6}{36} = \frac{1}{6}
$$

---

### Event B₂ — both results are the same

Possible outcomes:

- `(1,1)`
- `(2,2)`
- `(3,3)`
- `(4,4)`
- `(5,5)`
- `(6,6)`

Number of favorable outcomes: **6**

$$
P(B_2) = \frac{6}{36} = \frac{1}{6}
$$

---

### Event C₂ — the sum of the results is at least 10

Possible outcomes:

- `(4,6)`
- `(5,5)`
- `(6,4)`
- `(5,6)`
- `(6,5)`
- `(6,6)`

Number of favorable outcomes: **6**

$$
P(C_2) = \frac{6}{36} = \frac{1}{6}
$$

---

# 3. Three die rolls

Sample space contains:

$$
|\Omega_3| = 6^3 = 216
$$

equally likely outcomes.

---

### Event A₃ — the sum of the results equals 10

Examples of favorable outcomes:

- `(1,3,6)`
- `(2,2,6)`
- `(3,3,4)`
- `(4,4,2)`
- `(5,3,2)`
- `(6,2,2)`

There are **27 possible outcomes** where the sum equals 10.

$$
P(A_3) = \frac{27}{216} = \frac{1}{8}
$$

---

### Event B₃ — exactly two rolls give the same number

Examples:

- `(2,2,3)`
- `(4,5,5)`
- `(6,1,6)`

To count these outcomes:

1. choose the number that appears twice
2. choose the different number
3. arrange the numbers in the sequence

Total favorable outcomes:

$$
150
$$

Probability:

$$
P(B_3) = \frac{150}{216}
$$

---

### Event C₃ — the outcomes contain two twos and one three

Possible ordered outcomes:

- `(2,2,3)`
- `(2,3,2)`
- `(3,2,2)`

Number of favorable outcomes: **3**

$$
P(C_3) = \frac{3}{216}
$$

---

# 4. Additional event

Define the event:

**D₃ — all three results are different**

Example outcomes:

- `(1,2,3)`
- `(4,5,6)`
- `(2,4,6)`

Number of favorable outcomes:

$$
6 \times 5 \times 4 = 120
$$

Probability:

$$
P(D_3) = \frac{120}{216}
$$
