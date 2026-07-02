# Participant Instructions: RFP Compliance Matrix

## Goal

Draft a compliance matrix and responsibility tracker from a synthetic RFP excerpt.

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

1. Read `data/synthetic-rfp-excerpt.md`.
2. Inspect `data/synthetic-deliverables.csv` and `data/synthetic-team-roles.csv`.
3. Review the output columns and clearly labeled synthetic example rows in `templates/`. The examples show format only; they are not additional source requirements.
4. Copy the prompt from `prompt.md` into Codex. The prompt already tells Codex to create both draft files.
5. Inspect each proposed row and source reference.
6. Compare both drafts with `expected-output-guide.md`.
7. Find one combined requirement that should be split or one owner that needs confirmation. For example, “Volume 1 shall describe the discovery approach and provide a workshop plan” should become two rows because each response item can be checked separately.
8. Revise the files and apply the participant human-review checklist.

Use only dates found in the synthetic RFP. If an internal draft date is needed but not supplied, leave `due_date` blank and set `due_date_status` to `Needs human planning`.

The general safety boundary belongs in these workflow instructions and review guidance. Do not repeat it mechanically in every CSV row; use `human_review_note` and `routing_note` for item-specific review needs.

## Success Standard

The draft should help qualified reviewers find, assign, and discuss requirements. It must not claim that every requirement has been identified.

Both output files are draft internal workflow aids requiring qualified human review. This training does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.
