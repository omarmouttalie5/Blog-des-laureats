# Workshop: Understanding the Agile Approach and the Scrum Framework

**Reference Project:** Blog laureats  
**Objective:** Understand the shift from Waterfall to Agile, master the core pillars, roles, and events of Scrum, and apply them to managing **Blog laureats**.

---

## 1. The Shift: Waterfall (V-Model) vs. Agile Approach

### Limitations of the Waterfall Model
In a traditional sequential approach (Waterfall / V-Model), all phases (analysis, design, development, testing, deployment) follow a strict linear order:
- **Tunnel effect:** End users (students and laureats) do not see any working software until the entire project is finished.
- **Rigidity to change:** Modifying a requirement mid-project (e.g., adding category filtering or adjusting mobile layouts) is expensive and delays the whole delivery.
- **Late risk detection:** Usability issues or technical bugs are only discovered at the very end of the cycle.

### The Agile Alternative
The Agile approach breaks the project down into short, iterative cycles called **Sprints**:
- Regular delivery of working software providing immediate business value.
- Continuous user feedback allowing the product to adapt after every iteration.
- Early risk reduction through automated testing integrated from the very first sprint.

---

## 2. The 4 Values of the Agile Manifesto

1. **Individuals and interactions** over processes and tools.
2. **Working software** over comprehensive documentation.
3. **Customer collaboration** over contract negotiation.
4. **Responding to change** over following a plan.

---

## 3. The 3 Empirical Pillars of Scrum

Scrum is founded on empiricism—making decisions based on observation and experience:
- **Transparency:** All team members and stakeholders share a clear, common view of progress, the *Product Backlog*, and the *Definition of Done*.
- **Inspection:** Artifacts and progress toward the Sprint Goal are inspected frequently to detect any deviations early.
- **Adaptation:** Whenever a deviation or new user need arises, the process or product is adjusted immediately.

---

## 4. The 3 Scrum Roles (Applied to **Blog laureats**)

| Role | General Responsibilities | Application on **Blog laureats** |
| :--- | :--- | :--- |
| **Product Owner (PO)** | Maximizes product value, manages and prioritizes the *Product Backlog*, writes *User Stories*. | Decides that public article reading takes priority over advanced admin moderation; defines acceptance criteria. |
| **Scrum Master (SM)** | Ensures the Scrum framework is understood and enacted, facilitates events, and removes blockers (*impediments*). | Keeps meetings time-boxed and helps resolve technical roadblocks (Laravel/NativePHP environment setup). |
| **Developers** | Design, build, test, and deliver a usable increment at the end of every Sprint. | Build the Eloquent models (`Laureat`, `Article`, `Categorie`), Blade/Tailwind/Preline UI views, and PHPUnit/Pest tests. |

---

## 5. The 5 Scrum Events (Rituals)

1. **The Sprint (Container):** A fixed-length iteration (1 to 4 weeks) during which a usable product increment is created.
2. **Sprint Planning:** Kickoff meeting to define the *Sprint Goal* and select the *Product Backlog* items to deliver during the Sprint.
3. **Daily Scrum:** A 15-minute daily stand-up for Developers to synchronize progress and identify any impediments.
4. **Sprint Review:** End-of-sprint demonstration of the working increment to stakeholders to gather feedback and adapt the backlog.
5. **Sprint Retrospective:** Internal team reflection on processes, tools, and collaboration to improve effectiveness in the next Sprint.

---

## 6. Increment and Definition of Done (DoD)

- **Increment:** A concrete, tested, and usable version of the product delivered at the end of a Sprint, building upon all previous increments.
- **Definition of Done (DoD):** A formal checklist of quality criteria required before any backlog item can be considered complete.

### Concrete Example: Sprint 1 on **Blog laureats**
- **Sprint Goal:** Allow students to browse published articles and read the full details of an article.
- **Delivered Increment:** A home page listing published articles (title, category, laureat author) and a dedicated article detail page.
- **Definition of Done (DoD) Criteria:**
  - MySQL database migrated and populated with seeders (`Laureat`, `Article`, `Categorie`).
  - Clean MVC and Service layer architecture implemented in Laravel.
  - Responsive UI verified on desktop and mobile (Tailwind CSS + Preline UI).
  - PHPUnit / Pest feature tests written and passing.