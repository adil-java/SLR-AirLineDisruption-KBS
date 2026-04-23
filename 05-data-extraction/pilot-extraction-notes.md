# Pilot Extraction Notes

## Pilot conducted: 2026-04-10

**Studies piloted:** S001, S003, S006, S013, S015
(selected to span technique groups: KBS, optimisation, ontology, integrated, DSS)

**Reviewers:** SE-23023 (R1) and SE-23025 (R2) independently extracted each
study, then compared results in a joint session.

## Issues identified during pilot

### Issue 1: Technique group ambiguity for hybrid systems
**Problem:** Several papers combine optimisation with rule-based logic (e.g.,
S015 uses ILP warm-started by rules). Single "Technique Group" column was
insufficient.
**Resolution:** Allow combined entries in Technique Group (e.g., "Classical
Optimisation + Rule-Based") with detail in Specific Methods column.

### Issue 2: Capturing deployment stage
**Problem:** R1 and R2 used inconsistent terminology (e.g., "tested",
"validated", "deployed").
**Resolution:** Standardised to four categories: Research, Prototype,
Pilot deployment, Operational. Applied retroactively to all piloted studies.

### Issue 3: Limitations column scope
**Problem:** R1 captured limitations from abstract only; R2 used full
discussion section. Results diverged significantly.
**Resolution:** Always use full paper discussion/conclusion section for
limitations. At least one verbatim quote required in Key Quotes column.

### Issue 4: "Human-in-the-loop" definition
**Problem:** Some papers describe optional human override; others require
human approval for all recommendations. R1 and R2 tagged both as "Yes".
**Resolution:** "Yes" = human must approve or can modify any recommendation.
"Partial" = automated execution with human monitoring only. "No" = fully
automated with no human step.

### Issue 5: Real-time capability claims
**Problem:** Papers vary in what they call "real-time" — some mean
sub-second, others mean within 15 minutes.
**Resolution:** Accept paper's own claim but note time window in RQ3 notes
column if stated explicitly.

## Form changes after pilot

Extraction form updated 2026-04-11 to reflect resolutions above. All five
piloted studies re-extracted using updated form.

## Time per study (pilot)

- S001: 35 minutes
- S003: 28 minutes
- S006: 45 minutes (complex ontology paper)
- S013: 40 minutes (large integrated ILP, many constraints to capture)
- S015: 30 minutes

**Average:** 36 minutes per study.
Estimated total for 142 studies: ~85 hours (split between R1 and R2).
