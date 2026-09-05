# Equation Sheet — Quick Lookup

One page. No explanations. Full context lives in [`notes/ch02-motion-in-one-dimension.md`](../notes/ch02-motion-in-one-dimension.md).

---

## Definitions

| Quantity | Equation | Type | Source |
|---|---|---|---|
| Displacement | $\Delta \vec{x} = x - x_0$ | vector | Ch. 2 §2 |
| Average speed | $\dfrac{\text{distance}}{\text{time}}$ | scalar | Ch. 2 §3 |
| Average velocity | $\vec{v} = \dfrac{\Delta \vec{x}}{\Delta t}$ | vector | Ch. 2 §3 |
| Average acceleration | $\bar{a} = \dfrac{\vec{v} - \vec{v}_0}{\Delta t}$ | vector | Ch. 2 §6 |
| Constant-velocity position | $x = x_0 + vt$ | — | Ch. 2 §4 |
| Multi-leg average speed | $\dfrac{\text{total distance}}{\text{total time}}$ | scalar | Ch. 2 §5 |

---

## The 5 Kinematic Equations (constant acceleration only)

| # | Equation | Missing variable | Reach for it when... |
|---|---|---|---|
| 1 | $\bar{v} = \dfrac{v_0 + v}{2}$ | $a$, $x$ | you want average velocity from endpoints |
| 2 | $v = v_0 + at$ | $x$ | you don't need position |
| 3 | $x = x_0 + v_0 t + \tfrac{1}{2}at^2$ | $v$ | you don't know / don't need final velocity |
| 4 | $v^2 = v_0^2 + 2a(x - x_0)$ | $t$ | **no time given** |
| 5 | $x = x_0 + \tfrac{1}{2}(v + v_0)t$ | $a$ | **no acceleration given** |

**Rearranged forms you'll want:**

$$t = \frac{v - v_0}{a} \qquad a = \frac{v^2 - v_0^2}{2(x - x_0)} \qquad x - x_0 = v_0 t + \tfrac{1}{2}at^2$$

---

## Decision Table — Which Equation?

| I have... | I want... | Use |
|---|---|---|
| $v_0, a, t$ | $v$ | Eq. 2 |
| $v_0, a, t$ | $x$ | Eq. 3 |
| $v_0, v, \Delta x$ | $a$ | Eq. 4 |
| $v_0, v, t$ | $x$ | Eq. 5 |
| $v_0, v, a$ | $t$ | $t = (v - v_0)/a$ |
| constant $v$, $t$ | $x$ | $x = x_0 + vt$ |

---

## Sign Convention Cheat Card

| $\vec{v}$ | $\vec{a}$ | Motion |
|---|---|---|
| → | → | speeding up |
| → | ← | slowing down |
| ← | ← | speeding up |
| ← | → | slowing down |

**Same direction → speed up. Opposite → slow down.**

---

## Graph Facts

| Graph | Slope | Area under curve |
|---|---|---|
| $x$ vs $t$ | velocity | — |
| $v$ vs $t$ | acceleration | displacement |

$v$ vs $t$ area = rectangle ($v_0 t$) + triangle ($\tfrac{1}{2}at^2$) = **Eq. 3**

---

## Unit Conversions

$$1\ \text{hr} = 60\ \text{min} \qquad \text{min} \to \text{hr}: \ \times \frac{1\ \text{hr}}{60\ \text{min}}$$

$$1\ \text{mi} = 1609\ \text{m} \qquad 1\ \text{m/s} \approx 2.237\ \text{mph} \qquad g = 9.80\ \text{m/s}^2$$
