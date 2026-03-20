# Task 7 — k-Permutations (Ordered Selections Without Repetition)

## 1. Assigning first three places among 12 runners

### Step 1: Structure

We assign:

- 1st place
- 2nd place
- 3rd place

Order matters and no repetition is allowed.

### Step 2: Counting

- 1st place → 12 choices
- 2nd place → 11 choices
- 3rd place → 10 choices

### Step 3: Calculation

12 × 11 × 10 = 1320

---

## 2. 4-digit numbers with distinct digits from 1–9

### Step 1: Structure

Digits available: 1–9 (9 digits total)  
We form a 4-digit number with no repetition.

Order matters.

### Step 2: Counting

- 1st digit → 9 choices
- 2nd digit → 8 choices
- 3rd digit → 7 choices
- 4th digit → 6 choices

### Step 3: Calculation

9 × 8 × 7 × 6 = 3024

---

## 3. 4-digit numbers (distinct digits) divisible by 5

### Step 1: Key property

A number is divisible by 5 if the last digit is:

- 0 or 5

BUT digits are from 1–9 → only 5 is possible.

---

### Step 2: Fix last digit

Last digit = 5

Now we choose the first 3 digits from remaining digits:
{1,2,3,4,6,7,8,9} → 8 digits

---

### Step 3: Counting

- 1st digit → 8 choices
- 2nd digit → 7 choices
- 3rd digit → 6 choices

### Step 4: Calculation

8 × 7 × 6 = 336
