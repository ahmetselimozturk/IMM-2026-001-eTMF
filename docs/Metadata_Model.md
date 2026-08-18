# eTMF Metadata Model

## Purpose

The metadata model defines the minimum controlled attributes required to identify, classify, review, approve, file, and retrieve documents within the simulated eTMF.

## Core Metadata

| Field | Purpose |
|---|---|
| Study ID | Identifies the clinical trial |
| Document ID | Unique document identifier |
| Document Title | Controlled document name |
| TMF Zone | Functional filing area |
| Artifact Classification | Defines document type and classification |
| Version | Controlled document version |
| Document Status | Current lifecycle state |
| QC Status | Quality review result |
| Approval Status | Approval workflow result |
| Effective Date | Date document becomes effective |
| Filing Date | Date document is filed |
| Document Owner | Responsible function/person |
| Confidentiality | Access classification |
| Filing Location | Controlled repository location |

## Metadata Governance Principles

- Each document should have a unique identifier.
- Metadata should be complete before final filing.
- Artifact classification should match the document's intended purpose.
- Version information must be controlled.
- Lifecycle status must reflect the document's current state.
- Filing location must correspond to the approved TMF structure.
- Metadata changes should be traceable.

## Example

```text
Document ID: IMM-2026-001-DOC-001
Title: TMF Plan
Zone: 01 - Trial Management
Artifact Classification: 01.01.01 - TMF Plan
Version: 1.0
Status: Effective
QC Status: Passed
Approval Status: Approved
Confidentiality: Internal
