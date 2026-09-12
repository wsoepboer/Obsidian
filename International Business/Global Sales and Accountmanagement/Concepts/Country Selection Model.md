---
tags: [course/global-sales-accountmanagement, type/concept]
aliases: [Country selection model, Country screening funnel, Market screening funnel, Country screening, Landenselectiemodel, Pre-selection and fine selection, Weighted country scoring]
---

# Country Selection Model

The theory behind *which* countries: a **funnel** that reduces every country on earth to one or a few, in stages, where each stage costs more per country and uses better data than the one before it. The logic is economic — you cannot afford field research on 195 countries, so cheap secondary data throws most of them away first, and expensive primary research runs only on the survivors.

> [!info] Where this comes from
> Standard international-business and export-planning theory — the screening funnel (Cavusgil 1985; Root 1994), the country-portfolio matrix (Harrell & Kiefer 1981), and distance (Ghemawat 2001 → [[CAGE Distance Framework]]; Johanson & Vahlne 1977 → [[Uppsala Model]]). It is **not** taken from a published lecture, because this unit publishes none → [[Sales Frameworks Index]]. Check it against the decks when they land and defer to the lecturer's version if it differs.

## The funnel

| Stage | Question | Data | Countries out |
|---|---|---|---|
| **1 · Pre-selection** | Is this country even possible? | Knock-out criteria, macro secondary data | ~195 → 15–25 |
| **2 · Coarse screening** | Is there demand for *this product*? | Industry and trade statistics | → 5–8 |
| **3 · Fine selection** | Can *we* serve it profitably? | Channel, legal, logistics, cost data | → 2–3 |
| **4 · Final selection** | Which one, and what will it earn? | Primary research: visits, fairs, interviews | → 1 (+ ranked runners-up) |

**Stage 1 — knock-out criteria.** Pass/fail conditions, not scores: sanctions or export controls, no legal route to certification, war or acute instability, a market below minimum viable size, prohibitive tariffs or import bans, a currency you cannot get paid in. One failure removes the country; no strength compensates.

**Stage 2 — market potential for the product category.** Country GDP is not demand. What matters is category-level: imports under the relevant HS code, installed base, construction or industrial output, per-capita consumption, growth rate, competitive intensity, and who already holds the channel.

**Stage 3 — company fit and entry conditions.** Is there a route to the buyer? What does certification cost and how long does it take? What is the landed cost and lead time → [[Cross-Border Logistics]], [[Transportation Modes]], [[Lead Time]]? What margin survives tariffs → [[Trade Barriers and Tariffs]]? How far is the country culturally and administratively → [[CAGE Distance Framework]]? What is the payment and legal exposure → [[Market Entry Risk]]?

**Stage 4 — the decision.** Primary evidence, a sales forecast, a payback estimate — and a written record of **why each rejected country was rejected**. That record is the part most people skip.

> [!important] The funnel only runs one way
> Reversing it — choosing the country first, then assembling criteria that justify it — is the standard failure mode, and it shows in the write-up: the criteria look tailored, and the rejected countries fail on grounds never applied to the winner.

## The scoring matrix

Stages 2 and 3 are operationalised as a **weighted factor score** — criteria on the rows, countries in the columns, weights summing to 1, a bounded score (1–5) per cell, and a weighted total.

| Criterion | Weight | Country A | Country B |
|---|---|---|---|
| Category market size | 0.25 | 4 → 1.00 | 3 → 0.75 |
| Growth rate | 0.15 | 3 → 0.45 | 5 → 0.75 |
| Competitive intensity (reversed) | 0.15 | 2 → 0.30 | 4 → 0.60 |
| Certification cost and lead time | 0.20 | 5 → 1.00 | 2 → 0.40 |
| Landed cost and logistics | 0.15 | 4 → 0.60 | 3 → 0.45 |
| Cultural and administrative distance | 0.10 | 4 → 0.40 | 3 → 0.30 |
| **Weighted total** | **1.00** | **3.75** | **3.25** |

Four rules separate a defensible matrix from decoration:

- **Weights come from the company's objectives**, and you say where from. Equal weights are a confession that you never decided what matters.
- **Knock-out criteria stay out of the scoring.** They are pass/fail; scoring them lets a high total buy off an impossibility.
- **Every score cites a source** → [[Traceable Sources]]. An uncited 4 is an opinion with a number on it.
- **Test the ranking.** If shifting one weight by 0.05 flips the winner, the countries are effectively tied — say so rather than pretending the decimal decided.

## The two axes underneath

Strip the criteria back and every country-selection model has the same two dimensions.

**Attractiveness** — how much there is to win: size, growth, price level, margin.
**Accessibility and risk** — how hard it is to win: barriers, distance, certification, logistics, political and payment risk.

Plotted against each other — Harrell & Kiefer's country attractiveness / competitive strength portfolio — they give four positions:

| | Low risk / accessible | High risk / hard to access |
|---|---|---|
| **High attractiveness** | **Enter and invest** — commit, build presence | **Enter selectively** — low-commitment mode, staged |
| **Low attractiveness** | **Opportunistic** — serve reactively, no investment | **Avoid** — or monitor and revisit |

This is where selection hands over to [[Market Entry Strategy]], because the quadrant largely dictates the mode. Attractive-but-hard argues for a distributor or agent: low commitment, reversible. Attractive-and-accessible is what justifies a subsidiary.

## Distance: the normative and the descriptive

Screening models are **normative** — they say how the choice *should* be made. The [[Uppsala Model]] is **descriptive** — it observes that firms actually enter *psychically near* markets first, because perceived uncertainty falls as knowledge accumulates, and move outward only with experience. [[CAGE Distance Framework]] makes that intuition measurable across four distances.

Both belong in the analysis, doing different jobs. Use distance as a **criterion** in the matrix; use Uppsala to explain why the existing market footprint looks the way it does, and why a large psychic jump argues for a lower-commitment entry mode → [[Stages of Internationalisation]].

## Where the numbers come from

Traceable, free, and enough to run stages 1–3 without primary research:

- **Trade and category demand** — ITC Trade Map, UN Comtrade, World Bank WITS (imports by HS code are revealed demand)
- **Macro** — World Bank WDI, IMF World Economic Outlook, OECD, Eurostat, CBS
- **Tariffs, standards, certification** — EU Access2Markets, national standards bodies
- **Business environment and governance** — World Bank B-READY (successor to *Doing Business*, discontinued 2021), Worldwide Governance Indicators, Transparency International CPI → [[Corruption Risk]]
- **Composite indices** — globalEDGE **Market Potential Index** (Michigan State), ranking emerging markets on eight dimensions: market size, growth rate, intensity, consumption capacity, commercial infrastructure, economic freedom, market receptivity, country risk. Useful as a cross-check and as a precedent for weighting — but it is *general*, not category-specific, so it never replaces stage 2.
- **Culture** — the Hofstede country comparison tool → [[Hofstede's Cultural Dimensions]]
- **Sector intelligence** — RVO country reports, embassy and trade-council studies, industry associations

## Applying it when the countries are assigned

Here the countries are given, not chosen → [[Country Selection]]. That does not retire the model; it changes its job from **choosing** to **positioning and defending**:

1. Run the **stage 2–3 criteria** on each assigned country to show what makes it attractive and where it is hard. That output *is* the economic perspective of [[The Six Perspectives]], evidenced.
2. **Score the assigned countries against each other.** The rubric wants an entry recommendation for *a selected country* — the matrix is how you pick which of yours to build it around, and it makes the choice arguable instead of arbitrary.
3. Use the **knock-out list as a risk list.** Any criterion a country nearly failed is a real market-entry risk, already identified → [[Market Entry Risk]].
4. Use the **quadrant** to justify the entry mode *and to rule the others out* — the sharpest requirement in the rubric → [[Market Entry Strategy]].

**Connected:** [[Country Selection]] · [[CAGE Distance Framework]] · [[Export Strategy]] · [[Market Entry Strategy]] · [[The Six Perspectives]] · [[Market Entry Risk]] · [[Traceable Sources]] · [[Uppsala Model]] · [[Stages of Internationalisation]] · [[Country Analysis]]

---
**Assignment:** [[The Altrex Assignment]] · [[00 Global Sales and Accountmanagement MOC|↩ Course MOC]]
