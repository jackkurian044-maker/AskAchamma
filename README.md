# Ask Achamma — SME Review Portal

A lightweight review workspace for subject-matter experts to validate Ask Achamma's core tool names and propose corrections before changes are applied to the product.

## Review workflow

1. List a current tool name and its meaning/purpose.
2. SME suggests the corrected name, wording, or taxonomy.
3. Record rationale, confidence, and any examples.
4. Mark the item as Pending, In review, Accepted, Rejected, or Applied.
5. Product owner reviews accepted changes before updating the live tool.

## Important implementation note

This repository starts as a static review-portal skeleton. It does not yet persist submissions, authenticate reviewers, or publish edits to Ask Achamma. Before using this for real SME submissions, connect a durable data store and reviewer authentication; require owner approval before applying changes.

## Local preview

Open `index.html` in a browser, or deploy the repository as a static site.

## Suggested review fields

- Tool / feature area
- Current core name
- Current meaning / job to be done
- Proposed corrected name
- Proposed description
- Reason for change
- Example phrase / example user request
- SME name and expertise
- Confidence (Low / Medium / High)
- Status
- Product owner decision and date
