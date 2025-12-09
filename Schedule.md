# 🕒 **Project Schedule Management** (PMBOK® – Knowledge Area #6)

## 🎯 **Definition:**

> Project Schedule Management involves the **processes required to manage the timely completion** of the project.

It ensures the project is delivered **on time**, balancing scope, cost, and resource constraints.

---

## 📘 **Objective:**

* Define project **activities**
* Determine **sequence**
* Estimate **resources** and **durations**
* Develop a **realistic schedule baseline**
* **Monitor and control** progress against that baseline

---

## 🔹 **Processes in Schedule Management (6 Total)**

| # | Process Name                | Process Group            | Key Output                             |
| - | --------------------------- | ------------------------ | -------------------------------------- |
| 1 | Plan Schedule Management    | Planning                 | Schedule Management Plan               |
| 2 | Define Activities           | Planning                 | Activity List                          |
| 3 | Sequence Activities         | Planning                 | Project Schedule Network Diagram       |
| 4 | Estimate Activity Durations | Planning                 | Duration Estimates                     |
| 5 | Develop Schedule            | Planning                 | Schedule Baseline                      |
| 6 | Control Schedule            | Monitoring & Controlling | Work Performance Info, Change Requests |

---

# 🧭 **1️⃣ Plan Schedule Management**

**Purpose:**
Define *how* the project schedule will be developed, monitored, and controlled.

**Key Inputs:**

* Project Charter
* Project Management Plan
* EEFs & OPAs

**Key Output:**
✅ **Schedule Management Plan** — Defines:

* Scheduling methodology (Agile, Rolling Wave, Critical Path)
* Tools/software (MS Project, Jira, Primavera, etc.)
* Units of measure (hours, days, weeks)
* Rules for updating schedule
* Control thresholds (e.g., ±10% variance allowed)

**Lesson:**
It sets the *framework and standards* for managing time across the project.

---

# 🧱 **2️⃣ Define Activities**

**Purpose:**
Break down **work packages (from WBS)** into smaller, actionable **activities**.

**Key Tools & Techniques:**

* Decomposition
* Rolling Wave Planning (plan near-term in detail, future in rough)

**Key Outputs:**
✅ Activity List
✅ Activity Attributes (owner, location, duration, etc.)
✅ Milestone List

**Example:**
If WBS has *“Develop Payment Module”*, activities may be:

* Design database
* Integrate payment gateway
* Test API

**Lesson:**
Activities are the **lowest-level tasks** used for time estimation and scheduling.

---

# 🔗 **3️⃣ Sequence Activities**

**Purpose:**
Identify and document **dependencies** (relationships) between activities.

**Types of Dependencies:**

| Type                      | Description                                | Example                  |
| ------------------------- | ------------------------------------------ | ------------------------ |
| **FS (Finish to Start)**  | Task A must finish before Task B can start | Code → Test              |
| **SS (Start to Start)**   | Tasks start together                       | Design & Documentation   |
| **FF (Finish to Finish)** | Tasks finish together                      | Testing & Quality Review |
| **SF (Start to Finish)**  | Rare case                                  | Guard shift handover     |

**Outputs:**
✅ Project Schedule Network Diagram
✅ Updated Activity Attributes

**Tools:**

* Precedence Diagramming Method (PDM)
* Leads & Lags

**Lesson:**
Dependencies define **logical order**, ensuring the project flows smoothly.

---

# ⏱ **4️⃣ Estimate Activity Durations**

**Purpose:**
Estimate how long each activity will take.

**Inputs:**

* Activity list & attributes
* Resource calendar
* Risk register

**Techniques:**

| Method                            | Description                        | Example                    |
| --------------------------------- | ---------------------------------- | -------------------------- |
| **Expert Judgment**               | Based on experience                | Developer estimates 5 days |
| **Analogous Estimating**          | Based on previous similar projects | Last project took 10 days  |
| **Parametric Estimating**         | Based on measurable parameters     | 100 lines of code/day      |
| **Three-Point Estimating (PERT)** | (O + 4M + P)/6                     | (2 + 4×3 + 6)/6 = 3.3 days |
| **Bottom-up Estimating**          | Aggregate small tasks              | Sum of all sub-activities  |

**Outputs:**
✅ Duration Estimates
✅ Basis of Estimates

**Lesson:**
Accurate duration = realistic schedule = higher project credibility.

---

# 📅 **5️⃣ Develop Schedule**

**Purpose:**
Combine all activities, durations, dependencies, and resources into an **approved schedule baseline**.

**Tools & Techniques:**

* Critical Path Method (CPM)
* Schedule Compression (Crashing / Fast Tracking)
* What-If Analysis
* Resource Optimization (Leveling / Smoothing)
* Leads and Lags
* Agile Iteration Planning

**Outputs:**
✅ Project Schedule (Gantt Chart, Milestone Chart, Network Diagram)
✅ Schedule Baseline
✅ Schedule Data
✅ Project Calendar

**Key Concepts:**

* **Critical Path:** The longest path in the network → determines project duration.
* **Float (Slack):** The amount of time an activity can delay without affecting the project end date.

**Lesson:**
This is your *final, approved timeline* used for tracking project progress.

---

# 📊 **6️⃣ Control Schedule**

**Purpose:**
Monitor project progress and manage schedule changes.

**Key Activities:**

* Compare **actual vs. planned** performance
* Calculate **Schedule Variance (SV)** and **Schedule Performance Index (SPI)**
* Take corrective/preventive action as needed

**Formulas (Earned Value Management):**

* **SV = EV – PV** (Schedule Variance)

  * > 0 → ahead of schedule
  * <0 → behind schedule
* **SPI = EV ÷ PV** (Schedule Performance Index)

  * > 1 → ahead of schedule
  * <1 → behind schedule

**Outputs:**
✅ Work Performance Information
✅ Change Requests (if schedule deviations exceed thresholds)

**Lesson:**
Control Schedule = *keep project on track, update baselines when approved.*

---

## ⚙️ **Key Concepts & Terms**

| Term              | Meaning                                                 |
| ----------------- | ------------------------------------------------------- |
| **Critical Path** | Longest duration path → determines project finish date  |
| **Float (Slack)** | Time an activity can delay without delaying the project |
| **Crashing**      | Add resources to shorten duration (increases cost)      |
| **Fast Tracking** | Overlap tasks to shorten schedule (increases risk)      |
| **Lead**          | Task starts before its predecessor finishes             |
| **Lag**           | Delay between two tasks                                 |

---

## 🧩 **Schedule Management in Predictive vs. Agile Projects**

| Aspect   | Predictive         | Agile / Adaptive                        |
| -------- | ------------------ | --------------------------------------- |
| Planning | Detailed upfront   | Iterative & Rolling Wave                |
| Schedule | Fixed baseline     | Flexible (sprints, backlogs)            |
| Tracking | Gantt, EVM         | Burndown charts, velocity               |
| Control  | Focus on variances | Focus on team delivery and adaptability |

---

## 🧠 **Real-World Example**

Let’s say you’re managing a **Game App Development** project.

1️⃣ **Define Activities** – UI design, API integration, payment gateway, testing
2️⃣ **Sequence Activities** – UI before integration; integration before testing
3️⃣ **Estimate Durations** – 5, 10, 7, and 4 days respectively
4️⃣ **Develop Schedule** – You find the total duration is 26 days
5️⃣ **Control Schedule** – During execution, integration is delayed by 3 days → SPI drops to 0.9 → You apply fast-tracking by parallelizing testing with integration.

---

## 🏁 **Summary Table**

| Process             | Objective                   | Key Output         |
| ------------------- | --------------------------- | ------------------ |
| Plan Schedule Mgmt  | Define scheduling approach  | Schedule Mgmt Plan |
| Define Activities   | Break work into tasks       | Activity List      |
| Sequence Activities | Establish logical order     | Network Diagram    |
| Estimate Durations  | Determine time per task     | Duration Estimates |
| Develop Schedule    | Build final timeline        | Schedule Baseline  |
| Control Schedule    | Monitor and update schedule | Change Requests    |

---

✅ **PMP Exam Tip:**

* “Activity sequencing” or “dependency” → **Sequence Activities**
* “Duration calculation” → **Estimate Activity Durations**
* “Critical Path or compression” → **Develop Schedule**
* “Variance or performance index” → **Control Schedule**

---

* Planning Schedule Management
* Schedule Management Plan
* Defining Sequencing Activities
  - Defining Activities
  - Rolling Wave Planning
  - Milestones
  - Sequencing Activities
  - Precedence Diagramming Method (PDM)
  - Types of Activities
    - Finish To Start (FS)
    - Start To Start (SS)
    - Finish To Finish (FF)
    - Start To Finish (SF)
  - Types of Dependencies
    - Mandatory Dependency (Hard Logic)
    - Discretionary Dependency (Preferred, Preferential, Or Soft Logic)
    - External Dependency
    - Internal Dependency
  - Dependencies in Hybrid Environments
  - Leads and Lags
  - Project Schedule Network Diagram
  - Estimating The schedule
  - How is Estimating Done
  - Relative Sizing
  - One Point Estimating
  - Analogous Estimating
  - Parametric Estimating
  - Bottom Up Estimating
  - Affinity Estimating
  - T-Shirt Sizing
  - Planning Poker
  - Data Analysis
  - Decision Making
  - Preparing The Schedule
  - Schedule Network Analysis


# 🕐 **Project Schedule Management (PMP Knowledge Area)**

## 🧭 **Purpose**

The Schedule Management Knowledge Area ensures timely completion of the project by defining:

* *What work needs to be done* (activities)
* *How long each activity will take*
* *When it should start and finish*
* *Who will perform it*

---

## 🧩 **Schedule Management Process**

| Process                         | Description                                                           | Example                                                                  |
| ------------------------------- | --------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| **Plan Schedule Management**    | Create policies and procedures for planning and controlling schedule. | Define tools (MS Project, Jira), reporting format, and update frequency. |
| **Define Activities**           | Break WBS work packages into smaller activities.                      | Split “Game Logic Module” into: design → develop → test → integrate.     |
| **Sequence Activities**         | Identify dependencies between activities.                             | UI design must finish before development starts.                         |
| **Estimate Activity Durations** | Determine time required for each activity.                            | “Build multiplayer server” = 10 days.                                    |
| **Develop Schedule**            | Create schedule baseline, charts, and timeline.                       | Build Gantt chart showing task durations and dependencies.               |
| **Control Schedule**            | Monitor progress and manage deviations.                               | Compare actual vs baseline every sprint.                                 |

---

## 📘 **Schedule Baseline**

Approved version of the project schedule — used for comparison and performance tracking.
It includes:

* Start & finish dates
* Milestones
* Dependencies

✅ *Example:*
App development planned from **Jan–Mar 2025** with milestones like “UI Completed by Jan 30.”

---

## ⚡ **Schedule Compression**

Used when you must meet a tight deadline **without changing the scope**.

### 1. **Crashing**

Add more resources or overtime to shorten duration.
⚠️ Increases cost.

✅ *Example:* Hire 2 extra Unity developers to finish testing sooner.

### 2. **Fast Tracking**

Perform tasks in parallel that were originally sequential.
⚠️ Increases risk.

✅ *Example:* Start backend API development before UI is finalized.

---

## 📋 **Activity List**

A complete list of all project activities, with identifiers and descriptions.
Derived from WBS work packages.

✅ *Example:*

| ID | Activity            | Duration | Dependency |
| -- | ------------------- | -------- | ---------- |
| A1 | Design Home Screen  | 3 days   | –          |
| A2 | Develop Home Screen | 5 days   | A1         |
| A3 | Test Home Screen    | 2 days   | A2         |

---

## 🔗 **Network Diagram**

A visual representation of activity sequences and dependencies.
Helps identify the **critical path** and potential bottlenecks.

✅ *Example:*

```
Design UI → Develop UI → Test UI → Deploy UI
```

---

## ⚙️ **Dependencies (Logical Relationships)**

| Type                           | Description                                | Example                                                        |
| ------------------------------ | ------------------------------------------ | -------------------------------------------------------------- |
| **Mandatory (Hard Logic)**     | Inherent or physical dependency.           | Must build the database before connecting APIs.                |
| **Discretionary (Soft Logic)** | Based on team preference or best practice. | Test after code review, though technically could test earlier. |
| **External**                   | Depends on outside factor.                 | App Store approval.                                            |
| **Internal**                   | Within the project team’s control.         | Backend must be complete before frontend integration.          |

---

## 🧩 **Precedence Diagramming Method (PDM)**

Technique for constructing network diagrams using activity nodes.

4 relationship types:

* **Finish-to-Start (FS):** Default — e.g., Code must finish before testing starts.
* **Start-to-Start (SS):** Both start together — e.g., Backend and frontend can start simultaneously.
* **Finish-to-Finish (FF):** Both finish together — e.g., Testing and documentation.
* **Start-to-Finish (SF):** Rare — one activity must start before another finishes.

---

## 🔴 **Critical Path**

The **longest path** through the project network — determines **minimum project duration**.
Any delay in critical path = project delay.

✅ *Example:*
UI → API → Testing → Deployment (if it’s longest duration chain)

---

## ⚖️ **Relative Sizing (Agile Estimation)**

Compare tasks to each other rather than absolute hours.

✅ *Example:*
If “Login Module” = 2 points,
and “Multiplayer Feature” is roughly 3× harder,
then “Multiplayer” = 6 points.

---

## 🧮 **Story Points**

A numeric value expressing *effort*, *complexity*, and *risk*.
Common Agile units for sprint planning.

✅ *Example:*

* Simple = 2 points
* Medium = 5 points
* Complex = 13 points

---

## ⏳ **Float (Schedule Flexibility)**

| Type              | Definition                                                                 | Example                                                  |
| ----------------- | -------------------------------------------------------------------------- | -------------------------------------------------------- |
| **Total Float**   | How long an activity can be delayed *without delaying project completion.* | Task can slip 3 days with no impact.                     |
| **Free Float**    | Delay allowed without delaying next dependent task.                        | UI design can delay 1 day without affecting development. |
| **Project Float** | Delay allowed before missing external deadline.                            | Can delay entire project by 5 days before go-live.       |

---

## 📈 **Three-Point Estimating**

Formula to reduce uncertainty:

> **E = (O + 4M + P) / 6**

| Distribution                 | Description                                                   | Example                     |
| ---------------------------- | ------------------------------------------------------------- | --------------------------- |
| **Beta Distribution (PERT)** | Weighted average gives more weight to *most likely* estimate. | (2 + 4×5 + 10)/6 = 5.3 days |
| **Triangular Distribution**  | Simple average of three estimates.                            | (2 + 5 + 10)/3 = 5.7 days   |

✅ *Example:*
Estimate time for “Server Integration.”

---

## 🧮 **Monte Carlo Analysis**

Simulates thousands of project outcomes to predict completion probability.
Used in risk analysis.

✅ *Example:*
Simulation shows 85% chance to finish by June 15.

---

## 📊 **Bar Charts (Gantt Charts)**

Visual representation of activities over time.
Shows task durations, overlaps, and dependencies.

✅ *Example:*
MS Project or Jira Timeline view.

---

## 📘 **Schedule Model**

A model that represents the plan to execute the project.
It includes:

* Activities
* Durations
* Dependencies
* Resources
* Calendars

✅ *Tool:* Primavera, MS Project, Jira Advanced Roadmaps.

---

## 📄 **Schedule Management Plan**

Defines how schedule will be:

* Developed
* Managed
* Controlled
* Reported

✅ *Example:*
All updates to schedule must be reviewed weekly by PMO.

---

## 🧩 **Critical Path Method (CPM)**

Technique to identify the sequence of activities determining project duration.
Used for:

* Finding float
* Predicting earliest and latest start/finish times

✅ *Example:*
If *Design → Dev → Test* takes 20 days total and is longest, that’s your critical path.

---

## 🔁 **Leads and Lags**

| Term     | Description                                       | Example                                                  |
| -------- | ------------------------------------------------- | -------------------------------------------------------- |
| **Lead** | Activity can start *before* predecessor finishes. | Start testing while development is 80% done.             |
| **Lag**  | Delay between tasks.                              | Wait 2 days after paint dries before testing UI visuals. |

---

## ⛰️ **Milestones / Milestone List / Chart**

* **Milestone:** Significant event (zero duration).
* **Milestone List:** All project milestones.
* **Milestone Chart:** Timeline view.

✅ *Example:*

* Alpha Release — Jan 15
* Beta — Feb 20
* Final — Mar 30

---

## 🏦 **Reserve Analysis**

Allocates **contingency reserves** (for known risks) and **management reserves** (for unknowns).

✅ *Example:*
Add 10% buffer to testing phase for bug delays.

---

## ⚠️ **Padding**

Adding extra time *without justification* — not a good practice in PMP.

---

## 📏 **Estimating Techniques**

| Technique                 | Description                        | Example                                       |
| ------------------------- | ---------------------------------- | --------------------------------------------- |
| **Analogous Estimating**  | Based on previous similar project. | Prior game app took 4 months → estimate same. |
| **Parametric Estimating** | Use statistical relationships.     | 5 screens × 3 days each = 15 days.            |
| **Bottom-Up Estimating**  | Estimate small tasks, then sum up. | Add duration of each micro task.              |
| **Heuristics**            | Rules of thumb.                    | “80-hour rule” for module-level estimates.    |

---

## 🧾 **Activity Attributes**

Details about each activity:

* ID, name, description
* Predecessors/successors
* Resource requirements
* Constraints

✅ *Stored in:* Excel or project management software.

---

## 🔁 **Rolling Wave Planning**

Plan near-term work in detail and far-term work at a higher level.

✅ *Example:*
Sprint 1 detailed; Sprint 4 planned broadly.

---

## 🔄 **Progressive Elaboration**

Refining and detailing the plan continuously as more info becomes available.

✅ *Example:*
You refine testing estimates after prototype release.

---

## 💡 **Alternatives Analysis**

Comparing multiple methods to achieve task.
✅ *Example:*
Decide between using AWS ECS vs Firebase hosting.

---

## 🧠 **Affinity Estimating (Agile)**

Group stories by similarity before assigning points.
✅ *Example:*
Group all “UI-related stories” as same difficulty level.

---

## 👕 **T-Shirt Sizing**

Relative estimation using categories: XS, S, M, L, XL.
✅ *Example:*
Login = S, Multiplayer = L, Payment System = XL.

---

## 🃏 **Planning Poker**

Team estimation technique:
Each member chooses a card (number) for story effort, discuss, and reach consensus.

---

## 🧍‍♂️ **Resource Optimization**

| Technique              | Description                                                                      | Example                                                     |
| ---------------------- | -------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| **Resource Leveling**  | Adjust start/end dates to resolve resource conflicts — may change critical path. | Dev working on two features simultaneously, shift one task. |
| **Resource Smoothing** | Adjust resources *without changing critical path*.                               | Reassign minor tasks to balance workload.                   |

---

## 🚀 **Velocity (Agile)**

Average number of story points completed per iteration.
Used for forecasting future sprint capacity.

✅ *Example:*
Sprint 1 = 20 pts, Sprint 2 = 22 pts → Velocity ≈ 21 pts.

---

## 🗺️ **Agile Release Planning**

High-level plan mapping features or epics across releases or iterations.

✅ *Example:*
Release 1: Rummy core gameplay
Release 2: Teen Patti multiplayer
Release 3: Leaderboard + Coins Shop

---

## 📈 **Cumulative Flow Diagrams (CFD)**

Shows the number of tasks in each state (To Do, In Progress, Done) over time.
Helps identify bottlenecks.

✅ *Example:*
If “In Progress” keeps growing, development is slower than expected.

---

## 🔁 **Re-Estimating**

Updating activity durations or story points based on actual progress or new data.

✅ *Example:*
Testing took longer due to device lag → re-estimate future sprints accordingly.

---

# 🏁 **Summary Table**

| Concept               | Purpose                     | Example                    |
| --------------------- | --------------------------- | -------------------------- |
| Schedule Baseline     | Approved timeline reference | Launch plan                |
| Compression           | Save time                   | Fast track design + dev    |
| Critical Path         | Longest sequence            | UI → API → QA              |
| Float                 | Time flexibility            | 3-day buffer               |
| Estimating            | Forecast durations          | Analogous / Parametric     |
| Resource Optimization | Manage workload             | Level developer effort     |
| Velocity              | Agile speed                 | 21 story points per sprint |