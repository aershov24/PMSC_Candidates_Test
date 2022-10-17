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