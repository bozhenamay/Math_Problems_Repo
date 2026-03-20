# Task 9 — Digit Restrictions

## 1. How many 5-digit numbers exist?

### Step 1: What is a 5-digit number?

- The first digit cannot be 0
- The remaining digits can be 0–9

### Step 2: Choices per position

- 1st digit → 9 choices (1–9)
- 2nd digit → 10 choices
- 3rd digit → 10 choices
- 4th digit → 10 choices
- 5th digit → 10 choices

### Step 3: Multiply

9 × 10 × 10 × 10 × 10

### Final answer

90000

---

## 2. How many are even?

### Step 1: What makes a number even?

The last digit must be:
0, 2, 4, 6, or 8 → 5 choices

---

### Step 2: Split into positions

- 1st digit → 9 choices (1–9)
- 2nd digit → 10 choices
- 3rd digit → 10 choices
- 4th digit → 10 choices
- 5th digit → 5 choices (must be even)

### Step 3: Multiply

9 × 10 × 10 × 10 × 5

### Final answer

45000

---

## 3. How many contain no repeated digits?

### Step 1: Build the number step by step

- 1st digit → 9 choices (1–9)

Now digits cannot repeat:

- 2nd digit → 9 choices (0–9 except the first digit)
- 3rd digit → 8 choices
- 4th digit → 7 choices
- 5th digit → 6 choices

---

### Step 2: Multiply

9 × 9 × 8 × 7 × 6

### Calculation

= 27216

### Final answer

27216

---

## 4. How many contain at least one repeated digit?

### Step 1: Strategy

at least one repeated = total − no repetition

---

### Step 2: Use previous results

- Total numbers: 90000
- No repetition: 27216

---

### Step 3: Subtract

90000 − 27216 = 62784

### Final answer

62784
