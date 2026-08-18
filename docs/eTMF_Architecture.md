# eTMF Architecture

## Purpose

The IMM-2026-001 eTMF simulation models a structured Electronic Trial Master File environment for a fictional Phase II clinical trial.

The objective is to demonstrate how clinical trial documentation can be organized, classified, controlled, reviewed, and maintained throughout the study lifecycle.

## High-Level Structure

The repository is organized into 11 functional TMF zones:

| Zone | Functional Area |
|---|---|
| 01 | Trial Management |
| 02 | Central Trial Documents |
| 03 | Regulatory |
| 04 | IRB/IEC and Other Approvals |
| 05 | Site Management |
| 06 | Investigational Product and Trial Supplies |
| 07 | Safety Reporting |
| 08 | Centralized and Local Testing |
| 09 | Third Parties |
| 10 | Data Management |
| 11 | Statistics |

A dedicated `00_eTMF_Master_Register` area provides centralized document tracking and metadata control.

The `Configuration` area contains documents describing the simulated data model and document lifecycle.

## Document Control Model

Each controlled document is associated with key metadata such as:

- Study ID
- Document ID
- Document title
- TMF zone
- Artifact classification
- Version
- Document status
- QC status
- Approval status
- Effective date
- Filing date
- Owner
- Confidentiality classification

## Controlled Filing

Documents are filed according to their functional TMF zone and artifact classification.

Example:

```text
01_Trial_Management
└── 01.01_Trial_Planning
    └── 01.01.01_TMF_Plan
        └── IMM-2026-001_TMF_Plan_v1.0.docx
