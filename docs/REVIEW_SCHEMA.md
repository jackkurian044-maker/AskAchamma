# SME review record schema

Use one record per proposed terminology correction.

| Field | Purpose |
|---|---|
| review_id | Stable unique review identifier |
| tool_area | Feature or tool category |
| current_name | Name currently displayed |
| current_definition | Current intended meaning |
| proposed_name | SME recommendation |
| proposed_definition | Corrected definition |
| rationale | Domain evidence and reason |
| example_phrase | Example user utterance or scenario |
| reviewer_name | Reviewer identity (use approved identity model) |
| reviewer_expertise | Relevant subject expertise |
| confidence | Low / Medium / High |
| status | Pending / In Review / Accepted / Rejected / Applied |
| owner_decision | Approval or rejection rationale |
| reviewed_at | Timestamp of SME review |
| applied_version | Product version containing an approved change |
| verification_notes | Test evidence and follow-up notes |

## Governance

- Store reviews in a shared database once authentication and access rules are configured.
- Record the reviewer and timestamps; do not allow a reviewer to mark their own proposal as applied unless explicitly authorized.
- Keep proposed terminology separate from live production terminology.
- Require an authorized product owner to approve changes.
- Keep an audit trail for accepted, rejected, and applied decisions.
