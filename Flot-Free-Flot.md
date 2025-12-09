# **1. Float (General Term)**

Float = The amount of time an activity can be **delayed** without affecting something else.
👉 Think of it as “schedule flexibility.”

Two main types:

* **Total Float**
* **Free Float**

---

# **2. Total Float (TF)**

👉 The **total time** an activity can be delayed **without delaying the project finish date** (end of the critical path).

**Formula:**

$$
\text{Total Float} = \text{Late Start} - \text{Early Start} = \text{Late Finish} - \text{Early Finish}
$$

**Example:**

* Task A: ES = Day 1, EF = Day 5
* LS = Day 3, LF = Day 7

$$
TF = LS - ES = 3 - 1 = 2 \text{ days}
$$

So, Task A can slip **2 days** without delaying project completion.

---

# **3. Free Float (FF)**

👉 The time an activity can be delayed **without delaying the Early Start of its successor**.

**Formula:**

$$
FF = \text{(ES of successor)} - \text{(EF of current activity)}
$$

**Example:**

* Task A finishes on Day 5 (EF = 5).
* Task B (successor) starts earliest on Day 8 (ES = 8).

$$
FF = 8 - 5 = 3 \text{ days}
$$

So Task A has **3 days free float** (it won’t delay Task B even if delayed by 3 days).

---

# **4. Slack**

👉 In PMP terms, **Slack = Float** (they are interchangeable).

* Some books use “Slack” in **Critical Path Method (CPM)**.
* PMI generally uses “Float” in exam questions.
* So:

  * **Total Slack = Total Float**
  * **Free Slack = Free Float**

---

# **5. Critical Path & Float**

* Activities on the **Critical Path** have **0 Total Float** (no flexibility).
* Any delay in these tasks → directly delays project finish date.

---

# **Quick Example Project**

Suppose you have a project with these activities:

| Activity | Duration | Predecessor | Early Start (ES) | Early Finish (EF) | Late Start (LS) | Late Finish (LF) |
| -------- | -------- | ----------- | ---------------- | ----------------- | --------------- | ---------------- |
| A        | 5        | —           | 0                | 5                 | 0               | 5                |
| B        | 3        | A           | 5                | 8                 | 7               | 10               |
| C        | 4        | A           | 5                | 9                 | 5               | 9                |
| D        | 2        | B, C        | 9                | 11                | 10              | 12               |

### Calculations:

* **Activity A:** TF = LS − ES = 0 − 0 = 0 → Critical Path.
* **Activity B:** TF = LS − ES = 7 − 5 = 2 days.
* **Activity C:** TF = LS − ES = 5 − 5 = 0 → Critical Path.
* **Activity D:** TF = LS − ES = 10 − 9 = 1 day.

👉 Here, Critical Path = **A → C → D** (0 float activities).

---

# **Summary Table**

| Term                 | Meaning                                       | Formula / Concept           | Example         |
| -------------------- | --------------------------------------------- | --------------------------- | --------------- |
| **Float**            | General flexibility                           | Can be Free or Total        | —               |
| **Total Float (TF)** | Delay allowed without delaying project finish | LS − ES OR LF − EF          | Task B = 2 days |
| **Free Float (FF)**  | Delay allowed without delaying successor      | ES(successor) − EF(current) | Task A = 3 days |
| **Slack**            | Another name for Float                        | Same as Float               | —               |

---

✅ **Exam Tip:**
If the question says **“float” without specifying** → they usually mean **Total Float**.