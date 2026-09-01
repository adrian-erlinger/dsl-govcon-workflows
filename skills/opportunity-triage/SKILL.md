---
name: opportunity-triage
description: Draft an Opportunity Triage intake worksheet and preliminary bid/no-bid brief from synthetic or approved organizational GovCon opportunity sources, preserving source traceability, uncertainty, and human decision boundaries.
---

# Opportunity Triage

Use this skill when the user wants to run, rehearse, review, or adapt the Opportunity Triage and Bid/No-Bid workflow in this repository.

## Purpose

Help a GovCon team turn scattered opportunity information into a structured first pass that is easier for humans to review.

The workflow can:

- organize opportunity information into an intake worksheet;
- compare the opportunity against a capability statement and other approved source files;
- assess fit factors with source-based reasoning;
- surface known, partially supported, unknown, weak, missing, and conflicting information;
- draft a preliminary bid/no-bid brief and reviewer questions.

The pursuit decision remains with the responsible team. Scores are discussion aids, not mathematical rules or final bid/no-bid decisions.

## Required Repository Files

Before drafting, read:

- `AGENTS.md`
- `SAFETY-AND-BOUNDARIES.md`
- `workflows/opportunity-triage/README.md`
- `workflows/opportunity-triage/instructions.md`
- `workflows/opportunity-triage/data/source-packet-index.md`
- `workflows/opportunity-triage/prompt.md`

For first-time practice, use the approved synthetic source files listed in the source packet index and prompt. If the user explicitly identifies approved organizational source files, adapt the workflow to those files instead.

## Expected Outputs

When the user asks to run the workflow, create:

- `workflows/opportunity-triage/draft-opportunity-intake.md`
- `workflows/opportunity-triage/draft-bid-no-bid-brief.md`

Use the templates in:

- `workflows/opportunity-triage/templates/opportunity-intake.md`
- `workflows/opportunity-triage/templates/bid-no-bid-brief.md`

## Operating Rules

- Use only the source files the user has approved for the workflow.
- Do not use unauthorized company, client, proposal, procurement, pricing, confidential, controlled, or proprietary data.
- Separate source facts from analysis.
- Cite source files, rows, fields, or sections for material findings.
- Preserve unknown and conflicting information instead of forcing a clean answer.
- Route unresolved issues to reviewer roles such as BD lead, capture lead, proposal lead, contracts reviewer, technical SME, pricing lead, or executive reviewer.
- Do not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.
- State that all outputs are draft internal workflow aids requiring qualified human review.

## Review Standard

After drafting, compare the outputs with:

- `workflows/opportunity-triage/expected-output-guide.md`

Pay special attention to whether the draft:

- treats customer fit as documented relationship evidence, not general capability overlap;
- treats incomplete review criteria and missing pricing as questions;
- keeps partner readiness partial unless commitment is documented;
- preserves the unresolved on-site-session conflict;
- states that the recommendation is preliminary and belongs to human decision-makers.
