# Task 1 — Recognizing Counting Models

## 1. Arranging 7 students in a line

**Problem:**  
In how many ways can 7 students be arranged in a line?

**Model:** Permutation

**Formula:**

$$
7!
$$

**Explanation of the formula:**  
We fill positions one by one:

- 1st position → 7 choices
- 2nd → 6 choices
- 3rd → 5 choices
- ...
- last → 1 choice

So:

$$
7 \cdot 6 \cdot 5 \cdot 4 \cdot 3 \cdot 2 \cdot 1 = 7!
$$

---

## 2. Choosing 4 members of a committee from 12 people

**Problem:**  
In how many ways can we choose 4 people out of 12?

**Model:** Combination

**Formula:**

$$
\binom{12}{4} = \frac{12!}{4!(12-4)!} = \frac{12!}{4! \cdot 8!}
$$

**Explanation of the formula:**  
If we choose people one by one, we get:

$$
12 \cdot 11 \cdot 10 \cdot 9
$$

But this counts the same group multiple times in different orders.

Example:  
(A,B,C,D) and (B,A,C,D) represent the same committee.

Each group of 4 people can be arranged in:

$$
4!
$$

ways, so we divide by \(4!\) to remove duplicates.

The \(8!\) comes from the remaining people, since:

$$
12 - 4 = 8
$$

---

## 3. Assigning gold, silver, and bronze medals among 15 athletes

**Problem:**  
In how many ways can gold, silver, and bronze medals be assigned among 15 athletes?

**Model:** k-permutation

**Formula:**

$$
P(15,3) = \frac{15!}{(15-3)!}
$$

**Explanation of the formula:**

We assign medals one by one:

- Gold medal → we can choose any of the 15 athletes → 15 choices
- Silver medal → 1 athlete is already used → 14 choices left
- Bronze medal → 2 athletes are used → 13 choices left

So we multiply:

$$
15 \cdot 14 \cdot 13
$$

Now, why does the formula look like:

$$
\frac{15!}{12!}
$$

Because:

$$
15! = 15 \cdot 14 \cdot 13 \cdot 12!
$$

So when we divide by \(12!\), everything after 13 cancels out, leaving:

$$
15 \cdot 14 \cdot 13
$$

---

## 4. Forming a 6-digit PIN code

**Problem:**  
How many 6-digit PIN codes can be formed?

**Model:** Sequence with repetition

**Formula:**

$$
10^6
$$

**Explanation of the formula:**  
Each digit can be from 0 to 9 → 10 choices.

We have 6 positions, so:

$$
10 \cdot 10 \cdot 10 \cdot 10 \cdot 10 \cdot 10 = 10^6
$$

Repetition is allowed, so choices do not decrease.

---

## 5. Arranging the letters of the word BANANA

**Problem:**  
In how many distinct ways can the letters of BANANA be arranged?

**Model:** Permutation with repeated elements

**Formula:**

$$
\frac{6!}{3! \cdot 2!}
$$

**Explanation of the formula:**

First, imagine all letters are different.

Then the number of arrangements would be:

$$
6!
$$

But in BANANA:

- A appears 3 times
- N appears 2 times

Now look what happens:

If we swap two A’s, the word does not change.

Example:

$$
BANANA = BANANA
$$

So we are counting the same arrangement multiple times.

How many times?

- The 3 A’s can be rearranged in \(3!\) ways
- The 2 N’s can be rearranged in \(2!\) ways

So every arrangement is counted:

$$
3! \cdot 2!
$$

times too many.

To fix this, we divide:

$$
\frac{6!}{3! \cdot 2!}
$$

---

## 6. Seating 6 people around a round table

**Problem:**  
In how many ways can 6 people sit around a round table?

**Model:** Circular permutation

**Formula:**

$$
(6 - 1)! = 5!
$$

**Explanation of the formula:**

If the people were in a line, we would have:

$$
6!
$$

But in a circle, rotating everyone does NOT create a new arrangement.

Example:

- A B C D E F
- B C D E F A
- C D E F A B

These are all the same seating, just rotated.

So each arrangement is counted 6 times (once for each rotation).

To fix this, we divide by 6:

$$
\frac{6!}{6} = 5!
$$

Another way to think about it:

We fix one person in place and arrange the remaining 5:

$$
5!
$$
