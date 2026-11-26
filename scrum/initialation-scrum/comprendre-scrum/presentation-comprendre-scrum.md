---
marp: true
theme: default
paginate: true
size: 16:9
style: |
  section {
    font-size: 24px;
    padding: 40px;
  }
  h1 {
    color: #1e3a8a;
  }
  h2 {
    color: #2563eb;
  }
---

# Understanding Agile & the Scrum Framework
## Applied to: **Fashion & Apparel Store**

Scrum Initiation Workshop

---

# 1. Waterfall (V-Model) vs. Agile

| Waterfall / V-Model | Agile Approach (Iterative) |
| :--- | :--- |
| Single delivery at the end of the project | Frequent deliveries via **Sprints** |
| Tunnel effect (no early user feedback) | Continuous customer feedback |
| Rigid and costly to change | Rapid adaptation to seasonal fashion trends |
| Late bug and usability detection | Continuous testing at every iteration |

---

# 2. The 4 Agile Values & 3 Empirical Pillars

### Agile Manifesto (4 Values)
- **Individuals & interactions** > Processes & tools
- **Working software** > Comprehensive documentation
- **Customer collaboration** > Contract negotiation
- **Responding to change** > Following a plan

### Empirical Pillars of Scrum
1. **Transparency:** Shared visibility on the backlog and progress.
2. **Inspection:** Regular evaluation of deliverables against goals.
3. **Adaptation:** Immediate adjustments when deviations occur.

---

# 3. The 3 Scrum Roles on **Fashion & Apparel Store**

- **Product Owner (PO)**
  - Defines product vision and prioritizes the *Product Backlog*.
  - *Example: Prioritizing clothing catalog browsing before inventory management.*
- **Scrum Master (SM)**
  - Upholds Scrum practices and removes team blockers.
- **Developers**
  - Build the application (Laravel, MySQL, Tailwind/Preline UI) and write automated tests.

---

# 4. The 5 Scrum Events

1. **The Sprint:** Fixed time-boxed iteration producing a working increment.
2. **Sprint Planning:** Selects *User Stories* and sets the *Sprint Goal*.
3. **Daily Scrum (15 min):** Daily developer sync to track progress and blockers.
4. **Sprint Review:** Live demo of the increment to gather stakeholder feedback.
5. **Sprint Retrospective:** Team review to improve workflows for the next Sprint.

---

# 5. Concrete Example: Sprint 1 on **Fashion & Apparel Store**

- **Sprint Goal:**
  Enable shoppers to browse the clothing catalog and view full item details.
- **Delivered Increment:**
  - Apparel catalog showing clothing items, designer, and season/style.
  - Full clothing item detail view.
- **Definition of Done (DoD):**
  - Eloquent models (`Designer`, `ClothingItem`, `SeasonStyle`) + Seeders working.
  - Responsive layout (Tailwind CSS + Preline UI).
  - Automated PHPUnit / Pest tests passing.

---

# Conclusion

- Scrum replaces the tunnel effect with **incremental value delivery**.
- Every Sprint produces a **working, tested, and demonstrable increment**.
- On **Fashion & Apparel Store**, Scrum secures both web and mobile development step by step.