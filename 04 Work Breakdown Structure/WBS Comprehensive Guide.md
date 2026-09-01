---
tags: [process, wbs]
---
# Work Breakdown Structure (WBS) — Comprehensive Guide

## What & Why
A **hierarchical breakdown** of total project work into smaller, manageable components.
- Improves estimation of time, cost, resources
- Improves team coordination
- Foundation document for scheduling, cost, resources, and change control

## Key Features
- Hierarchical structure
- Defines **deliverables**, not actions
- Each level = more detail
- Follows the **100% Rule** (all work is included — if it's not in the WBS, it's not part of the project)
- Built via **decomposition**

## Levels
- **Level 1:** Project name (top)
- **Level 2:** Major deliverables/phases
- **Level 3:** Sub-deliverables
- **Level 4+:** Work packages (smallest unit)

**Example (Website Development Project):**
```
L1  Website Development Project
L2  ├─ Front-End Development
L3  │   ├─ UI/UX Design
L3  │   ├─ Coding
L3  │   └─ Testing
L4  │       └─ Wireframes, HTML/CSS Development
```

## Formats
1. **Tree diagram** (hierarchical/visual)
2. **Outline view** (numbered list, e.g. 1, 1.1, 1.1.1)

## Types of WBS
- **Deliverable-based** – organized by the final products/outputs (top tier = whole project, lower tiers = deliverables). Good when deliverables depend on each other.
- **Phase-based** – organized by project life-cycle phase (initiation, planning, execution, M&C, closure). Good when phases/tasks are sequential.

## Work Packages
The **smallest unit of work** in a WBS — essentially a sub-project.

**Guidelines (8/80 Rule & more):**
- **8/80 Rule:** each work package = 8–80 hours (1–10 days), matching a typical reporting period
- Total time & cost of each work package clearly defined
- Confirm it **cannot be decomposed further**
- **Only one person** assigned per work package
- Tracked/monitored start to finish

## Steps to Create a WBS
1. Define project scope
2. Identify major deliverables
3. Decompose deliverables into smaller tasks
4. Organize WBS levels logically
5. Assign WBS codes (e.g., 1, 1.1, 1.1.1)
6. Validate completeness using the 100% Rule

## Approaches to Developing a WBS
- **Guidelines** – some orgs (e.g. DOD) provide standard templates
- **Analogy** – adapt WBSs from similar past projects
- **Top-down** – start with the biggest items, break them down
- **Bottom-up** – start with specific tasks, roll them up
- **Mind-mapping** – branches radiating from a core idea

## Common Mistakes
- Mixing deliverables with activities (a WBS lists deliverables/nouns, not action verbs)
- Not following the 100% Rule
- Over-complicating the breakdown
- Skipping team collaboration

## Advice for a Good WBS / WBS Dictionary
- A unit of work appears in **only one place**
- The work content of an item = sum of the items below it
- Each item is the responsibility of **one individual**
- Must match how work will actually be performed
- Every WBS item needs a **WBS Dictionary entry** (detailed description of scope for that item)
- Must stay flexible enough to accommodate change

## What a WBS Does NOT Show
❌ Dependencies (that's the [[Gantt Chart]] / [[Critical Path Method (CPM)]])

## Practice
👉 [[WBS Practice Template (Blank)]]
👉 [[Worked Example - Pac-Man WBS (Waterfall)]]
👉 [[Worked Example - Pac-Man WBS (Scrum)]]
👉 [[Worked Example - VRAMS Preliminary Scope to WBS]]

## Related
- [[Work Breakdown Structure (Definition)]]
- [[Scope Management Processes]]
- [[Deliverable]]
