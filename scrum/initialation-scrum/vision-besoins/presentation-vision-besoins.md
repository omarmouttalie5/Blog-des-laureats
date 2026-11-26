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

# Product Vision & User Stories
## Applied to: **Fashion & Apparel Store**

Scrum Initiation Workshop

---

# 1. Core Agile Requirements Concepts

- **Product Vision:** Clear north star defining target users and value.
- **Personas:** Realistic user profiles capturing goals and pain points.
- **User Stories:** *As a [role], I want [action], so that [benefit].*
- **Acceptance Criteria:** Concrete, testable rules validating a story.
- **MVP:** Essential v1 scope delivering immediate value without bloat.

---

# 2. Product Vision — **Fashion & Apparel Store**

- **Target Users:** Fashion shoppers & independent designers.
- **Core Value:** A fast, curated web & mobile catalog connecting shoppers with seasonal designer collections.
- **Differentiator:** Clean style/season discovery without the clutter of mass-market marketplaces.

---

# 3. Target Personas

| Persona | Role | Goals | Pain Points |
| :--- | :--- | :--- | :--- |
| **Lina (24)** | Shopper | Browse seasonal outfits & designer specs on mobile | Cluttered catalogs, hard to filter by style |
| **Karim (31)** | Designer | Publish new pieces linked to a `SeasonStyle` | Complex, slow admin interfaces |

---

# 4. Key User Stories & Acceptance Criteria

- **US-01 (Browse):** *As a shopper, I want to browse clothing items with designer and style tags, so that I can discover apparel easily.*
  - **AC:** Responsive grid with `ClothingItem`, `Designer`, `SeasonStyle`; clean empty state.
- **US-02 (Details):** *As a shopper, I want to view full item details, so that I can check specs and designer info.*
  - **AC:** Dedicated detail view; 404 page on invalid ID.
- **US-03 (Filter):** *As a shopper, I want to filter by `SeasonStyle`, so that I find relevant outfits fast.*
  - **AC:** Dynamic category filtering + instant reset option.
- **US-04 (Manage):** *As a designer, I want to publish a new `ClothingItem`, so that shoppers see my latest collection.*
  - **AC:** Validated form saving to MySQL + clear error messages.

---

# 5. MVP Scope Boundary

| In-Scope (MVP v1) | Out-of-Scope (Future Releases) |
| :--- | :--- |
| Public catalog & item detail pages | Payment gateway & shopping cart |
| Filtering by `SeasonStyle` | Customer reviews & wishlists |
| Designer item creation & management | AI outfit recommendations |

---

# Conclusion

- A shared **Product Vision** aligns technical decisions with user value.
- **Personas** and **User Stories** keep features focused on real needs.
- Clear **Acceptance Criteria** and **MVP boundaries** secure Sprint execution on **Fashion & Apparel Store**.