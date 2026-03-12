# Task 5 — Buffon's Needle Experiment

## Description of the experiment

In Buffon's needle experiment, a needle of length **L** is thrown randomly onto a plane that contains equally spaced parallel lines.

The distance between two neighboring lines is **d**.

The experiment studies whether the needle **intersects one of the lines**.

---

# 1. Sample space of the experiment

The sample space $\Omega$ contains **all possible positions and orientations of the needle** when it lands on the plane.

Unlike the previous experiments (coin tosses, die rolls, card draws), the outcomes are **not discrete**.

Instead, the outcome depends on **continuous geometric variables** describing the needle's position and orientation.

Therefore, the sample space consists of all possible pairs:

$$
\Omega = \{(x,\theta)\}
$$

where:

- $x$ describes the position of the needle relative to the nearest line
- $\theta$ describes the angle between the needle and the lines

---

# 2. Parameters determining the outcome

The outcome of a single throw is determined by two parameters:

| Parameter | Meaning                                               |
| --------- | ----------------------------------------------------- |
| $x$       | distance of the needle's center from the nearest line |
| $\theta$  | angle between the needle and the parallel lines       |

These two values completely determine whether the needle intersects a line.

---

# 3. Representation of an elementary outcome

An **elementary outcome** of the experiment can be represented as:

$$
(x,\theta)
$$

where:

- $x$ represents the **distance of the needle's center to the nearest line**
- $\theta$ represents the **orientation angle of the needle**

Example outcomes:

- $(0.2, 0.5)$
- $(0.3, 1.1)$
- $(0.1, 0.9)$

Each pair corresponds to a **specific position and orientation of the needle**.

---

# 4. Mathematical description of the sample space

Using symmetry of the experiment, we can restrict the variables to:

$$
x \in \left[0,\frac{d}{2}\right]
$$

$$
\theta \in \left[0,\frac{\pi}{2}\right]
$$

Thus, the sample space can be written as:

$$
\Omega =
\left\{(x,\theta) \mid
x \in [0,\frac{d}{2}],
\theta \in [0,\frac{\pi}{2}]
\right\}
$$

This set contains **all possible combinations of position and orientation of the needle**.

---

# 5. Why the sample space is continuous

In the previous experiments:

- coin tosses
- die rolls
- card draws

the number of outcomes was **finite**.

For example:

| Experiment | Sample space size |
| ---------- | ----------------- |
| Coin toss  | 2                 |
| Die roll   | 6                 |
| Card draw  | 52                |

In Buffon's needle experiment:

- $x$ can take **infinitely many values**
- $\theta$ can take **infinitely many values**

Therefore, the sample space contains **infinitely many possible outcomes**.

Such a sample space is called a **continuous sample space**.

An elementary outcome corresponds to a **specific geometric configuration of the needle** defined by the pair $(x,\theta)$.
