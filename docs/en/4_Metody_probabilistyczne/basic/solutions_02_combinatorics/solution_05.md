# Task 5 — Combinations

---

## 1. A committee of 4 people is chosen from 12 students

### Step 1: What are we counting?

We select 4 students out of 12:

- order does not matter
- no repetition

### Step 2: Why combinations?

If we count ordered selections:
12 × 11 × 10 × 9

each group is counted multiple times (different orders of the same people).

Each group appears:
4! = 24 times

### Step 3: Correct formula

C(12,4) = (12 × 11 × 10 × 9) / 4!

### Step 4: Calculation

C(12,4) = 11880 / 24 = 495

---

## 2. Committees containing a particular student

### Step 1: Fix one student

We include one specific student, so we choose 3 more from the remaining 11.

### Step 2: Ordered count

11 × 10 × 9

Each group appears:
3! = 6 times

### Step 3: Correct formula

C(11,3) = (11 × 10 × 9) / 3!

### Step 4: Calculation

C(11,3) = 990 / 6 = 165

---

## 3. Committees containing at least one of two particular students

Let the students be A and B.

### Step 1: Strategy

at least one = total − none

---

### Step 2: Total committees

C(12,4) = 495

---

### Step 3: Committees with neither A nor B

We choose 4 from the remaining 10:

C(10,4) = (10 × 9 × 8 × 7) / 4!  
= 5040 / 24  
= 210

---

### Step 4: Final calculation

495 − 210 = 285

---

## 4. Committees with exactly two women (7 men, 5 women)

### Step 1: Structure

We choose:

- 2 women from 5
- 2 men from 7

### Step 2: Women

C(5,2) = (5 × 4) / 2 = 10

### Step 3: Men

C(7,2) = (7 × 6) / 2 = 21

### Step 4: Combine

10 × 21 = 210
