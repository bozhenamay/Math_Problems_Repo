# Task 8 — Sequences with Repetition

## 1. Number of 5-digit PIN codes (digits may repeat)

### Step 1: What are we forming?

A PIN code has:

- 5 positions
- each position can be any digit from 0 to 9

### Step 2: Choices per position

Each position has 10 possible digits.

So:

- position 1 → 10 choices
- position 2 → 10 choices
- position 3 → 10 choices
- position 4 → 10 choices
- position 5 → 10 choices

### Step 3: Multiply (product rule)

10 × 10 × 10 × 10 × 10 = 10⁵

### Final answer

100000

---

## 2. Codes with at least one repeated digit

### Step 1: What does “at least one repeated” mean?

It means:

- some digit appears twice (or more)

Instead of counting this directly, we use an easier idea:

at least one repeated = total − no repetition

---

### Step 2: Total number of codes

From part 1:
100000

---

### Step 3: Codes with NO repeated digits

Now we build a code where all digits are different.

- position 1 → 10 choices
- position 2 → 9 choices (one digit already used)
- position 3 → 8 choices
- position 4 → 7 choices
- position 5 → 6 choices

### Calculation

10 × 9 × 8 × 7 × 6 = 30240

---

### Step 4: Subtract

100000 − 30240 = 69760

### Final answer

69760

---

## 3. Codes with all digits different

### Step 1: This is exactly what we counted above

We already calculated:
10 × 9 × 8 × 7 × 6

### Final answer

30240
