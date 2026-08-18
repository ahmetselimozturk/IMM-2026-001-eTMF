# eTMF Filing Log Model

## Purpose

The Filing Log provides a controlled record of documents filed within the simulated eTMF.

## Filing Information

| Field | Description |
|---|---|
| Filing ID | Unique filing record identifier |
| Document ID | Associated document |
| Document Title | Controlled document title |
| TMF Zone | Functional filing zone |
| Artifact Classification | Document classification |
| Version | Controlled document version |
| Filing Location | Final repository location |
| Filing Date | Date of filing |
| Filed By | User or role performing filing |
| Filing Status | Filing result |
| QC Status | QC result at filing |
| Approval Status | Approval result |

## Filing Controls

Before filing, the following should be confirmed:

- Document belongs to the correct study
- Document classification is appropriate
- Version is controlled
- Required QC is complete
- Required approval is complete
- Metadata is complete
- Filing location is correct

## Example

```text
Filing ID: FIL-0001
Document ID: IMM-2026-001-DOC-001
TMF Zone: 01 - Trial Management
Artifact Classification: 01.01.01 - TMF Plan
Version: 1.0
Filing Location: 01_Trial_Management/01.01_Trial_Planning/01.01.01_TMF_Plan
Filing Status: Filed
QC Status: Passed
Approval Status: Approved
