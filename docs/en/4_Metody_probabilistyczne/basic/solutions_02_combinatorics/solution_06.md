# Task 6 — Combinations in Card Problems

A standard deck contains 52 cards:

- 13 hearts
- 39 non-hearts

We always form a **5-card hand**, where:

- order does not matter
- no repetition

---

## 1. Exactly 2 hearts

### Step 1: Understand the structure

A valid hand must contain:

- 2 hearts
- 3 non-hearts

We count these two parts separately.

---

### Step 2: Choose hearts

We choose 2 cards from 13 hearts:

C(13,2) = (13 × 12) / 2 = 78

---

### Step 3: Choose non-hearts

We choose 3 cards from 39 non-hearts:

C(39,3) = (39 × 38 × 37) / 6 = 9139

---

### Step 4: Combine

Each valid hand is formed by:

- one choice of hearts
- one choice of non-hearts

Multiply:

78 × 9139 = 712842

---

### Final answer

712842

---

## 2. At least one heart

### Step 1: Strategy

Counting “at least one heart” directly is messy.

Instead, we use:
at least one = total − no hearts

---

### Step 2: Total number of 5-card hands

Choose any 5 cards from 52:

C(52,5) = (52 × 51 × 50 × 49 × 48) / 120 = 2598960

---

### Step 3: Hands with no hearts

All 5 cards come from the 39 non-hearts:

C(39,5) = (39 × 38 × 37 × 36 × 35) / 120 = 575757

---

### Step 4: Subtract

2598960 − 575757 = 2023203

---

### Final answer

2023203

---

## 3. No face cards (J, Q, K)

### Step 1: Identify allowed cards

Face cards:

- J, Q, K in each suit → 12 cards

Non-face cards:
52 − 12 = 40

---

### Step 2: Choose from allowed cards only

We choose 5 cards from 40:

C(40,5) = (40 × 39 × 38 × 37 × 36) / 120 = 658008

---

### Final answer

658008
