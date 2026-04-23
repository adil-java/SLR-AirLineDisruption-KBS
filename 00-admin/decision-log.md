# Decision Log

Append-only record of all methodological decisions made during the SLR.

---

## 2026-02-01 — Topic scope definition

**Decision:** Scope defined as the intersection of Knowledge-Based Systems,
decision support, optimisation, and intelligent recovery planning within the
airline and aviation domain. Focus on systems handling Irregular Operations
(IROPS) including aircraft rerouting/retiming, crew rescheduling, passenger
recovery, and integrated recovery.

**Rationale:** The CT-359 CEP assignment requires a domain where knowledge
representation and expert systems are both applicable and documented in
literature. Airline disruption management provides rich published evidence
and a clear gap for KBS approaches.

---

## 2026-02-18 — Date range

**Decision:** Include papers published 2001–2025.

**Rationale:** The domain predates 2001 but operational academic literature
with methodological detail begins in the early 2000s. Extending to 2001
ensures foundational optimisation work is captured alongside modern ML and
KBS approaches.

---

## 2026-02-20 — Language restriction

**Decision:** Include only English-language papers.

**Rationale:** Team has no non-English reading capability; risk of
misinterpretation outweighs coverage benefit. This limitation is acknowledged
in the SLR synthesis report.

---

## 2026-02-25 — Search tool selection

**Decision:** Use Harzing's Publish or Perish (PoP) to query Google Scholar
with individual keyword strings, export as RIS, and import into Rayyan for
deduplication and screening.

**Rationale:** Institutional access to Scopus and Web of Science is not
available. Google Scholar via PoP provides the broadest coverage accessible
without subscription, and Rayyan automates deduplication and dual-reviewer
blinding.

---

## 2026-03-05 — Exclusion of maritime/road logistics papers

**Decision:** Exclude papers focused exclusively on maritime routing, road
logistics, or rail scheduling with no aviation relevance.

**Rationale:** While methodological overlap exists (e.g., vehicle rescheduling),
the domain-specific constraints of aviation (crew duty time regulations, ACARS
data, slot coordination) differ fundamentally and such papers would not inform
the proposed KBS design.

---

## 2026-04-01 — Treatment of borderline "decision support" papers

**Decision:** Include papers describing decision support systems (DSS) for
aviation even when the KBS component is implicit (e.g., embedded constraint
rules in an optimisation pipeline), provided the paper presents architectural
or methodological detail relevant to at least one RQ.

**Rationale:** Pure KBS papers are a minority in this domain; excluding all
DSS work would leave the literature review unable to address RQ2 (architectural
patterns) adequately. Inclusion with appropriate labelling in the extraction
form is more informative.

---

## 2026-04-10 — Final included study count confirmed

**Decision:** Final included set: 142 studies after full-text assessment.

**Rationale:** PRISMA flow accounts for 658 imported records → 214 duplicates
removed → 444 screened → 302 excluded → 142 full-text assessed → 82 excluded
at full-text → 60 carried forward (note: the report uses all 142 that passed
full-text assessment for extraction, as all provided methodological detail
for at least one RQ).
