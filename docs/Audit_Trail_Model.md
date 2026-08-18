# eTMF Audit Trail Model

## Purpose

The audit trail model demonstrates how document-related activities can be recorded to support traceability, accountability, and inspection readiness.

## Audit Events

Typical events include:

- Document Created
- Metadata Updated
- QC Started
- QC Passed
- QC Failed
- Approval Requested
- Document Approved
- Document Rejected
- Document Became Effective
- Document Filed
- Document Superseded
- Filing Location Updated

## Audit Trail Fields

| Field | Description |
|---|---|
| Audit Event ID | Unique event identifier |
| Document ID | Associated document |
| Event Type | Type of activity |
| Event Date/Time | Time of activity |
| Performed By | User or role performing the action |
| Previous Value | Previous metadata/state |
| New Value | Updated metadata/state |
| Reason | Reason for the change |
| Result | Outcome of the activity |

## Example

```text
Audit Event ID: AUD-0001
Document ID: IMM-2026-001-DOC-001
Event Type: QC Passed
Performed By: TMF Quality Reviewer
Previous Value: QC Pending
New Value: QC Passed
Reason: Document passed metadata and content QC
Result: PASS
