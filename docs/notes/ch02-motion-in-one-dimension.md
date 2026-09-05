# Chapter 2 — Motion in One Dimension

**Course:** PHY-201-001 · **Topics:** distance, displacement, speed, velocity, acceleration, kinematic equations

> **The one big idea of this chapter:** scalars only tell you *how much*, vectors tell you *how much and which way*. Almost every mistake in Chapter 2 comes from mixing the two up.

---

## Table of Contents

1. [Scalars vs. Vectors](#1-scalars-vs-vectors)
2. [Distance vs. Displacement](#2-distance-vs-displacement)
3. [Speed vs. Velocity](#3-speed-vs-velocity)
4. [Constant Velocity](#4-constant-velocity)
5. [Average Speed for a Multi-Leg Trip](#5-average-speed-for-a-multi-leg-trip)
6. [Acceleration](#6-acceleration)
7. [The Kinematic Equations (2-5 Equations)](#7-the-kinematic-equations-2-5-equations)
8. [Reading Motion Graphs](#8-reading-motion-graphs)
9. [Problem-Solving Strategy](#9-problem-solving-strategy)
10. [Worked Examples](#10-worked-examples)
11. [Exam Traps and Reminders](#11-exam-traps-and-reminders)

---

## 1. Scalars vs. Vectors

| | Definition | Examples |
|---|---|---|
| **Scalar** | Has **magnitude only** ("how much?") | time, mass, volume, **distance**, **speed** |
| **Vector** | Has **magnitude *and* direction** | **position**, **displacement**, **velocity**, **acceleration**, force |

**Origin (∅)** — the reference point you compare all other points to. Every position is measured *from* the origin.

- $x_0$ = initial position
- $x$ = final position

A position isn't complete without a direction/sign: "5 m from the origin" is not enough — you need **"+5.00 m"** (i.e. 5 m to the right of the origin).

---

## 2. Distance vs. Displacement

### Distance (scalar)
The **length of the path actually traveled**.

> You need to know *everything about the path* to calculate distance. Every wiggle, every backtrack, gets added.

### Displacement (vector)
The **change in position** — straight line from start to finish, plus direction.

$$\Delta \vec{x} = x - x_0$$

### The relationship

> ⚠️ **Distance is the magnitude of displacement ONLY for a straight-line path** (with no reversal of direction).

If the object backtracks or curves, distance > |displacement|.

**Reference example — I-85 (origin at the GA/SC line, North = +):**

∅ ───────┬──────────────┬─────────────────────┬────────► N
GA/SC 19.0 mi 46.0 mi 90.0 mi
Anderson Barton Campus Gaffney


| | Path 1: Anderson → Gaffney → back to Barton | Path 2: Anderson → Barton (straight) |
|---|---|---|
| Legs | 71.0 mi north, then 44.0 mi south | 27.0 mi north |
| $x_0$ | +19.0 mi | +19.0 mi |
| $x$ | +46.0 mi | +46.0 mi |
| **Distance** | 71.0 + 44.0 = **115.0 mi** | **27.0 mi** |
| **Displacement** | 46.0 − 19.0 = **+27.0 mi** | **+27.0 mi** |

Same start, same finish → **same displacement**. Totally different **distance**.

---

## 3. Speed vs. Velocity

### Average Speed (scalar)

$$\boxed{\text{average speed} = \frac{\text{distance}}{\text{time}}}$$

### Average Velocity (vector)

$$\boxed{\vec{v} = \frac{\text{displacement}}{\text{time}} = \frac{\Delta \vec{x}}{\Delta t}}$$

> ⚠️ **Average speed is the magnitude of average velocity ONLY for the straight-line path.** Same rule as distance/displacement — it's inherited directly from it.

**Comparison using the two I-85 paths:**

| | Path 1 (out and back, 1.77 hr) | Path 2 (straight, 0.540 hr) |
|---|---|---|
| Avg. speed | $\dfrac{115.0\ \text{mi}}{1.77\ \text{hr}} = 65.0\ \text{mph}$ | $\dfrac{27.0\ \text{mi}}{0.540\ \text{hr}} = 50.0\ \text{mph}$ |
| Avg. velocity | $\dfrac{+27.0\ \text{mi}}{1.77\ \text{hr}} = +15.3\ \text{mph}$ | $\dfrac{+27.0\ \text{mi}}{0.540\ \text{hr}} = +50.0\ \text{mph}$ |
| Equal? | **No** (path curved back) | **Yes** (straight line) |

---

## 4. Constant Velocity

When velocity is constant:

$$\text{instantaneous velocity} = \text{average velocity}$$

Starting from $v = \dfrac{\Delta x}{\Delta t}$ with $\Delta t = t - t_0$ and $t_0 = 0$:

$$v = \frac{x - x_0}{t} \quad\Longrightarrow\quad vt = x - x_0 \quad\Longrightarrow\quad \boxed{x = x_0 + vt}$$

That last form is the workhorse — it's just the $a = 0$ special case of the big position equation in §7.

---

## 5. Average Speed for a Multi-Leg Trip
And ────────────────┬──────────────────────────── Gaf
27.0 mi Bar 44.0 mi
0.540 hr 1.100 hr
50.0 mi/hr 40.0 mi/hr


$$\text{avg speed} = \frac{\text{total distance}}{\text{total time}} = \frac{27.0 + 44.0}{0.540 + 1.100} = \frac{71.0\ \text{mi}}{1.640\ \text{hr}} = 43.3\ \text{mi/hr}$$

> ⚠️ **Do NOT average the two speeds.** $(50.0 + 40.0)/2 = 45.0$ — wrong. You must add the distances and add the times, then divide once.

---

## 6. Acceleration

**Acceleration — the change of velocity per unit of time.** (vector)

$$\boxed{\bar{a} = \frac{\vec{v} - \vec{v}_0}{\Delta t}}$$

$$\text{instantaneous acceleration} = \text{average acceleration} \quad \text{(if the acceleration is constant)}$$

Rearranged into the form you'll actually use:

$$a = \frac{v - v_0}{t} \quad\Longrightarrow\quad \boxed{v = v_0 + at}$$

**Reference example — car "0 to 60" performance run:**

Given $v_0 = +5.00$ m/s at $t = 0$, and $v = +31.80$ m/s at $t = 6.00$ s (≈ 60.0 mph):

$$a = \frac{31.80\ \text{m/s} - 5.00\ \text{m/s}}{6.00\ \text{s}} = \frac{26.80\ \text{m/s}}{6.00\ \text{s}} = +4.47\ \text{m/s}^2$$

### Signs: is it speeding up or slowing down?

Compare the **direction of $\vec{a}$** to the **direction of $\vec{v}$** — *not* the sign of $a$ by itself.

| $\vec{v}$ | $\vec{a}$ | Result |
|---|---|---|
| → | → | **speeds up** |
| → | ← | **slows down** |
| ← | → | **slows down** |
| ← | ← | **speeds up** |

**Same direction = speeding up. Opposite directions = slowing down.** A negative acceleration does *not* automatically mean "slowing down."

---

## 7. The Kinematic Equations (2-5 Equations)

**These only work when acceleration is constant.**

| # | Equation | Use it when... |
|---|---|---|
| 1 | $\bar{v} = \dfrac{v_0 + v}{2}$ | you need the average velocity from endpoints |
| 2 | $v = v_0 + a t$ | $v$ if $a$ is constant |
| 3 | $x = x_0 + v_0 t + \tfrac{1}{2} a t^2$ | **final position** if $a$ is constant |
| 4 | $v^2 = v_0^2 + 2a(x - x_0)$ | **you don't know $t$** |
| 5 | $x = x_0 + \tfrac{1}{2}(v + v_0) t$ | **you don't know $a$** |
| — | $t = \dfrac{v - v_0}{a}$ | solving equation 2 for time |

**Equation 3 is the "final position equation"** — highlighted in class. It's also written as:

$$x - x_0 = v_0 t + \tfrac{1}{2} a t^2$$

The five variables are $x$, $x_0$, $v_0$, $v$, $a$, $t$. **Each equation is missing exactly one of them** — that's how you pick which one to use. Find the variable you *don't have and don't want*, and grab the equation that leaves it out.

---

## 8. Reading Motion Graphs

**Velocity vs. time graph ($v$ vs $t$):**

- **Slope = acceleration** ($a$)
- **Area under the curve = displacement**
  - rectangle piece: $v_0 t$
  - triangle piece: $\tfrac{1}{2} a t \cdot t = \tfrac{1}{2} a t^2$
  - Add them: $\Delta x = v_0 t + \tfrac{1}{2} a t^2$ — **this is where equation 3 comes from.**
- $y$-intercept = $v_0$
- A **straight line** = constant acceleration. A **curve** = changing acceleration (the kinematic equations don't apply).

The triangle-plus-rectangle picture is worth memorizing — it lets you rebuild equation 3 from scratch if you blank on it.

---

## 9. Problem-Solving Strategy

The three steps from class:

1. **Identify what you WANT** (the unknown you're solving for)
2. **Identify what is GIVEN** (list every value with its sign)
3. **See what equation can give you what you want** from what you have

Practical additions:
- Draw the picture and mark the **positive direction** before anything else.
- Write down $x_0, x, v_0, v, a, t$ as a checklist and fill in what you know.
- Carry the units through the algebra — they'll catch sign and setup errors.

---
## 10. Worked Examples

Every fully worked example — the I-85 position problem, the full motion table, and the crash test — now lives in **[Worked Problems](../problems/ch02-worked.md)**, written in exam format (asked / given / missing / equation / work / checks). This keeps the concept notes here short and the problem-solving practice in one dedicated place.

---

## 11. Exam Traps and Reminders

- [ ] **"Only for the straight-line path"** — this qualifier showed up twice in lecture (distance/displacement and speed/velocity). It's begging to be a test question.
- [ ] **Never average speeds.** Total distance ÷ total time.
- [ ] **Negative acceleration ≠ slowing down.** Compare $\vec{a}$ to $\vec{v}$.
- [ ] **Kinematic equations require constant $a$.** Check before using them.
- [ ] **Convert minutes to hours** (and km to m) *before* plugging in.
- [ ] **Every vector answer needs a sign or a direction word.** "+27.0 mi" or "27.0 mi north" — not bare "27.0 mi."
- [ ] **Pick the equation by what's missing**, not by what looks familiar.
