# SLR Protocol v1.0

**Title:** A Knowledge-Based Expert System for Airline Disruption Management
and Recovery Planning — Systematic Literature Review Protocol

**Version:** 1.0
**Date:** 2026-03-18
**Reporting guideline:** PRISMA 2020 (Page et al., BMJ 2021;372:n71)

## 1. Administrative Information

### 1.1 Title
See above.

### 1.2 Authors
- Muhammad Yaafay (SE-23023), Software Engineering, Section A, Batch 2023
- Adil Javed (SE-23025), Software Engineering, Section A, Batch 2023

### 1.3 Amendments
None as of v1.0. All future amendments will be documented in
00-admin/decision-log.md with date, rationale, and impact.

## 2. Introduction

### 2.1 Rationale

Airline operations are vulnerable to disruptions including adverse weather,
mechanical failures, crew unavailability, air traffic control restrictions,
and cascading delays. When disruptions occur, airlines must rapidly formulate
recovery plans that minimise passenger impact, optimise resource utilisation,
and restore normal schedule operation. This process — Airline Disruption
Management — requires coordinating interdependent resources (aircraft, crews,
passengers, and airport slots) under tight time constraints and operational
uncertainty.

Existing disruption management systems are predominantly optimisation-centric
and lack explainability, integration, and passenger-centricity. Knowledge-Based
Systems offer a complementary approach: encoding domain expertise in auditable,
maintainable rule bases that can support transparent, context-aware recovery
recommendations. Despite this potential, KBS approaches remain underrepresented
in the literature. This SLR aims to synthesise the current state of the field,
identify best practices, and map findings onto the proposed system architecture.

### 2.2 Objectives

1. Identify algorithmic techniques and knowledge representation paradigms used
   for airline disruption management (RQ1).
2. Catalogue architectural patterns and system components in existing DSS/KBS
   for airline operations (RQ2).
3. Understand how structured knowledge is integrated with computational engines
   for real-time recovery support (RQ3).
4. Identify primary limitations and research gaps (RQ4).

## 3. Methods

### 3.1 Eligibility Criteria

**Inclusion:**
- Peer-reviewed papers and conference proceedings published 2001–2025
- Studies focusing on airline disruption management, IROPS, recovery planning,
  or closely related aviation decision support systems
- Studies presenting or evaluating systems, algorithms, or frameworks with
  methodological detail
- Papers describing system architecture, knowledge representation, or
  computational approach clearly

**Exclusion:**
- Non-English papers
- Papers lacking technical or methodological detail
- Pure opinion, editorial, or perspective articles without empirical content
- Studies focused exclusively on unrelated transportation domains (maritime
  routing, road logistics) with no aviation relevance
- Duplicate or redundant studies

### 3.2 Information Sources

Primary database: Google Scholar, accessed via Harzing's Publish or Perish (PoP).
Ten targeted keyword search strings were executed individually.
All retrieved RIS files were imported into Rayyan for deduplication and screening.

### 3.3 Search Strategy

Ten search strings were executed in PoP:
1. expert system airline disruption recovery
2. knowledge-based system airline recovery
3. airline disruption management optimization
4. airline irregular operations recovery system
5. decision support system aviation disruption
6. aircraft crew rescheduling recovery
7. flight delay prediction machine learning
8. passenger recovery airline disruption
9. aviation scheduling disruption management
10. IROPS airline recovery system

See 02-searches/ for individual search string files and search-log.xlsx for
record counts per string.

### 3.4 Study Records

**Data management:** RIS files exported from PoP and imported into Rayyan.
Rayyan performed automatic deduplication. Two reviewers independently screened
all records at title/abstract stage with reviewer blinding enabled in Rayyan.

**Selection process:** Dual independent screening at title/abstract and
full-text stages. Disagreements resolved through discussion; escalated to
supervisor if unresolved.

### 3.5 Data Items

The extraction form (05-data-extraction/extraction-form-template.xlsx) captures:
bibliographic data, technique group, specific method, knowledge representation
type, architecture pattern, system components, integration approach, limitations,
and gap mapping per RQ.

### 3.6 Data Synthesis

Narrative synthesis organised by research question. No meta-analysis is planned
due to heterogeneity of study types, methods, and evaluation contexts. Synthesis
outputs include technique distribution tables, architectural pattern synthesis,
knowledge representation mapping, and a research gap synthesis.

## 4. Reporting

The completed SLR is reported in CEP Progress Report 2 (April 2026) following
PRISMA 2020 with a PRISMA flow diagram included.
