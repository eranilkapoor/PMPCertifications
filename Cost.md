# 💰 **Project Cost Management (PMBOK® – Knowledge Area #7)**

## 🎯 **Definition**

> **Project Cost Management** includes the processes involved in *planning, estimating, budgeting, financing, funding, managing, and controlling costs* so the project can be completed **within the approved budget.**

It ensures the project is **financially feasible, controlled, and profitable** (or within sponsor expectations).

---

## 📘 **Objective**

* Estimate all costs required to complete the project
* Develop a realistic **budget (Cost Baseline)**
* Monitor and control actual spending
* Identify cost variances early
* Forecast final project costs

---

## 🔹 **Processes in Cost Management (4 Total)**

| # | Process Name         | Process Group            | Key Output                      |
| - | -------------------- | ------------------------ | ------------------------------- |
| 1 | Plan Cost Management | Planning                 | Cost Management Plan            |
| 2 | Estimate Costs       | Planning                 | Cost Estimates                  |
| 3 | Determine Budget     | Planning                 | Cost Baseline                   |
| 4 | Control Costs        | Monitoring & Controlling | Cost Forecasts, Change Requests |

---

# 🧭 **1️⃣ Plan Cost Management**

**Purpose:**
Establish the *policies, procedures, and documentation* for planning, managing, and controlling project costs.

**Key Inputs:**

* Project Charter
* Project Management Plan
* EEFs (Economic conditions, labor rates)
* OPAs (Cost reporting templates, historical data)

**Key Output:**
✅ **Cost Management Plan**, which defines:

* Units of measure (e.g., INR, USD)
* Precision & rounding rules
* Control thresholds (e.g., ±10%)
* Performance measurement rules (EVM method)
* Reporting formats (weekly/monthly)

**Lesson:**
This plan sets **how cost estimation and control** will happen throughout the project.

---

# 🧾 **2️⃣ Estimate Costs**

**Purpose:**
Develop **approximate cost estimates** for each activity, resource, or work package.

**Inputs:**

* Scope Baseline (WBS, WBS Dictionary)
* Project Schedule
* Resource Requirements
* Risk Register

**Techniques:**

| Technique                  | Description                                              | Example                                     |
| -------------------------- | -------------------------------------------------------- | ------------------------------------------- |
| **Analogous Estimating**   | Uses cost of similar past projects (high-level)          | Last CRM cost ₹10L → similar size this year |
| **Parametric Estimating**  | Uses statistical relationship (per unit cost × quantity) | ₹500/sq.ft × 2000 sq.ft = ₹10L              |
| **Bottom-up Estimating**   | Aggregates detailed estimates for all tasks              | Sum of all activity costs                   |
| **Three-Point Estimating** | (O + 4M + P)/6 for weighted average                      | (₹1000 + 4×₹1500 + ₹2000)/6 = ₹1500         |
| **Expert Judgment**        | Based on SME experience                                  | Senior dev: 8 hrs × ₹150/hr                 |
| **Reserve Analysis**       | Adds contingency for risks                               | Add 10% risk reserve                        |

**Outputs:**
✅ Activity Cost Estimates
✅ Basis of Estimates
✅ Cost Estimates at different levels (Activity → Work Package → Project)

**Lesson:**
Estimation helps identify **funding needs** and **resource allocation** accurately.

---

# 💰 **3️⃣ Determine Budget**

**Purpose:**
Aggregate all estimated costs to establish an **authorized cost baseline** and funding requirements.

**Inputs:**

* Cost Estimates
* Schedule (timing of expenditures)
* Risk Register
* Agreements

**Tools:**

* Cost Aggregation (sum of all work packages)
* Reserve Analysis (Contingency & Management reserves)
* Historical Data & Funding Limits
* Financing options

**Outputs:**
✅ **Cost Baseline**
✅ **Project Funding Requirements**

**Cost Baseline =**

> Approved version of the project budget (time-phased), excluding management reserves.

**Funding Requirements =**

> Cost Baseline + Management Reserves

**Lesson:**
Cost Baseline is your **official spending plan** — the benchmark for performance measurement.

---

# 📊 **4️⃣ Control Costs**

**Purpose:**
Monitor project costs and control changes to the cost baseline.

**Activities:**

* Measure cost performance
* Identify deviations
* Forecast future costs
* Apply corrective or preventive actions

**Key Tools:**

* **Earned Value Management (EVM)** 📈
* **Variance Analysis**
* **Trend Analysis**
* **Reserve Analysis**

**Outputs:**
✅ Work Performance Information
✅ Cost Forecasts (EAC, ETC)
✅ Change Requests

---

## 📘 **Earned Value Management (EVM) – The Core of Cost Control**

EVM integrates **scope, schedule, and cost** to measure project performance.

| Term                   | Formula                        | Meaning         |
| ---------------------- | ------------------------------ | --------------- |
| **PV (Planned Value)** | Budgeted cost for work planned | Baseline amount |
| **EV (Earned Value)**  | Budgeted cost for work done    | Earned progress |
| **AC (Actual Cost)**   | Actual cost of work performed  | Money spent     |

---

### 🧮 **Variance Calculations**

| Metric                               | Formula | Interpretation                               |
| ------------------------------------ | ------- | -------------------------------------------- |
| **CV (Cost Variance)**               | EV - AC | + = under budget, − = over budget            |
| **SV (Schedule Variance)**           | EV - PV | + = ahead of schedule, − = behind schedule   |
| **CPI (Cost Performance Index)**     | EV ÷ AC | >1 = under budget, <1 = over budget          |
| **SPI (Schedule Performance Index)** | EV ÷ PV | >1 = ahead of schedule, <1 = behind schedule |

---

### 🔮 **Forecasting**

| Forecast                         | Formula               | Meaning                           |
| -------------------------------- | --------------------- | --------------------------------- |
| **EAC (Estimate at Completion)** | AC + (BAC − EV) / CPI | Forecast total cost               |
| **ETC (Estimate to Complete)**   | EAC − AC              | Cost remaining                    |
| **VAC (Variance at Completion)** | BAC − EAC             | + = under budget, − = over budget |

---

**Example:**

* BAC = ₹100,000
* EV = ₹40,000
* AC = ₹50,000
* CPI = EV ÷ AC = 0.8 → over budget
* EAC = BAC ÷ CPI = 100,000 ÷ 0.8 = ₹125,000 → expected overrun ₹25,000

---

## 🧩 **Types of Reserves**

| Type                    | Purpose              | Controlled by     |
| ----------------------- | -------------------- | ----------------- |
| **Contingency Reserve** | For identified risks | Project Manager   |
| **Management Reserve**  | For unknown risks    | Senior Management |

**Total Budget = Cost Baseline + Management Reserve**

---

## 💡 **Key Terms**

| Term                                     | Meaning                                                      |
| ---------------------------------------- | ------------------------------------------------------------ |
| **Cost Baseline**                        | Approved time-phased budget used to track performance        |
| **Budget at Completion (BAC)**           | Total planned budget for the project                         |
| **Earned Value (EV)**                    | Value of completed work                                      |
| **To-Complete Performance Index (TCPI)** | Efficiency needed to meet BAC/EAC                            |
| **Life Cycle Costing**                   | Total cost of ownership (development + operation + disposal) |

---

## 📈 **Example Scenario**

You’re managing a **Mobile App Project**:

* Planned for 6 months with ₹12L budget
* After 3 months:

  * Planned to complete 50% (PV = ₹6L)
  * Actually completed 40% (EV = ₹4.8L)
  * Spent ₹7L (AC = ₹7L)

Now calculate:

* **CV = EV - AC = ₹4.8L - ₹7L = -₹2.2L → Over Budget**
* **SV = EV - PV = ₹4.8L - ₹6L = -₹1.2L → Behind Schedule**
* **CPI = EV ÷ AC = 4.8 ÷ 7 = 0.69 → Inefficient spending**
* **SPI = EV ÷ PV = 4.8 ÷ 6 = 0.8 → Progressing slowly**

---

## 🧠 **PMP Exam Tips**

✅ “How will costs be measured, tracked, and reported?” → **Plan Cost Management**
✅ “Estimating cost for each work package?” → **Estimate Costs**
✅ “Aggregating cost estimates to get total project cost?” → **Determine Budget**
✅ “Tracking performance and variances?” → **Control Costs (EVM)**
✅ “CPI < 1, SPI < 1” → project is **over budget & behind schedule**
✅ “Contingency reserve vs Management reserve” → know who controls which

---

## 🏁 **Summary Table**

| Process          | Objective                                  | Key Output                      |
| ---------------- | ------------------------------------------ | ------------------------------- |
| Plan Cost Mgmt   | Define how to plan, manage & control costs | Cost Management Plan            |
| Estimate Costs   | Approximate monetary resources             | Cost Estimates                  |
| Determine Budget | Aggregate costs & set baseline             | Cost Baseline                   |
| Control Costs    | Monitor and control cost performance       | Cost Forecasts, Change Requests |

---

# 🧩 **Cost Management Overview**

**Purpose:**
To ensure the project is completed **within the approved budget**.
It involves estimating, budgeting, financing, funding, managing, and controlling costs.

### **Main Processes (PMBOK®-based)**

1. **Plan Cost Management** – Define how project costs will be estimated, budgeted, managed, monitored, and controlled.
2. **Estimate Costs** – Approximate the monetary resources required for project activities.
3. **Determine Budget** – Aggregate the estimated costs to establish an authorized cost baseline.
4. **Control Costs** – Monitor and update project costs and manage changes to the cost baseline.

---

## 🧭 **Cost Management Process**

### **1. Cost Management Plan**

* A component of the **Project Management Plan** that describes:

  * How cost will be planned, structured, and controlled.
  * Units of measure, accuracy, precision.
  * Control thresholds.
  * Reporting formats.

**Example:**
For your **Social Game App (Rummy, Teen Patti, Call Break)** — the Cost Management Plan could define:

* Use of INR as currency.
* Variance threshold of ±10%.
* Monthly cost reporting.

---

## 💰 **Earned Value Analysis (EVA)**

EVA integrates **scope, schedule, and cost** to measure project performance and forecast outcomes.

### **Key Terms and Formulas**

| Term                                     | Definition                              | Formula                          | Example                       |
| ---------------------------------------- | --------------------------------------- | -------------------------------- | ----------------------------- |
| **PV (Planned Value)**                   | Budgeted cost of work scheduled         | —                                | ₹100,000 planned by month 3   |
| **EV (Earned Value)**                    | Budgeted cost of work performed         | —                                | ₹80,000 worth of work done    |
| **AC (Actual Cost)**                     | Actual cost incurred for work performed | —                                | ₹90,000 spent                 |
| **CPI (Cost Performance Index)**         | Efficiency of cost                      | `CPI = EV / AC`                  | 0.89 → over budget            |
| **SPI (Schedule Performance Index)**     | Schedule efficiency                     | `SPI = EV / PV`                  | 0.8 → behind schedule         |
| **BAC (Budget at Completion)**           | Total planned budget                    | —                                | ₹500,000                      |
| **EAC (Estimate at Completion)**         | Expected final cost                     | `EAC = BAC / CPI`                | ₹561,800                      |
| **ETC (Estimate to Complete)**           | Expected remaining cost                 | `ETC = EAC - AC`                 | ₹471,800 left                 |
| **VAC (Variance at Completion)**         | Expected budget surplus/deficit         | `VAC = BAC - EAC`                | -₹61,800 (overrun)            |
| **CV (Cost Variance)**                   | Difference between EV and AC            | `CV = EV - AC`                   | -₹10,000                      |
| **SV (Schedule Variance)**               | Difference between EV and PV            | `SV = EV - PV`                   | -₹20,000                      |
| **TCPI (To Complete Performance Index)** | Cost efficiency needed to meet BAC      | `TCPI = (BAC - EV) / (BAC - AC)` | If > 1 → difficult to achieve |

**Interpretation Example:**
If your game app project CPI = 0.9 and SPI = 0.8 →
You are **10% over budget and 20% behind schedule**.

---

## 📉 **Cost Baseline**

* The approved version of the **time-phased project budget** (excluding management reserves).
* Used to **compare actual results** to detect variances.

**Example:**

* Month 1 budget = ₹50k
* Month 2 budget = ₹70k
* Month 3 budget = ₹80k
  → Total **Cost Baseline = ₹200k**

---

## 💵 **Cost Budget**

* Includes **Cost Baseline + Management Reserves** = Total authorized funding.

---

## 📊 **Performance Measurement Baseline**

* The integrated scope, schedule, and cost baseline used for **EVM tracking**.

---

## 🔢 **Estimating Techniques**

| Technique                  | Description                                                                                 | Example                                      |
| -------------------------- | ------------------------------------------------------------------------------------------- | -------------------------------------------- |
| **Three-Point Estimating** | Considers uncertainty using optimistic (O), pessimistic (P), and most likely (M) estimates. | E = (O + 4M + P) / 6                         |
| **Analogous Estimating**   | Based on past similar projects (high-level).                                                | Last Rummy app cost ₹5L → use that estimate. |
| **Bottom-Up Estimating**   | Sum of detailed estimates of components.                                                    | UI ₹1L + API ₹2L + Server ₹1L = ₹4L          |
| **Parametric Estimating**  | Uses statistical relationships.                                                             | ₹500 per screen × 40 screens = ₹20,000       |
| **Heuristics**             | Rule of thumb.                                                                              | 15% of development cost = testing budget.    |

---

## 📋 **Inputs to Cost Estimation**

* Scope baseline
* Project schedule
* Resource rates
* Risk register
* Enterprise environmental factors (EEFs)
* Organizational process assets (OPAs)

---

## 🎯 **Types of Estimates**

| Type                               | Accuracy     | Example                      |
| ---------------------------------- | ------------ | ---------------------------- |
| **Rough Order of Magnitude (ROM)** | -25% to +75% | Initial estimate: ₹10L ± ₹5L |
| **Budget Estimate**                | -10% to +25% | During planning              |
| **Definitive Estimate**            | -5% to +10%  | After scope finalization     |

---

## 🧱 **Reserves**

| Type                     | Purpose                                      | Example                           |
| ------------------------ | -------------------------------------------- | --------------------------------- |
| **Contingency Reserves** | Known-unknowns; part of cost baseline.       | Server downtime repair cost.      |
| **Management Reserves**  | Unknown-unknowns; not part of cost baseline. | Unexpected legal compliance cost. |

---

## ⚙️ **Variable vs Fixed Costs**

* **Variable:** Change with production. (e.g., hosting, API usage)
* **Fixed:** Stay same. (e.g., office rent)

---

## 🧾 **Direct vs Indirect Costs**

* **Direct:** Clearly attributable to the project. (e.g., developer salaries)
* **Indirect:** Shared overhead. (e.g., HR, utilities)

---

## 🚦 **Control Thresholds**

* Define acceptable variance limits.
  Example: ±10% variance → if exceeded, trigger corrective action.

---

## 📢 **Progress Reporting**

* Compare **EV, AC, and PV** to show cost/schedule health.
* Use graphs like **S-curves** or **EVM trend charts** for stakeholders.

---

### **Example Summary — Game App Cost Scenario**

| Metric                     | Value                              | Meaning                   |
| -------------------------- | ---------------------------------- | ------------------------- |
| PV                         | ₹200,000                           | Planned budget by Month 4 |
| EV                         | ₹180,000                           | Work done worth ₹180k     |
| AC                         | ₹210,000                           | Actually spent ₹210k      |
| CPI = 0.86                 | Cost inefficiency (overspent)      |                           |
| SPI = 0.9                  | Behind schedule                    |                           |
| EAC = ₹500k / 0.86 = ₹581k | Project will exceed budget by ₹81k |                           |

---

## ✅ **In Summary**

| Concept                  | Description                                         |
| ------------------------ | --------------------------------------------------- |
| **Plan Cost Management** | Defines how cost will be handled                    |
| **Estimate Costs**       | Quantify money for each activity                    |
| **Determine Budget**     | Aggregate costs to create baseline                  |
| **Control Costs**        | Monitor and manage cost performance                 |
| **Tools**                | EVM, variance analysis, forecasting                 |
| **Outputs**              | Cost baseline, performance reports, change requests |