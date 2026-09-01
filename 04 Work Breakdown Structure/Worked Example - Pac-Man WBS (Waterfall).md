---
tags: [example, wbs, waterfall]
---
# Worked Example: Pac-Man Game WBS (Waterfall)

3-level WBS excerpt, Waterfall SDLC methodology.

| Code | Task | Level | Key Resources | Dependencies | Effort (hrs) |
|---|---|---|---|---|---|
| 1 | Requirements Gathering & Analysis | 2 | PM, Game Designer, Developer, IT Support | None | 60 |
| 1.1 | Define Game Requirements | 3 | PM, Game Designer | None | 20 |
| 1.2 | Conduct Feasibility Study | 3 | PM, Developer, IT Support | 1.1 | 20 |
| 1.3 | Stakeholder Alignment | 3 | PM, Game Designer | 1.1, 1.2 | 20 |
| 2 | System Design | 2 | Game Designer, Developer, IT Support | 1.3 | 80 |
| 2.1 | Design Game Architecture | 3 | Game Designer, Developer | 1.3 | 30 |
| 2.2 | Design User Interface (UI) | 3 | Game Designer | 2.1 | 30 |
| 2.3 | Design Gameplay Flow | 3 | Game Designer, Developer | 2.1 | 20 |
| 3 | Development | 2 | Developer, Game Designer, IT Support | 2.3 | 200 |
| 3.1 | Setup Development Environment | 3 | Developer, IT Support | 2.3 | 40 |
| 3.2 | Code Game Mechanics | 3 | Developer, Game Designer | 3.1 | 100 |
| 3.3 | Create Visual & Audio Assets | 3 | Game Designer | 3.1 | 60 |
| 4 | Testing | 2 | QA Tester, Developer | 3 | 120 |
| 5 | Deployment | 2 | PM, Developer, IT Support | 4 | 40 |
| 6 | Maintenance & Support | 2 | IT Support, Developer, QA Tester | 5 | 120 |

**Note on structure:** Level 1 = "Pac-Man Game Development Project" (implied root). Level 2 = the 6 SDLC phases (deliverable/phase-based WBS). Level 3 = work packages within each phase, sized close to the 8/80 rule.

👉 Pairs with [[Worked Example - Pac-Man RACI (Waterfall)]]

## Related
- [[WBS Comprehensive Guide]]
- [[Waterfall Methodology]]
