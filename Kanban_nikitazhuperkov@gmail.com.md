# Topic: Kanban

**Author**: Nick Zhuperkov

**QAs Total**: 3

---

## Q1: Name Basic Metrics that are used in Kanban.

**Difficulty:** `Junior`

**Source:**

https://kanbanguides.org/english/#:~:text=The%20four%20mandatory,work%20item%20finished.

**Answer:**

The four mandatory flow measures to track are:

* **WIP (Work In Progress):** The number of work items started but not finished.
* **Throughput:** The number of work items finished per unit of time. Note the measurement of throughput is the exact count of work items.
* **Work Item Age:** The amount of elapsed time between when a work item started and the current time.
* **Cycle Time:** The amount of elapsed time between when a work item started and when a work item finished.

---

## Q2: What is the difference between Acceptance Criteria and DoD (Definition of Done)?

**Difficulty:** `Middle`

**Source:**

https://www.visual-paradigm.com/scrum/definition-of-done-vs-acceptance-criteria/#:~:text=VS%20ACCEPTANCE%20CRITERIA-,Definition%20of%20Done%20vs%20Acceptance%20Criteria,-Definition%20of%20Done

**Answer:**

**Definition of Done (DoD)** is a list of requirements that a user story must adhere to for the team to call it complete.  
**Acceptance Criteria (AC)** of a User Story consist of set of Test Scenarios that are to be met to confirm that the software is working as expected.

The difference between these two is that the **DoD** is common for all the User Stories whereas the **AC** is applicable to specific User Story. **AC** of each User Story will be different based on the requirements of that User Story.

In other words, Both **DoD** and **AC** must be met in order to complete the User Story.  The Product Increment is not considered to be complete, unless both these two lists are done. Thus, we need to define two aspects of the **Definition of Done (DoD)** – Completion Criteria and **Acceptance Criteria (AC)**:

![](https://www.visual-paradigm.com/servlet/editor-content/scrum/definition-of-done-vs-acceptance-criteria/sites/7/2018/11/definition-of-done-vs-acceptance-criteria.png)

---

## Q3: How to build Continuous Delivery Pipeline with DevOps in SAFe 5.1?

**Difficulty:** `Senior`

**Source:**

https://www.scaledagileframework.com/continuous-delivery-pipeline/#:~:text=The%20Four%20Aspects,long%20after%20release.

**Answer:**

The **SAFe Continuous Delivery Pipeline** contains four aspects: *continuous exploration*, *continuous integration*, *continuous deployment*, and *release on demand*. The **CDP** enables organizations to map their current pipeline into a new structure and then use relentless improvement to deliver value to customers.

* **Continuous Exploration (CE)** focuses on creating alignment on what needs to be built.
* **Continuous Integration (CI)** focuses on taking features from the Program backlog and implementing them.
* **Continuous Deployment (CD)** takes the changes from the staging environment and deploys them to production.
* **Release on Demand (RoD)** is the ability to make value available to customers all at once, or in a staggered fashion based market and business needs

![](https://stagingv5.wpenginepowered.com/wp-content/uploads/2021/02/CDP_F01_WEB-3.png)

**NOTE**: A shorter version that I used to remember key points.

**Continuous Exploration** - Understand Customer needs - Hypothesize, Collaborate & Research, Architect, Synthesize;  
**Continuous Integration** – A critical technical practice of the ART - Develop, Build, Test End-to-End, Stage;  
**Continuous Deployment** – Getting to production early - Deploy, Verify, Monitor, Respond - Deploy to Staging every Iteration, Automate deployment, Automate testing of features and NFRs, Decouple deployment from release;  
**Release on Demand** - Release, Stabilize, Measure, Learn.

---
