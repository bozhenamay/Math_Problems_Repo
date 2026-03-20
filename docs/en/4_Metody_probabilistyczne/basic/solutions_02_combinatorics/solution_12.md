# Task 12 — Mixed Counting Problem

## 1. Student ID Codes

Letters: {A, B, C, D, E} → 5 letters  
Digits: 0–9 → 10 digits

Format: 2 letters + 3 digits

---

### 1.1 Letters and digits may repeat

### Step 1: Letters

- 1st letter → 5 choices
- 2nd letter → 5 choices

### Step 2: Digits

- each of the 3 digits → 10 choices

### Step 3: Multiply

5 × 5 × 10 × 10 × 10 = 5² × 10³

### Final answer

25000

---

### 1.2 Letters cannot repeat, digits may repeat

### Step 1: Letters (no repetition)

- 1st letter → 5 choices
- 2nd letter → 4 choices

### Step 2: Digits

- each digit → 10 choices

### Step 3: Multiply

5 × 4 × 10 × 10 × 10 = 20000

---

### 1.3 No repetition at all

### Step 1: Letters

- 5 × 4

### Step 2: Digits (no repetition)

- 1st digit → 10 choices
- 2nd digit → 9 choices
- 3rd digit → 8 choices

### Step 3: Multiply

5 × 4 × 10 × 9 × 8 = 14400

---

## 2. Medal Assignment (12 runners)

---

### 2.1 Number of ways to assign medals

### Step 1: Structure

Gold, Silver, Bronze → order matters

### Step 2: Counting

- Gold → 12 choices
- Silver → 11 choices
- Bronze → 10 choices

### Step 3: Multiply

12 × 11 × 10 = 1320

---

### 2.2 Two particular runners must both receive medals

Let them be A and B.

---

### Step 1: Choose positions for A and B

There are 3 medal positions.

Choose 2 of them:
C(3,2) = 3 ways

---

### Step 2: Assign A and B to those positions

They can switch places:
2! = 2 ways

---

### Step 3: Assign remaining medal

Choose 1 runner from remaining 10:
10 choices

---

### Step 4: Multiply

3 × 2 × 10 = 60

---

## 3. Committee Selection (10 students: 6 men, 4 women)

---

### 3.1 Total committees

Choose 4 from 10:
C(10,4) = (10 × 9 × 8 × 7) / 24 = 210

---

### 3.2 Exactly two women

### Step 1: Choose women

C(4,2) = 6

### Step 2: Choose men

C(6,2) = 15

### Step 3: Multiply

6 × 15 = 90

---

### 3.3 At least one woman

### Step 1: Strategy

at least one = total − no women

---

### Step 2: Committees with no women

All men:
C(6,4) = (6 × 5 × 4 × 3) / 24 = 15

---

### Step 3: Subtract

210 − 15 = 195

---

## 4. Circular Seating (7 people)

---

### 4.1 Total arrangements

### Step 1: Circular idea

Fix one person → arrange remaining 6

### Step 2: Calculation

6! = 720

---

### 4.2 Two particular people sit next to each other

Let them be A and B.

---

### Step 1: Treat as one block

(A,B) acts as one unit

Now we have:

- (A,B) + 5 others = 6 objects

---

### Step 2: Circular arrangement

Fix one → arrange 5:
5! = 120

---

### Step 3: Internal order of A and B

A B or B A → 2 ways

---

### Step 4: Multiply

120 × 2 = 240

---

## 5. Passwords (digits 0–9 and letters A–Z)

Total symbols:
10 + 26 = 36

---

### 5.1 Repetition allowed

### Step 1: Structure

5 positions, each independent

### Step 2: Counting

36 × 36 × 36 × 36 × 36 = 36⁵

### Final answer

60466176

---

### 5.2 No repetition

### Step 1: Decreasing choices

- 1st → 36
- 2nd → 35
- 3rd → 34
- 4th → 33
- 5th → 32

### Step 2: Multiply

36 × 35 × 34 × 33 × 32 = 45239040

---

### 5.3 Models used

- With repetition → sequence with repetition
- Without repetition → k-permutation
