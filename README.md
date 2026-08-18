# IMM-2026-001 — eTMF Simulation Project

A fictional, portfolio-focused Electronic Trial Master File (eTMF) project designed to demonstrate clinical trial document management, metadata governance, controlled filing, document lifecycle, quality control, approval, effectiveness, and inspection readiness.

> **Important:** IMM-2026-001 is entirely fictional. This repository does not contain records from a real clinical trial and is not connected to a production Veeva Vault environment.

---

## Project Overview

| Attribute | Value |
|---|---|
| Study ID | IMM-2026-001 |
| Sponsor | Fictional Pharma Ltd. |
| Therapeutic Area | Immunology / Allergy |
| Indication | Moderate-to-Severe Atopic Dermatitis |
| Investigational Product | IMM-101 |
| Phase | II |
| Design | Randomized, Double-Blind, Placebo-Controlled |

---

## eTMF Structure

The project follows an 11-zone eTMF structure:

1. Trial Management
2. Central Trial Documents
3. Regulatory
4. IRB/IEC and Other Approvals
5. Site Management
6. Investigational Product and Trial Supplies
7. Safety Reporting
8. Centralized and Local Testing
9. Third Parties
10. Data Management
11. Statistics

A dedicated `00_eTMF_Master_Register` area provides centralized document tracking and metadata control.

The `Configuration` area contains documents describing the simulated data model and document lifecycle.

---

## Repository Contents

The current repository contains:

- 96 controlled clinical-trial document files
- 1 eTMF Master Register
- 2 eTMF configuration specifications
- 3 portfolio documentation files
- README and repository configuration

The controlled documents are organized according to their functional TMF zone and artifact classification.

---

## Document Lifecycle

The simulated document lifecycle is:

```text
Created
   ↓
Metadata Review
   ↓
QC Review
   ↓
QC Passed
   ↓
Approval
   ↓
Approved
   ↓
Effective
   ↓
Filed
   ↓
Inspection Ready
