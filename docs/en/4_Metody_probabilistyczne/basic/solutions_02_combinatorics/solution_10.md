# Task 10 — Urn Models

Urn contains:

- 5 red (R)
- 4 blue (B)
- 3 green (G)

Total: 12 balls

---

## 1. Three balls drawn without replacement, order ignored

### Step 1: What is an outcome?

We draw 3 balls, and:

- order does NOT matter
- the actual balls matter (they are distinct objects)

So an outcome is a **set of 3 specific balls**.

---

### Step 2: Why combinations?

If we tried to count step-by-step:

- 1st draw → 12 choices
- 2nd draw → 11 choices
- 3rd draw → 10 choices

This gives:
12 × 11 × 10

BUT this counts different orders of the same 3 balls as different:

- A, B, C
- B, A, C
- C, B, A

These are the same set.

Each group is counted 3! times.

---

### Step 3: Correct count

We divide by 3!:

C(12,3) = (12 × 11 × 10) / 6

= 220

---

## 2. Samples with exactly two red balls

### Step 1: What do we want?

A sample of 3 balls with:

- exactly 2 red
- 1 ball that is NOT red

---

### Step 2: Split into parts

We choose:

- 2 balls from the 5 red ones
- 1 ball from the 7 non-red ones (4 blue + 3 green)

---

### Step 3: Why multiply?

These choices are independent:

- choosing red balls does not affect which non-red ball we choose

So we multiply.

---

### Step 4: Calculation

Red:
C(5,2) = 10

Non-red:
C(7,1) = 7

Total:
10 × 7 = 70

---

## 3. Three balls drawn, order of colors is recorded

### Step 1: What changed?

Now we record only **colors**, not specific balls.

Example outcomes:

- R, B, G
- R, R, B
- G, G, R

We are counting **color sequences**.

---

### Step 2: Important idea

Even though we draw without replacement, we still have:

- multiple balls of each color

So drawing the same color multiple times is possible.

---

### Step 3: Build the sequence

Each position can be:

- R, B, or G

So:

- 1st position → 3 choices
- 2nd position → 3 choices
- 3rd position → 3 choices

---

### Step 4: Calculation

3 × 3 × 3 = 27

---

## 4. Outcomes with exactly two red balls (order recorded)

### Step 1: What do we want?

Sequences of length 3 with:

- exactly 2 R
- 1 non-red (B or G)

---

### Step 2: Choose positions for R

We place R in 2 of the 3 positions.

Possible placements:

- R R X
- R X R
- X R R

So there are 3 ways.

---

### Step 3: Choose the non-red color

The remaining position (X) can be:

- B or G

So 2 choices.

---

### Step 4: Combine

3 × 2 = 6
