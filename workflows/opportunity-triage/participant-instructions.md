# Participant Instructions: Opportunity Triage

## Goal

Create a first-pass opportunity intake worksheet and bid/no-bid brief from the provided synthetic files.

## Working Definitions

- **Score 0:** Weak or no evidence in the supplied synthetic inputs.
- **Score 1:** Partial or uncertain evidence in the supplied synthetic inputs.
- **Score 2:** Strong evidence from the supplied synthetic inputs.
- **Unknown:** The supplied inputs do not provide enough information to assign a score. Do not treat an unknown as a negative fact.
- **Customer fit:** The strength of supplied evidence that Synthetic Organization Alpha has documented knowledge of or a relationship with the fictional customer. Use only the customer relationship and related information in the supplied synthetic files; do not infer familiarity from general capability fit.
- **Red flag:** A known fact in the supplied inputs that may create pursuit or delivery risk.
- **Missing information:** Information the supplied inputs do not provide. Record it as a question, not as a negative fact.

Approved reviewer roles are: **BD lead, capture lead, proposal lead, contracts reviewer, technical SME, pricing lead, and executive reviewer**. These are suggested routing labels for questions and next steps, not facts about a real team or authorization for Codex to invent people.

## Steps

1. Read the [synthetic opportunity summary](data/synthetic-opportunity-summary.md).
2. Open the [synthetic opportunity input CSV](data/synthetic-opportunity-input.csv) and use the `status` column to identify which fields are known, partial, or unknown.
3. Review the output structures in the [opportunity intake template](templates/opportunity-intake.md) and [bid/no-bid brief template](templates/bid-no-bid-brief.md).
4. Open the [opportunity triage prompt](prompt.md), copy the full text inside the code block, and paste it into Codex. The prompt already tells Codex to create both draft files outside the `templates/` folder.
5. Inspect the diff before accepting the drafts: confirm what changed, which files changed, whether the drafts followed the prompt, whether any facts were invented, and whether qualified human review remains required.
6. Compare the drafts with the [expected output guide](expected-output-guide.md).
7. Find at least one score, risk, or recommendation that needs a human question.
8. Revise the draft and apply the [participant human-review checklist](../../participant/human-review-checklist.md).

## Success Standard

The drafts should make the team's reasoning and missing information easier to review. They should not make the final pursuit decision.

This training does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice. The output is a draft internal workflow aid requiring qualified human review.
