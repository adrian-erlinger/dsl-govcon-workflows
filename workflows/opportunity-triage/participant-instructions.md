# Participant Instructions: Opportunity Triage

## Goal

Create a first-pass opportunity brief from the provided synthetic files.

## Steps

1. Read `data/synthetic-opportunity-summary.md`.
2. Open `data/synthetic-opportunity-input.csv` and identify known and missing fields.
3. Review the output structures in `templates/`.
4. Copy the prompt from `prompt.md` into Codex.
5. Ask Codex to create draft output files outside the `templates/` folder:
   - `draft-opportunity-intake.md`
   - `draft-bid-no-bid-brief.md`
6. Inspect the diff before accepting changes.
7. Find at least one score, risk, or recommendation that needs a human question.
8. Revise the draft and apply the participant human-review checklist.

## Success Standard

The draft should make the team's reasoning and missing information easier to review. It should not make the final pursuit decision.

This training does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice. The output is a draft internal workflow aid requiring qualified human review.

