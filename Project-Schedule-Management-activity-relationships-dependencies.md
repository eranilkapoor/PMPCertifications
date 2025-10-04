In **Project Schedule Management**, **activity relationships (dependencies)** describe how activities are linked in the schedule. These are defined in **Precedence Diagramming Method (PDM)**.

There are **four types of logical relationships**:

---

### 1️⃣ **Finish-to-Start (FS)** – *Most common*

* **Definition:** The successor cannot **start** until the predecessor **finishes**.
* **Example:** You cannot **start painting** (successor) until **wall construction is finished** (predecessor).

📌 Formula: *Finish A → Start B*

---

### 2️⃣ **Finish-to-Finish (FF)**

* **Definition:** The successor cannot **finish** until the predecessor **finishes**.
* **Example:** **Testing** (successor) cannot **finish** until **coding** (predecessor) finishes.
* Both activities may run in parallel but must finish in order.

📌 Formula: *Finish A → Finish B*

---

### 3️⃣ **Start-to-Start (SS)**

* **Definition:** The successor cannot **start** until the predecessor **starts**.
* **Example:** In construction, **pumping concrete** (predecessor) and **leveling concrete** (successor) must start together or with overlap.

📌 Formula: *Start A → Start B*

---

### 4️⃣ **Start-to-Finish (SF)** – *Least common*

* **Definition:** The successor cannot **finish** until the predecessor **starts**.
* **Example:** A **night security shift (successor)** cannot **finish** until the **day shift (predecessor)** starts.
* Rarely used in real projects.

📌 Formula: *Start A → Finish B*

---

### 🔑 Quick Memory Tip

* **FS** – Most common → “Task A must finish before Task B can start.”
* **FF** – Finish depends on Finish.
* **SS** – Start depends on Start.
* **SF** – Rare! Finish depends on Start.


Great question 👍 — this is one of the areas that **frequently shows up in PMP exams**. Let’s break it down clearly.

---

# **Precedence Diagramming Method (PDM) Relationships**

PDM (also called Activity-on-Node or AON) is a scheduling technique where activities are represented as nodes and relationships (dependencies) are represented as arrows.

There are **4 types of logical relationships** you must know:

---

## **1. Finish-to-Start (FS)** – *Most Common*

👉 Successor activity cannot **start** until the predecessor activity **finishes**.

**Example (Construction Project):**

* Activity A: Pour concrete foundation
* Activity B: Build walls
* You cannot start building the walls until the concrete foundation is complete.

📌 **Exam Tip:** This is the default and most frequently used relationship in scheduling.

---

## **2. Finish-to-Finish (FF)**

👉 Successor activity cannot **finish** until the predecessor activity **finishes**.

**Example (Software Testing):**

* Activity A: Execute test cases
* Activity B: Log defects
* Defect logging (B) can start earlier, but it **cannot finish until all test cases are finished**.

📌 **Exam Tip:** Look for scenarios where tasks run in parallel but must complete together.

---

## **3. Start-to-Start (SS)**

👉 Successor activity cannot **start** until the predecessor activity **starts**.

**Example (Documentation Project):**

* Activity A: Start writing content
* Activity B: Start editing content
* Editing can start once writing starts (maybe with initial sections), but both continue in parallel.

📌 **Exam Tip:** Used when activities overlap to save time.

---

## **4. Start-to-Finish (SF)** – *Least Common*

👉 Successor activity cannot **finish** until the predecessor activity **starts**.

**Example (Shift Work in a Call Center):**

* Activity A: Start new staff shift at 9 AM
* Activity B: Old staff shift ends
* The old shift **cannot finish** until the new shift has started.

📌 **Exam Tip:** Very rare in practice, but you need to remember it for the exam.

---

# **Quick Mnemonics**

* **FS:** “Finish this, then Start next.”
* **FF:** “Finish together.”
* **SS:** “Start together.”
* **SF:** “Can’t Finish until new one Starts.”

---

✅ **In PMP exams:**
They often give you a real-world scenario and ask you **which PDM relationship applies**. Example:

**Question Example:**
*In a road project, paving can only begin once the grading has started, but both may continue simultaneously. What type of dependency is this?*

* A. Finish-to-Start
* B. Finish-to-Finish
* C. Start-to-Start ✅
* D. Start-to-Finish

---