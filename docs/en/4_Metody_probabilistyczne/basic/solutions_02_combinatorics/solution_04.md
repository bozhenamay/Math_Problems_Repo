# Task 4 — Circular Permutations

## 1. Seating 7 people around a round table

**Problem:**  
In how many ways can 7 people sit around a round table?

**Model:** Circular permutation

**Formula:**

$$
(7 - 1)! = 6!
$$

**Explanation of the formula:**

If the people were sitting in a row, we would have:

$$
7!
$$

But in a circle, rotations do not create new arrangements.

Example:

- A B C D E F G
- B C D E F G A

These are the same seating.

So each arrangement is counted 7 times (once for each rotation).

To fix this, we divide by 7:

$$
\frac{7!}{7} = 6!
$$

**Final result:**

$$
6! = 720
$$

---

## 2. Seating 7 people where two particular people must sit next to each other

**Problem:**  
In how many ways can 7 people sit around a round table if two particular people must sit next to each other?

**Model:** Circular permutation with grouping

**Formula:**

$$
(6 - 1)! \cdot 2! = 5! \cdot 2!
$$

**Explanation of the formula:**

Step 1: Treat the two people as one block

Now we have:

- 5 other people
- 1 block

Total = 6 objects

Arrange them in a circle:

$$
(6 - 1)! = 5!
$$

Step 2: Arrange the two people inside the block:

$$
2!
$$

Total:

$$
5! \cdot 2!
$$

**Final result:**

$$
5! \cdot 2! = 120 \cdot 2 = 240
$$

---

## 3. Seating 7 people where two particular people must NOT sit next to each other

**Problem:**  
In how many ways can 7 people sit around a round table if two particular people must not sit next to each other?

**Model:** Complement counting

**Formula:**

$$
6! - 5! \cdot 2!
$$

**Explanation of the formula:**

Step 1: Count all possible circular arrangements:

$$
6!
$$

Step 2: Count arrangements where the two people ARE together

From Task 2:

$$
5! \cdot 2!
$$

Step 3: Subtract:

$$
6! - 5! \cdot 2!
$$

**Final result:**

$$
720 - 240 = 480
$$
