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
## Applied to: **Blog laureats**

Scrum Initiation Workshop 

---

# 1. Waterfall (V-Model) vs. Agile

| Waterfall / V-Model | Agile Approach (Iterative) |
| :--- | :--- |
| Single delivery at the end of the project | Frequent deliveries via **Sprints** |
| Tunnel effect (no early user feedback) | Continuous user feedback |
| Rigid and costly to change | Rapid adaptation to evolving needs |
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

# 3. The 3 Scrum Roles on **Blog laureats**

- **Product Owner (PO)**
  - Defines product vision and prioritizes the *Product Backlog*.
  - *Example: Prioritizing article reading before admin moderation.*
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

# 5. Concrete Example: Sprint 1 on **Blog laureats**

- **Sprint Goal:**
  Enable students to browse the list of published articles and read a full article.
- **Delivered Increment:**
  - Article feed showing title, category, and laureat author.
  - Full article detail view.
- **Definition of Done (DoD):**
  - Eloquent models (`Laureat`, `Article`, `Categorie`) + Seeders working.
  - Responsive layout (Tailwind CSS + Preline UI).
  - Automated PHPUnit / Pest tests passing.

---

# Conclusion

- Scrum replaces the tunnel effect with **incremental value delivery**.
- Every Sprint produces a **working, tested, and demonstrable increment**.
- On **Blog laureats**, Scrum secures both web and mobile development step by step.