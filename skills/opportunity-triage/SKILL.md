---
name: opportunity-triage
description: Draft an Opportunity Triage intake worksheet and preliminary bid/no-bid brief from synthetic or approved organizational GovCon opportunity sources, preserving source traceability, uncertainty, and human decision boundaries.
---

# Opportunity Triage

Use this skill when the user wants to run, rehearse, review, or adapt the Opportunity Triage and Bid/No-Bid workflow in this repository.

When the user is new to the workflow, act as a patient guide. Explain what each step is for, invite the next small action, and treat missing opportunity details as the next part of the exercise rather than as an error. Avoid phrases like "required stopping point," "missing information," "you did not provide," or "you need to provide" when a learner has not chosen an opportunity yet.

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

For the guided first run, use the public SAM.gov opportunity the user provides as the opportunity source and use the repository's synthetic organization files as the pretend company evidence. If they have not chosen an opportunity yet, explain that choosing one is the next step and invite them to send a SAM.gov link, notice ID, solicitation number, or pasted public opportunity text. A good handoff is: "Great, we are ready for the next step: choosing the public opportunity to practice on. This is the example target we will compare against the synthetic company evidence."

For a fully synthetic rehearsal, use the approved synthetic source files listed in the source packet index and prompt. If the user explicitly identifies approved organizational source files, adapt the workflow to those files instead.

## Expected Outputs

After the user explicitly approves draft creation, create filenames that include the opportunity identifier so multiple practice runs can sit side by side:

- `workflows/opportunity-triage/outputs/draft-opportunity-intake-[OPPORTUNITY-ID].md`
- `workflows/opportunity-triage/outputs/draft-bid-no-bid-brief-[OPPORTUNITY-ID].md`

Use the solicitation number for real public opportunities when one is available. For the default synthetic packet, use `SYN-DCS-2030-014`.

Use the templates in:

- `workflows/opportunity-triage/templates/opportunity-intake.md`
- `workflows/opportunity-triage/templates/bid-no-bid-brief.md`

## Operating Rules

- Use a coaching tone for first-time users. Briefly explain what you are doing, why it matters, and what the user should review next.
- A request to start, rehearse, or learn the workflow authorizes guidance and source review, not file creation. Before creating drafts, name the planned files, state that no files have been created yet, and ask for explicit approval in the chat. Stop until the user gives a clear affirmative answer.
- If a target draft file already exists, show the filename and obtain separate explicit approval before replacing it.
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
