# **Three-Point Estimation**

It’s a technique that uses **three estimates** to reduce uncertainty in project planning:

1. **Optimistic (O):** Best-case scenario (everything goes smoothly).
2. **Most Likely (M):** Normal / realistic scenario (based on experience).
3. **Pessimistic (P):** Worst-case scenario (risks & issues occur).

From these three values, we calculate an **expected duration (E)**.

---

# **Types of Three-Point Estimation**

### **1. Triangular Distribution**

Formula:

$$
E = \frac{O + M + P}{3}
$$

👉 Treats all estimates (O, M, P) as equally weighted.

**Example (Software Task):**

* O = 4 days (if requirements are clear)
* M = 6 days (normal case)
* P = 10 days (if issues occur)

$$
E = \frac{4 + 6 + 10}{3} = \frac{20}{3} = 6.67 \text{ days (approx)}
$$

---

### **2. Beta Distribution (PERT Analysis)**

Formula:

$$
E = \frac{O + 4M + P}{6}
$$

👉 More weight to **Most Likely (M)** value, because reality usually follows that case.

**Example (Same Task):**

* O = 4
* M = 6
* P = 10

$$
E = \frac{4 + 4(6) + 10}{6} = \frac{4 + 24 + 10}{6} = \frac{38}{6} = 6.33 \text{ days (approx)}
$$

---

# **Standard Deviation & Range (PERT)**

In PMP, sometimes they also ask for **uncertainty range**.

$$
SD = \frac{P - O}{6}
$$

$$
Variance = (SD)^2
$$

👉 Gives confidence interval.

**Example:**

* O = 4, M = 6, P = 10
* SD = (10 − 4) / 6 = 1 day
* Variance = 1² = 1

So expected time = **6.33 days ± 1 day**

---

# **Quick Comparison Table**

| Distribution    | Formula        | Weight Given               | When to Use                        |
| --------------- | -------------- | -------------------------- | ---------------------------------- |
| **Triangular**  | (O + M + P)/3  | Equal weight to all        | Rough estimates, low data          |
| **Beta (PERT)** | (O + 4M + P)/6 | More weight to Most Likely | More reliable, detailed estimation |

---

✅ **Sample PMP Question**
A project task has an optimistic estimate of 3 days, most likely 6 days, and pessimistic 15 days. What is the expected duration using **PERT**?

$$
E = \frac{3 + 4(6) + 15}{6} = \frac{42}{6} = 7 \text{ days}
$$

Answer: **7 days**

---