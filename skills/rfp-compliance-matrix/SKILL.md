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

After the user explicitly approves draft creation, create:

- `workflows/rfp-compliance-matrix/outputs/draft-compliance-matrix.csv`
- `workflows/rfp-compliance-matrix/outputs/draft-responsibility-tracker.csv`

Use the templates in:

- `workflows/rfp-compliance-matrix/templates/compliance-matrix.csv`
- `workflows/rfp-compliance-matrix/templates/responsibility-tracker.csv`

## First-Time User Experience

When a user says, "Let's do the RFP compliance workflow," "Help me get started," or otherwise signals that they are new, begin the exercise without creating files. Do not begin with "Done," a file list, or unexplained row IDs.

Start by explaining that the repository contains a fictional RFP packet for practice. In plain language, explain that the compliance matrix is a structured list of what the RFP asks for and where each item appears, while the responsibility tracker is a separate list of proposed coordinating and review roles. Name the two planned drafts, tell the learner that no files have been created yet, and ask whether they would like you to create them now.

Do not create, edit, replace, or overwrite draft files until the learner gives a clear affirmative answer in the chat after this orientation. Treat a request to start, the existence of an approval control, or a previously copied workflow prompt as insufficient approval to write files. If a target file already exists, show the filename and obtain a separate explicit confirmation before replacing it.

After an approved draft is created, orient the learner before giving technical details:

- state what each draft is for, using ordinary language;
- point to two or three rows that demonstrate a useful habit, such as tracing an instruction to its source, recording an amendment, or leaving an unanswered question open;
- explain why proposed owner roles still need a person to confirm them;
- invite one small next action, such as checking a named source reference or asking why one item was split into two rows.

Use reassuring language. Do not suggest the learner has failed to provide information or should already understand RFP terms, CSV files, or repository paths. Keep the qualified-review boundary concise and put it after the practical explanation: these are training drafts, not a determination that a proposal is complete or compliant.

## Walk-Me-Through Conversation

When a user asks to "walk me through" the workflow, enter a read-only teaching conversation. Do not create, edit, replace, or overwrite any files, and do not treat the request as approval to prepare drafts.

The first reply must be self-contained and start with the learner's outcome, not the repository location. Explain that the exercise teaches them to turn a fictional RFP's scattered instructions into two simple working lists: one list of what the RFP asks for, and one list of proposed coordination and review handoffs. Tell them that no files have been created.

Guide the learner through only the first of these three stages in the first reply:

1. **See the job:** An RFP contains instructions in more than one place. The aim is to make each instruction easy to find and discuss.
2. **Turn an instruction into a checkable item:** A statement that asks for two distinct things becomes two separate items in the draft, each tied back to where it came from.
3. **Keep questions visible:** When the packet changes, is unclear, or needs specialist input, the draft records that rather than guessing.

Use one small, ordinary example in the first reply, without assuming the learner knows RFP terms. For example: "If the packet asks for a discovery approach and a workshop plan, those are two separate things to track." Then invite the learner to continue to the next stage.

Do not lead with repository paths, an inventory of source files, output filenames, record IDs, amendment IDs, specialist role names, or a long boundary disclaimer. Introduce those details only when they become useful in a later stage. Refer to draft outputs as planned work, not as existing files. Do not ask for file-creation approval during the walk-through unless the learner explicitly changes the request from learning the workflow to creating drafts.

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
