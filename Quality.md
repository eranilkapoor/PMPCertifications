# 🎯 **Project Quality Management – Overview**

**Purpose:**
To ensure that the project and its deliverables meet the quality standards and satisfy the needs for which the project was undertaken.

**Key Objective:**
Prevent defects *before* they occur, rather than inspect and fix them later.

---

## 🧩 **Quality Management Processes**

There are **3 main processes** under this Knowledge Area:

| Process                     | Process Group            | Purpose                                                                                    |
| --------------------------- | ------------------------ | ------------------------------------------------------------------------------------------ |
| 1️⃣ Plan Quality Management | Planning                 | Identify quality requirements and plan how to meet them.                                   |
| 2️⃣ Manage Quality          | Executing                | Ensure processes are being followed; focuses on process improvement and quality assurance. |
| 3️⃣ Control Quality         | Monitoring & Controlling | Verify that deliverables meet quality standards; focuses on inspection and testing.        |

---

### 1️⃣ **Plan Quality Management**

**Goal:**
Define quality standards, metrics, and how to achieve them.

**Key Inputs:**

* Project Charter
* Scope Baseline
* Requirements Documentation
* Risk Register
* Stakeholder Register
* EEFs & OPAs

**Key Tools & Techniques:**

* Cost-benefit analysis (weighing quality vs. cost)
* Cost of Quality (CoQ)
* Benchmarking (compare with similar projects)
* Design of Experiments (DOE)
* Flowcharts, Cause-and-effect diagrams (Ishikawa/Fishbone)
* Meetings

**Outputs:**

* Quality Management Plan
* Quality Metrics (e.g., defect rate, cycle time)
* Updates to project documents

---

### 2️⃣ **Manage Quality (Quality Assurance)**

**Goal:**
Convert the quality management plan into executable quality activities; ensure processes are followed correctly.

**Key Focus:**
*Process improvement, not product inspection.*

**Key Inputs:**

* Quality Management Plan
* Quality Metrics
* Risk Report
* Lessons Learned Register

**Tools & Techniques:**

* Quality Audits (independent evaluation of process compliance)
* Process Analysis (identify inefficiencies)
* Root Cause Analysis (find source of defects)
* Design for X (DfX – optimize design parameters like reliability, manufacturability)
* Problem-solving techniques

**Outputs:**

* Quality Reports
* Test and evaluation documents
* Change requests (for process improvements)
* Updates to project documents

---

### 3️⃣ **Control Quality**

**Goal:**
Monitor and record results of quality activities to assess performance and recommend necessary changes.

**Key Focus:**
*Verification of deliverables and defect identification.*

**Inputs:**

* Quality Metrics
* Deliverables
* Work Performance Data

**Tools & Techniques:**

* Inspection and Testing
* Control Charts (e.g., Six Sigma, SPC)
* Checklists
* Statistical Sampling
* Pareto Analysis (80/20 rule)
* Histogram
* Scatter Diagram

**Outputs:**

* Quality Control Measurements
* Verified Deliverables
* Change Requests
* Updates to Quality Management Plan and Project Documents

---

## 💰 **Cost of Quality (CoQ)**

Represents the total cost to ensure quality.

| Category                   | Description                         | Example                    |
| -------------------------- | ----------------------------------- | -------------------------- |
| **Prevention Costs**       | Cost to avoid defects               | Training, Quality planning |
| **Appraisal Costs**        | Cost to inspect/test                | Testing, Inspections       |
| **Internal Failure Costs** | Cost to fix defects before delivery | Rework                     |
| **External Failure Costs** | Cost to fix defects after delivery  | Warranty claims, refunds   |

👉 The earlier the defect is found, the cheaper it is to fix.

---

## 🔁 **Key Quality Concepts**

| Concept                             | Meaning                                                                                                              |
| ----------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| **Continuous Improvement (Kaizen)** | Ongoing improvement in processes.                                                                                    |
| **PDCA Cycle (Plan-Do-Check-Act)**  | Deming cycle for iterative process improvement.                                                                      |
| **Six Sigma**                       | Reduces process variation and defects.                                                                               |
| **Quality vs Grade**                | *Quality*: degree to which requirements are met. *Grade*: category based on characteristics (e.g., luxury vs basic). |
| **Precision vs Accuracy**           | *Precision*: repeatability of measurement. *Accuracy*: closeness to target value.                                    |

---

## 📊 **Deliverables and Documentation**

* Quality Management Plan
* Quality Metrics
* Quality Reports
* Test and Evaluation Documents
* Verified Deliverables
* Change Requests

---

## ✅ **Summary**

| Process                     | Focus                                     | Key Output              |
| --------------------------- | ----------------------------------------- | ----------------------- |
| **Plan Quality Management** | Define quality standards and plan.        | Quality Management Plan |
| **Manage Quality**          | Execute assurance & process improvements. | Quality Reports         |
| **Control Quality**         | Verify deliverables meet standards.       | Verified Deliverables   |

---















# 🎯 **Quality Management Knowledge Area (PMBOK)**

**Objective:**
To ensure that the project’s **deliverables meet the required standards** and that **processes are efficient** — avoiding defects, rework, and customer dissatisfaction.

---

## 🧩 **Quality Management Processes**

1. **Plan Quality Management** – Identify quality requirements and plan how to meet them.
2. **Manage Quality** – Turn the plan into executable quality activities (quality assurance).
3. **Control Quality** – Monitor and verify that deliverables meet the standards.

---

## 🏗 **Definition of Quality**

> Quality = “The degree to which a set of inherent characteristics fulfills requirements.”

**Example:**
For your game app, quality means:

* The app should **load in <3 seconds**,
* Have **no crashes** during gameplay,
* Ensure **fair gameplay logic**, and
* **Secure transactions** with no data leak.

---

## 🚫 **Gold Plating**

Adding **extra features** not requested by the customer.

**Example:**
A developer adds a “chat feature” to the Rummy app though it was not in scope.
➡️ This increases testing time and risk — **avoid gold plating**.

---

## ⚙️ **Prevention Over Inspection**

> It’s better (and cheaper) to **prevent defects** than to **find and fix them** later.

**Example:**
Add **automated code quality checks** in CI/CD instead of fixing bugs after launch.

---

## ♻️ **Continuous Improvement**

Based on **PDCA Cycle (Plan–Do–Check–Act)** or **Kaizen** — small, ongoing improvements in process or product.

**Example:**
Regularly updating gameplay logic using user feedback analytics.

---

## 🕓 **Just-In-Time (JIT)**

Producing only what is needed, when it’s needed — **reduces inventory & waste**.

**Example:**
Only compile game assets (like images/sounds) when ready for deployment, not before.

---

## 👥 **Responsibility for Quality**

* **Project Manager:** Ultimate accountability.
* **Team Members:** Execute according to standards.
* **Quality Team:** Audits, verifies compliance.

---

## 💡 **Interviews, Brainstorming, and Benchmarking**

* **Interviews:** Discuss with players/testers about experience.
* **Brainstorming:** Identify potential improvement areas.
* **Benchmarking:** Compare your app quality with competitors like MPL or WinZO.

---

## ⚖️ **Cost–Benefit Analysis**

Compare **cost of quality activities** vs **benefit gained**.

**Example:**
If automated testing costs ₹1L but reduces production bugs saving ₹3L → it’s beneficial.

---

## 💸 **Impact of Poor Quality**

* Rework and cost overruns
* Brand damage (bad app reviews)
* Lost customers

---

## 💰 **Cost of Quality (CoQ)**

Total cost to achieve desired quality level.

### **1. Cost of Conformance**

✅ *Money spent to ensure quality*

* **Prevention Costs:** Training, QA, process audits.
* **Appraisal Costs:** Inspections, testing, code reviews.

### **2. Cost of Nonconformance**

❌ *Money spent because of failure*

* **Internal Failure:** Bug fixes before release.
* **External Failure:** App crashes after release, user refunds.

**Example:**

| Type             | Example (Game App)                | Cost Impact |
| ---------------- | --------------------------------- | ----------- |
| Prevention       | Code standards, automated testing | Low         |
| Appraisal        | Beta testing, reviews             | Medium      |
| Internal Failure | Fixing before go-live             | High        |
| External Failure | Negative reviews, refund          | Very High   |

---

## ⚖️ **Marginal Analysis**

Balance the **cost of improving quality** vs **benefit from improvement** until both are equal.

**Example:**
Spending more on testing stops being useful when bug reduction becomes minimal.

---

## 🧩 **Logical Data Models**

Used to ensure **data accuracy and integrity** in system design (ER diagrams, data flow).

---

## 🔁 **Flowcharts**

Graphical representation of a process — helps identify **bottlenecks or defects**.

**Example:**
Flowchart for user registration to verify email → wallet creation → start game.

---

## ✅ **Test and Inspection Planning**

Define **what will be tested**, **how**, **when**, and **acceptance criteria**.

---

## 🧾 **Checklists**

A structured list of things to verify before moving to the next phase.

**Example:**
Pre-launch checklist: Server tested, UI responsive, No broken links.

---

## 📊 **Quality Metrics**

Define **specific measurable parameters** for quality.

**Examples:**

* App crash rate < 1%
* Response time < 2 sec
* Defect density ≤ 0.5 per 1000 LOC

---

## 📘 **Quality Management Plan**

Describes:

* Quality objectives
* Standards to follow
* Roles & responsibilities
* Tools and techniques
* Metrics and control thresholds

---

## ⚙️ **Quality Tools**

### **Cause and Effect Diagram (Ishikawa/Fishbone)**

Identifies root causes of defects.
**Example:**
Low game performance → cause: memory leak → subcause: unoptimized assets.

---

### **Histograms**

Bar chart showing **frequency of defects** or test results.

---

### **Pareto Chart (80/20 Rule)**

80% of problems come from 20% of causes.
**Example:**
If 80% of bugs are due to 2 modules (payment & gameplay), focus testing there.

---

### **Scatter Diagrams**

Show **relationship between two variables**.
**Example:**
More server load → higher latency.

---

### **Alternatives Analysis**

Compare multiple process options for best quality improvement path.

---

### **Document Analysis**

Review of project documents to ensure compliance and completeness.

---

### **Design of Experiments (DOE)**

Statistical technique to determine **which variables affect quality output**.

**Example:**
Test combination of screen sizes, devices, and network speeds to optimize gameplay.

---

### **Process Analysis**

Examines **process efficiency** using data from flowcharts or process maps.

---

### **Root Cause Analysis**

Identify the **real cause** behind defects, not symptoms.

---

### **Failure Analysis**

Analyze why a product failed to prevent recurrence.

---

### **Multicriteria Decision Analysis**

Evaluate multiple quality options using weighted scoring.

---

### **Affinity Diagrams**

Group related ideas from brainstorming to find major themes.

---

### **Audits**

Independent check to verify process compliance.

---

### **Design for X (DfX)**

Design optimized for certain objectives (e.g., **Design for Performance**, **Design for Testability**).

---

### **Problem Solving Steps**

1. Define the problem
2. Identify root cause
3. Generate alternatives
4. Select best solution
5. Implement and verify

---

### **Test and Evaluation Documents**

Define **test cases, acceptance tests, and quality reviews**.

---

### **Quality Reports**

Summarize **results of quality activities**, include trends and issues.

---

## 📈 **Statistical Concepts**

| Term                         | Meaning                                | Example                                     |
| ---------------------------- | -------------------------------------- | ------------------------------------------- |
| **Mutual Exclusivity**       | Two events cannot happen together.     | “Game crashes” and “Game runs smoothly”     |
| **Probability**              | Likelihood of event                    | 0.1 = 10% crash chance                      |
| **Normal Distribution**      | Symmetrical bell curve for data spread | User response time distribution             |
| **Statistical Independence** | One event doesn’t affect another       | Login success doesn’t affect sound playback |
| **Standard Deviation (σ)**   | Measure of variation                   | Small σ = consistent app performance        |
| **3σ / 6σ**                  | Quality levels                         | 6σ → 3.4 defects per million ops            |

---

## 📋 **Checksheets**

Used to collect data on frequency of defects — input to Pareto analysis.

---

## 🔢 **Statistical Sampling**

Inspecting a **subset** of deliverables instead of all.

**Example:**
Test 100 random game sessions instead of 10,000.

---

## 📣 **Questionnaires and Surveys**

Collect user satisfaction or beta feedback on app quality.

---

## 📊 **Performance Reviews**

Formal assessment of process efficiency and team output.

---

## 🔍 **Inspection**

Checking deliverables for defects (code review, playtest).

---

## 📉 **Control Charts**

Show if process variation is within acceptable limits.

**Key Components:**

* **Mean (Center Line):** Average performance.
* **Control Limits (UCL/LCL):** Statistically calculated boundaries.
* **Specification Limits:** Customer-defined limits.
* **Assignable/Special Cause Variation:** Unusual events that cause deviation (e.g., server outage).
* **Out of Control:** When a point crosses control limits.
* **Rule of Seven:** 7 points consecutively on one side of mean → process trend → investigate cause.

**Example:**
If average response time = 2s (mean),
Control limits = 1.5s–2.5s.
If 7 samples show 2.6s → process is **out of control**.

---

## ✅ **Summary Table**

| Concept                     | Description                                                      |
| --------------------------- | ---------------------------------------------------------------- |
| **Plan Quality Management** | Identify and plan quality standards                              |
| **Manage Quality**          | Implement QA activities                                          |
| **Control Quality**         | Verify deliverables                                              |
| **Tools**                   | Pareto, Cause-effect, Control charts, Checklists                 |
| **Focus**                   | Customer satisfaction, defect prevention, continuous improvement |
| **Output**                  | Quality reports, change requests, verified deliverables          |

---