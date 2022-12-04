# Topic: Kanban

**Author**: Alex Smith

**QAs Total**: 2

---

## Q1: Name the _Core Properties_ of Kanban 

**Difficulty:** `Mid`

**Source:**

https://teamhood.com/kanban-resources/kanban-principles/

**Answer:**

There are the _Core Properties_ of Kanban:

* **Visualize the workflow** - Visualise what's actually happening, rather than what you want to happen (so represent reality over the ideal)
* **Limit Work in Progress (WIP)** - WIP Limits force the team to help finish existing work in progress rather than starting new work (bug fixing for the feature in QA, rather than starting a new feature development). This enables a new work is only ‘pulled’ in when there is enough capacity to handle it.
* **Manage the flow** - Focusing on the flow of tasks through the columns on the board highlights any potential bottlenecks. Work out what slows you down and how to get feedback faster.
* **Make process policies explicit** - Define, publish, and share your processes and policies. If you see something that isn't represented by your visualisaton, and it's part of implicit process, make it part of what you visualise. The team can't improve what the team can't see.
* **Improve collaboratively** - Use visual models & the scientific methods like The Theory of Constraints, The Theory of Profound Knowledge, The Lean Economic Model

---

## Q2: How do you deal with _bugs_ or mistakes in Kanban? Would you move items back on a board?

**Difficulty**: `Senior`

**Source:**

https://pm.stackexchange.com/questions/3935/kanban-moving-items-back-or-how-do-you-manage-mistakes

**Details**:

Given that you have a feature tracking through your Kanban board, the dev marks it done, it's pulled into QA, and the dev pulls in new work. QA fails the item.

Now what? Would you move the item back to the Dev stage? What will you do if you can't move it back into the dev stream as it's full?

**Answer:**

My first advice would be to treat your QA stage as the one **covering both**: _testing_ and _bug fixing_ which basically renders the problem of moving index cards anywhere irrelevant. Developers work in the QA stage (same as testers) when they are fixing production defects. 

I won't personally **move cards back** as it just adds a lot of hassle. You can have policies that you can violate limits in such situation but chaos introduced isn't worth the value.

Other options to consider might be: 
* You may **"park" features** which didn't pass testing. You may have dedicated subcolumn where you put such features so everyone knows that they require bug-fixing.
* You may just **visualize status of testing**, e.g. testing started, testing passed, testing failed, with additional visual signal and keep the index cards in QA column.
* You may **deal with bugs using additional information radiator**, usually not a full-blown Kanban board. Then, again, you keep the index cards in QA stage but you deal with bugs independently.

---

## Q3: What is the difference between _DMAIC_ and _DMADV_ in Six Sigma?

**Difficulty:** `Junior`

**Source:**

https://www.vinsys.com/blog/strategic-difference-between-dmaic-and-dmadv/#:~:text=With%20regard%20to%20measurement%2C%20DMAIC,model%20to%20meet%20customer%20requirements

**Answer:**

* **DMAIC** stands for: Define, Measure, Analyze, Improve, Control
* **DMADV** stands for: Define, Measure, Analyze, Design, Verify

Despite the first three shared letters of their names, there are some notable differences:
* **DMAIC** typically defines a business process and how it applies; **DMADV** defines customer needs as they relate to a service or product.
* **DMAIC** measures the current performance of a process, while **DMADV** measures customer specifications and needs.
* **DMAIC** focuses on making improvements to a business process to reduce or eliminate defects. **DMADV** develops an appropriate business model to meet customer requirements.

![](https://keydifferences.com/wp-content/uploads/2022/03/flow-chart.jpg)

---

## Q4: What is the role of the _1.5 Sigma Shift_?

**Difficulty**: `Senior`

**Source:**
https://www.qualitydigest.com/inside/six-sigma-column/15-sigma-shift-explained-040406.html

**Answer:**

Experience has shown that processes usually do not perform as well in the _long term_ as they do in the short term. As a result, the number of sigmas that will fit between the process mean and the nearest specification limit (SL) may well drop over time, compared to an initial short-term study. To account for this real-life increase in _process variation_ over time, an _empirically_ based 1.5 sigma shift is introduced into the calculation.

According to this idea, a process that fits 6 sigma between the process mean and the nearest specification limit in a short-term study will in the long term fit only 4.5 sigma – either because the process mean will move over time, or because the long-term standard deviation of the process will be greater than that observed in the short term, or both.

**NOTE**: With the introduction of the 1.5 Sigma Shift the "6 sigma" process will have long-term defect rates corresponding to 4.5 sigma performance rather than actual 6 sigma performance.

In practice, the 1.5 sigma shift results in the generally accepted six sigma value of **3.4 defects per million** opportunities:

![https://www.allaboutlean.com/wp-content/uploads/2014/03/SixSigmaNormalDistributionWithShift.png](https://www.allaboutlean.com/wp-content/uploads/2014/03/SixSigmaNormalDistributionWithShift.png)

_Ignoring_ the 1.5 sigma shift results in a six sigma value of **2 defects per billion** opportunities:

![https://www.allaboutlean.com/wp-content/uploads/2014/03/SixSigmaNormalDistribution.png](https://www.allaboutlean.com/wp-content/uploads/2014/03/SixSigmaNormalDistribution.png)