---
tags: [example, wbs, agile]
---
# Worked Example: Pac-Man Game WBS (Scrum)

3-level WBS excerpt, organized by **sprint** instead of SDLC phase — shows how a WBS adapts to Agile.

| Code | Task | Level | Key Resources | Dependencies | Effort (hrs) |
|---|---|---|---|---|---|
| 1 | Sprint 0: Initial Setup | 2 | PO, Scrum Master, DevOps | None | 40 |
| 1.1 | Define User Stories | 3 | PO, Scrum Master | None | 20 |
| 1.2 | Set Up Dev Environment | 3 | DevOps, Developer | None | 20 |
| 2 | Sprint 1: Core Game Mechanics | 2 | PO, Developer, QA | 1.2 | 160 |
| 2.1 | Develop & Test Basic Movement | 3 | Developer, QA | 1.1 | 40 |
| 2.2 | Code & Test Collision Mechanics | 3 | Developer, QA | 2.1 | 40 |
| 2.3 | Code & Test Scoring System | 3 | Developer, QA | 2.2 | 40 |
| 2.4 | Sprint Review & Retrospective | 3 | Scrum Team | 2.3 | 40 |
| 3 | Sprint 2: Advanced Gameplay | 2 | PO, Developer, QA | 2 | 160 |
| 4 | Sprint 3: UI & Level Design | 2 | PO, Developer, Game Designer, QA | 3 | 160 |
| 5 | Sprint 4: Final Integration & Testing | 2 | PO, Developer, QA | 4 | 160 |
| 6 | Release & Post-Launch Support | 2 | PO, Developer, IT Support | 5 | 80 |

**Key difference from Waterfall WBS:** Level 2 items are **sprints** (time-boxed, ~2–4 weeks each) rather than sequential SDLC phases, and testing is **embedded in every sprint** instead of being a single phase at the end.

👉 Pairs with [[Worked Example - Pac-Man RACI (Scrum)]]

## Related
- [[WBS Comprehensive Guide]]
- [[Scrum Methodology]]
