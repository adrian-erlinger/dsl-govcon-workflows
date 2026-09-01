---
name: rfp-compliance-matrix
description: Draft an RFP compliance matrix and proposal responsibility tracker from synthetic or approved organizational RFP sources, preserving source references, proposed ownership, review questions, and compliance boundaries.
---

# RFP Compliance Matrix

Use this skill when the user wants to run, rehearse, review, or adapt the RFP Compliance Matrix and Proposal Responsibility Tracker workflow in this repository.

## Purpose

Help a GovCon proposal team organize stated requirements, handoffs, deadlines, amendment impacts, Q&A issues, and review needs into structured draft artifacts.

The workflow can:

- extract distinct stated requirements into a matrix;
- identify source sections, attachments, amendments, and Q&A references;
- propose owner and consulted reviewer roles;
- surface proposal, contracts, pricing, security, technical, and operations questions;
- create a responsibility tracker for human coordination.

Qualified reviewers still determine meaning, completeness, responsiveness, and compliance. The workflow does not provide legal interpretation, automated compliance certification, or final proposal review.

## Required Repository Files

Before drafting, read:

- `AGENTS.md`
- `SAFETY-AND-BOUNDARIES.md`
- `workflows/rfp-compliance-matrix/README.md`
- `workflows/rfp-compliance-matrix/instructions.md`
- `workflows/rfp-compliance-matrix/data/source-packet-index.md`
- `workflows/rfp-compliance-matrix/prompt.md`

For first-time practice, use the approved synthetic source files listed in the source packet index and prompt. If the user explicitly identifies approved organizational source files, adapt the workflow to those files instead.

## Expected Outputs

When the user asks to run the workflow, create:

- `workflows/rfp-compliance-matrix/draft-compliance-matrix.csv`
- `workflows/rfp-compliance-matrix/draft-responsibility-tracker.csv`

Use the templates in:

- `workflows/rfp-compliance-matrix/templates/compliance-matrix.csv`
- `workflows/rfp-compliance-matrix/templates/responsibility-tracker.csv`

## Operating Rules

- Use only the source files the user has approved for the workflow.
- Do not use unauthorized company, client, proposal, procurement, pricing, confidential, controlled, or proprietary data.
- Extract distinct requirements into separate rows.
- Cite exact sections, attachments, amendment IDs, Q&A IDs, or source rows.
- Preserve unknown, amended, unanswered, partial, and conflicting information.
- Treat owner roles as proposed until a human confirms them.
- Route specialist questions without answering them.
- Do not interpret laws, clauses, security obligations, or pricing requirements.
- Do not claim that the draft identifies every requirement or certifies compliance.
- State that all outputs are draft internal workflow aids requiring qualified human review.

## Review Standard

After drafting, compare the outputs with:

- `workflows/rfp-compliance-matrix/expected-output-guide.md`

Pay special attention to whether the draft:

- separates combined instructions into usable rows;
- reflects amendment impacts without losing the original source trail;
- preserves unanswered Q&A as review items;
- avoids inventing internal due dates, owners, weights, standards, or pricing conclusions;
- routes contracts, legal, security, pricing, proposal, and subject-matter issues to appropriate reviewer roles.
