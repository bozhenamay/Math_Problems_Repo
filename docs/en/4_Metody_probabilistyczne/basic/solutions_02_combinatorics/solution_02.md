# Task 2 — Permutations

## 1. Arranging 8 different books on a shelf

**Problem:**  
In how many ways can 8 different books be arranged on a shelf?

**Model:** Permutation

**Formula:**

$$
8!
$$

**Explanation of the formula:**  
We arrange the books one by one:

- 1st position → 8 choices
- 2nd → 7 choices
- ...
- last → 1 choice

So:

$$
8! = 8 \cdot 7 \cdot 6 \cdot 5 \cdot 4 \cdot 3 \cdot 2 \cdot 1
$$

**Final result:**

$$
8! = 40320
$$

---

## 2. Two particular people must sit next to each other

**Problem:**  
In how many ways can 8 people sit in a row if two particular people must sit next to each other?

**Model:** Permutation with grouping

**Formula:**

$$
7! \cdot 2!
$$

**Explanation of the formula:**

Step 1: Treat the two people as one block

Now we have:

- 6 other people
- 1 block

So 7 objects total → arrange:

$$
7!
$$

Step 2: Arrange the two people inside the block

They can switch places:

$$
2!
$$

Total:

$$
7! \cdot 2!
$$

**Final result:**

$$
7! \cdot 2! = 5040 \cdot 2 = 10080
$$

---

## 3. Two particular people must NOT sit next to each other

**Problem:**  
In how many ways can 8 people sit in a row if two particular people must not sit next to each other?

**Model:** Complement counting

**Formula:**

$$
8! - 7! \cdot 2!
$$

**Explanation of the formula:**

Step 1: Count all possible arrangements:

$$
8!
$$

Step 2: Count arrangements where they ARE together

$$
7! \cdot 2!
$$

Step 3: Subtract:

$$
8! - 7! \cdot 2!
$$

**Final result:**

$$
40320 - 10080 = 30240
$$

---

## 4. First question is fixed

**Problem:**  
In how many ways can 10 questions be ordered if the first question is fixed?

**Model:** Permutation with restriction

**Formula:**

$$
9!
$$

**Explanation of the formula:**

The first position is fixed, so we only arrange the remaining 9:

- 2nd position → 9 choices
- 3rd → 8 choices
- ...
- last → 1 choice

So:

$$
9!
$$

**Final result:**

$$
9! = 362880
$$
