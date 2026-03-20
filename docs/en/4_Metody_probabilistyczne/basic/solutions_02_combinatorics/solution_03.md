# Task 3 — Permutations with Repeated Elements

## 1. Arrangements of MISSISSIPPI

**Problem:**  
How many distinct arrangements of the word MISSISSIPPI are possible?

**Model:** Permutation with repeated elements

**Formula:**

$$
\frac{11!}{4! \cdot 4! \cdot 2!}
$$

**Explanation of the formula:**

The word MISSISSIPPI has 11 letters.

Count repetitions:

- M = 1
- I = 4
- S = 4
- P = 2

If all letters were different, we would have:

$$
11!
$$

But identical letters create duplicate arrangements:

- The 4 I’s can be rearranged in \(4!\) ways
- The 4 S’s in \(4!\) ways
- The 2 P’s in \(2!\) ways

Each arrangement is counted:

$$
4! \cdot 4! \cdot 2!
$$

times too many.

So we divide:

$$
\frac{11!}{4! \cdot 4! \cdot 2!}
$$

**Final result:**

$$
\frac{39916800}{24 \cdot 24 \cdot 2} = 34650
$$

---

## 2. Arrangements of STATISTICS

**Problem:**  
How many distinct arrangements of the word STATISTICS are possible?

**Model:** Permutation with repeated elements

**Formula:**

$$
\frac{10!}{3! \cdot 3! \cdot 2!}
$$

**Explanation of the formula:**

The word STATISTICS has 10 letters.

Count repetitions:

- S = 3
- T = 3
- I = 2
- A = 1
- C = 1

If all letters were different:

$$
10!
$$

But identical letters create duplicates:

- 3! for S
- 3! for T
- 2! for I

So we divide:

$$
\frac{10!}{3! \cdot 3! \cdot 2!}
$$

**Final result:**

$$
\frac{3628800}{6 \cdot 6 \cdot 2} = 50400
$$

---

## 3. Arrangements of STATISTICS starting with S

**Problem:**  
How many arrangements of STATISTICS start with the letter S?

**Model:** Permutation with repeated elements (with restriction)

**Formula:**

$$
\frac{9!}{2! \cdot 3! \cdot 2!}
$$

**Explanation of the formula:**

We fix the first letter as S.

Remaining letters:

- S = 2
- T = 3
- I = 2
- A = 1
- C = 1

Total remaining letters = 9

If all were different:

$$
9!
$$

But we still have repeated letters:

- 2! for S
- 3! for T
- 2! for I

So:

$$
\frac{9!}{2! \cdot 3! \cdot 2!}
$$

**Final result:**

$$
\frac{362880}{2 \cdot 6 \cdot 2} = 15120
$$
