# Instructions: Opportunity Triage

## Goal

Create a first-pass opportunity intake worksheet and bid/no-bid brief from the provided synthetic Opportunity Triage case packet.

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

1. Read the [source packet index](data/source-packet-index.md) to see the approved files.
2. Read the [synthetic opportunity notice](data/synthetic-opportunity-notice.md) and [synthetic opportunity summary](data/synthetic-opportunity-summary.md).
3. Open the [synthetic opportunity input CSV](data/synthetic-opportunity-input.csv) and use the `status` column to identify which fields are known, partial, or unknown.
4. Read the [synthetic review criteria](data/synthetic-review-criteria.md). Notice which review factors are present and which evaluation details are missing.
5. Read the [synthetic customer context](data/synthetic-customer-context.md). Notice the difference between general customer context and a documented customer relationship. Preserve the conflicting on-site-session note as an unresolved source conflict.
6. Read the [synthetic capability statement](data/synthetic-capability-statement.md). Notice what it does and does not prove.
7. Review the [past-performance snapshots](data/synthetic-past-performance-snapshots.csv), [delivery-capacity data](data/synthetic-delivery-capacity.csv), and [staffing and partner notes](data/synthetic-staffing-and-partner-notes.csv). Look for caveats, partial evidence, conflicts, and missing information.
8. Review the output structures in the [opportunity intake template](templates/opportunity-intake.md) and [bid/no-bid brief template](templates/bid-no-bid-brief.md).
9. Open the [opportunity triage prompt](prompt.md), copy the full text inside the code block, and paste it into Codex. The prompt already tells Codex to create both draft files outside the `templates/` folder.
10. Inspect the diff before accepting the drafts: confirm what changed, which files changed, whether the drafts followed the prompt, whether any facts were invented, and whether qualified human review remains required.
11. Compare the drafts with the [expected output guide](expected-output-guide.md).
12. Find at least one score, risk, source conflict, or recommendation that needs a human question.
13. Revise the draft and apply the [human-review checklist](../../guides/human-review-checklist.md).

## Success Standard

The drafts should make the team's reasoning and missing information easier to review. They should not make the final pursuit decision.

This training does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice. The output is a draft internal workflow aid requiring qualified human review.
