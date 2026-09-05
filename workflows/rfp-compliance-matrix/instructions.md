# Instructions: RFP Compliance Matrix

## Goal

Draft a compliance matrix and responsibility tracker from a synthetic RFP source packet.

## What You Will See

This exercise starts with a fictional RFP packet. Codex turns that packet into two working spreadsheets so you can see how a large set of instructions becomes reviewable:

- The **compliance matrix** records an instruction, its source, and any question that needs human attention.
- The **responsibility tracker** records the same response work as proposed coordination and review handoffs.

You are not expected to know the terminology or inspect every row at once. Start by tracing one row back to the source packet, then notice how the draft keeps unclear information visible for a human reviewer.

## Guided Tour

Ask Codex, **"Walk me through the RFP Compliance Matrix workflow,"** when you want to learn before creating drafts. The tour should take one small idea at a time:

1. An RFP can place instructions in several locations, so the workflow makes each instruction easier to find and discuss.
2. A sentence that asks for two different things becomes two separate, checkable items. For example, a discovery approach and a workshop plan are tracked separately.
3. When a source changes, is unclear, or needs specialist input, the draft preserves that question instead of guessing.

The tour is read-only. Codex should not create draft files unless you later explicitly ask it to do so.

## Beginner Column Guide

| Column | Meaning |
|---|---|
| `source_section` | Exact synthetic section or attachment where the requirement appears. |
| `evidence_needed` | Material or check needed to show that the response addresses the requirement. Do not invent evidence. |
| `compliance_risk` | A source-based omission, ambiguity, mismatch, or uncertainty that needs human attention—not a legal or compliance conclusion. |
| `review_status` | Current human-review state. Start with `Not reviewed` or `Needs qualified review`; only a human may mark an item confirmed. |
| `consulted_role` | Specialist role that should review or provide input. |
| `due_date_status` | Whether the date is a source deadline, `Needs human planning`, or has been confirmed by a human. |
| `review_gate` | Human checkpoint required before the task can be treated as complete. |
| `routing_note` | Brief reason for the routing and any unanswered specialist question. |

A **proposed owner** coordinates the response item. A **consulted role** reviews or provides specialist input. Both are routing suggestions until a person confirms them.

- Route contract terms, instructions, submission conditions, exceptions, representations, flowdowns, and contractual-risk questions to `contracts_reviewer`.
- Route legal-interpretation or legal-risk questions requiring qualified legal judgment to `legal_reviewer`.
- Route to `devops_reviewer` only when the supplied synthetic RFP contains operational, deployment, hosting, automation, CI/CD, or environment-management evidence. Do not create a DevOps task merely because the role exists.

## Steps

1. Read `data/source-packet-index.md` to see the approved synthetic files.
2. Read `data/synthetic-rfp-excerpt.md`, `data/synthetic-submission-instructions.md`, and `data/synthetic-evaluation-factors.md`.
3. Inspect `data/synthetic-amendment-log.csv`, `data/synthetic-qa-log.csv`, `data/synthetic-deliverables.csv`, and `data/synthetic-team-roles.csv`.
4. Review the output columns and clearly labeled synthetic example rows in `templates/`. The examples show format only; they are not additional source requirements.
5. Copy the prompt from `prompt.md` into Codex. It will introduce the two planned files, then ask for your approval before creating them in `outputs/`.
6. Inspect each proposed row and source reference.
7. Compare both drafts with `expected-output-guide.md`.
8. Find one combined requirement that should be split, one amendment impact that should be reflected, or one owner that needs confirmation. For example, “Volume 1 shall describe the discovery approach and provide a workshop plan” should become two rows because each response item can be checked separately.
9. Revise the files and apply the human-review checklist.

Use only dates found in the synthetic RFP. If an internal draft date is needed but not supplied, leave `due_date` blank and set `due_date_status` to `Needs human planning`.

The general safety boundary belongs in these workflow instructions and review guidance. Do not repeat it mechanically in every CSV row; use `human_review_note` and `routing_note` for item-specific review needs.

## Success Standard

The draft should help qualified reviewers find, assign, and discuss requirements. It must not claim that every requirement has been identified, interpreted, or certified as compliant.

Both output files are draft internal workflow aids requiring qualified human review. This training does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.
