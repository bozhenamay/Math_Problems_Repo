# Task 11 — Modeling Outcomes

---

## 1. Distinguishable vs Indistinguishable Objects

We have:

- 4 red balls
- 4 blue balls
- 3 green balls  
  Total: 11 balls

---

### 1.1 Indistinguishable balls (by color only)

### Step 1: What matters?

Balls of the same color are treated as identical.

So we only care about the **color pattern**, not individual balls.

Example:
R R B G B ... (only colors matter)

---

### Step 2: Why divide?

If all balls were different, we would have:
11! arrangements

But:

- 4 red balls are identical → divide by 4!
- 4 blue balls are identical → divide by 4!
- 3 green balls are identical → divide by 3!

---

### Step 3: Result

11! / (4! × 4! × 3!)

---

### 1.2 Distinguishable balls (all labeled)

Now each ball is different:
R₁, R₂, R₃, R₄, B₁, ..., G₃

---

### Step 1: What matters?

Every ball is unique → all arrangements are different.

---

### Step 2: Result

11!

---

### 1.3 Why the answers differ

In the indistinguishable case:

- swapping two red balls does NOT create a new arrangement

In the distinguishable case:

- swapping R₁ and R₂ DOES create a new arrangement

So:

- indistinguishable → fewer outcomes
- distinguishable → more outcomes

---

## 2. Recording order vs ignoring order

We draw 3 balls without replacement.

---

### 2.1 Order ignored (only colors recorded as a set)

### Step 1: What matters?

We only care which colors appear, not their order.

Example:
{R, B, G} is the same as {G, R, B}

---

### Step 2: Model

We are choosing 3 balls from 11 without order.

### Result

C(11,3)

---

### 2.2 Order recorded (sequence of colors)

### Step 1: What matters?

Now order matters:

R, B, G ≠ B, R, G

---

### Step 2: Model

We build sequences:

- 1st draw → 11 choices
- 2nd draw → 10 choices
- 3rd draw → 9 choices

### Result

11 × 10 × 9

---

### 2.3 Why order changes everything

When order is ignored:

- multiple sequences represent the same outcome

When order is recorded:

- each sequence is a different outcome

So recording order increases the number of outcomes.

---

## 3. PIN code vs 4-digit number

---

### 3.1 Number of PIN codes (repetition allowed)

### Step 1: Structure

- 4 positions
- digits 0–9
- repetition allowed

### Step 2: Counting

10 × 10 × 10 × 10 = 10⁴

### Result

10000

---

### 3.2 Number of 4-digit numbers

### Step 1: Key restriction

First digit cannot be 0.

---

### Step 2: Counting

- 1st digit → 9 choices (1–9)
- next digits → 10 choices each

### Calculation

9 × 10 × 10 × 10 = 9000

---

### 3.3 Why PIN and numbers differ

PIN:

- leading zero allowed (e.g. 0123 is valid)

Number:

- leading zero NOT allowed

So the counting rules differ.

---

### 3.4 Why 1234 and 4321 are different

A PIN is a **sequence**:

- position matters

So:
1234 ≠ 4321

They are different because the order of digits is different.
