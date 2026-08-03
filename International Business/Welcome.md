---
tags: [type/readme]
aliases: [README, Start Here, Home]
---

# 👋 Welcome — Study Vault

Your Obsidian study vault. It holds **multiple courses**, each a self-contained folder with its own map of content (MOC), atomic concept notes, and reference sheets. Pick a course below, or read *How this vault works* to learn the system.

> [!tip] New here? Open a course's **MOC** and study from its links. Turn on **Graph view** (colour-coded by course) to see how everything connects.

---

## 📚 Courses in this vault

### 🎓 Fundamentals of Business Economics  ·  *built*
Textbook: *Accounting and Finance for Non-Specialists* (Atrill & McLaney).
→ **[[00 Fundamentals of Business Economics MOC|Open the course]]**
Financial statements, company accounts, ratios, costing, budgeting, investment appraisal, financing, working capital. *(`$= dv.pages('"Fundamentals of Business Economics/Chapters"').length` chapters · `$= dv.pages('"Fundamentals of Business Economics/Concepts"').length` concepts)*

### 📘 Organisational Strategy and HR  ·  *built (lectures) · handbook pending*
Built from the lecture decks; the *Organisation and Management* handbook joins this course once clean text is available.
→ **[[00 Organisational Strategy and HR MOC|Open the course]]**
Management history, external environment, strategy, internationalisation, future of work, HRM, culture & ethics. *(`$= dv.pages('"Organisational Strategy and HR/Topics"').length` topics · `$= dv.pages('"Organisational Strategy and HR/Concepts"').length` concepts)*

---

## 🧭 How this vault works

Built on the standard **Obsidian-for-students** method: a map of content, chapter/topic notes, and atomic linked notes.

| Note type | What it is | Where |
|---|---|---|
| **MOC** (map of content) | The hub for a course — links everything | Top of each course folder |
| **Chapter / Topic** | The narrative: overview, learning outcomes, a **self-test**, and assignment | `Chapters/` · `Topics/` |
| **Concept** | One idea or framework each, heavily cross-linked — the graph's value | `Concepts/` |
| **Reference** | Glossaries, a formulas cheat-sheet, a frameworks index | `Reference/` |

**Folder layout**
```
(vault root)
├── Welcome.md                              ← you are here
├── Fundamentals of Business Economics/     (Chapters · Concepts · Reference)
└── Organisational Strategy and HR/         (Topics · Concepts · Reference)
```

**Tag scheme** — every note is tagged so you can filter by course and type:
- `course/…` — `course/business-economics` · `course/org-strategy-hr`
- `type/…` — `moc` · `chapter` · `topic` · `concept` · `reference`

---

## 🎯 Study one course at a time (focus mode)

- **Study from the MOC** — open a course's MOC and follow its links; you never see the other.
- **Filter the graph** — in Graph view's search box, type a course tag, e.g.
  `tag:#course/business-economics` — everything else greys out.
- **Colour-coded graph** — 🟢 Fundamentals of Business Economics · 🟠 Organisational Strategy and HR.
- **Scoped search** — add `path:"<course folder>"` or `tag:#course/…` to any search.
- **Workspaces** — save a layout per course (Command Palette → *Manage workspace layouts*) and switch in one click.
- **Local graph** — use a note's own local graph instead of the global one.

---

## 🔖 Quick links
- **Business Economics:** [[00 Fundamentals of Business Economics MOC]] · [[Glossary]] · [[Formulas Cheat-Sheet]]
- **Organisational Strategy and HR:** [[00 Organisational Strategy and HR MOC]] · [[Organisational Strategy and HR Glossary]] · [[Frameworks & Models Index]]

---

## ➕ Adding new material
Give clean text (Markdown, PDF, EPUB, DOCX, or copy-pasted chapter text — not OCR'd screenshots) and it gets built into the matching course: chapter/topic notes with self-tests, atomic concept notes for every key term or framework, a glossary, and links from the MOC. Concepts that recur across courses are **reused**, not duplicated.

*Conventions: British spelling in note bodies; wikilinks by note name; one idea per concept note.*
