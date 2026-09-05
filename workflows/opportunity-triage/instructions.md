# Instructions: Opportunity Triage

## Goal

Create a first-pass opportunity intake worksheet and bid/no-bid brief that a human reviewer can inspect.

For the first run, use the fully synthetic opportunity packet in this folder. Every opportunity and organization fact comes from the repository, so the learner can focus on source traceability, uncertainty, and review discipline.

After completing the synthetic exercise, a learner may use a public SAM.gov opportunity with the [Public SAM.gov Practice Reference Prompt](../../FIRST-RUN-REFERENCE-PROMPT.md). Use approved organizational sources only when the data and workspace are approved.

## Working Definitions

- **Score 0:** Weak or no evidence in the approved sources.
- **Score 1:** Partial or uncertain evidence in the approved sources.
- **Score 2:** Strong evidence from the approved sources.
- **Unknown:** The approved sources do not provide enough information to assign a score. Do not treat an unknown as a negative fact.
- **Customer fit:** The strength of approved evidence that Synthetic Organization Alpha has documented knowledge of or a relationship with the customer named in the opportunity. Use only approved relationship evidence; do not infer customer familiarity from general capability fit.
- **Red flag:** A known fact in the approved sources that may create pursuit or delivery risk.
- **Missing information:** Information the approved sources do not provide. Record it as a question, not as a negative fact.

Approved reviewer roles are: **BD lead, capture lead, proposal lead, contracts reviewer, technical SME, pricing lead, and executive reviewer**. These are suggested routing labels for questions and next steps, not facts about a real team or authorization for Codex to invent people.

## First Run: Fully Synthetic

1. Open [First-Run Starter Prompt](../../FIRST-RUN-PROMPT.md) and paste it into Codex.
2. Let Codex read the safety boundaries, this workflow overview, the [source packet index](data/source-packet-index.md), and the workflow prompt.
3. Before Codex creates files, check that it identifies the synthetic sources, one unknown or weak point, and the two planned drafts.
4. Explicitly approve creation only after you review that plan.
5. Inspect the diff: confirm what changed, which files changed, whether the drafts followed the prompt, whether any facts were invented, and whether qualified human review remains required.
6. Ask Codex to explain one score, risk, missing fact, or reviewer question by tracing it to the source.
7. Revise the draft and apply the [human-review checklist](../../guides/human-review-checklist.md).

> **Why this matters:** The source packet is the boundary for the exercise. It lets you test whether Codex preserves unknowns instead of filling gaps with plausible-sounding claims.

> **You are doing well if:** You can point to a source row, field, or section behind one material claim and name one item the sources do not establish.

## Synthetic Source Packet Walkthrough

1. Read the [source packet index](data/source-packet-index.md) to see the approved synthetic files.
2. Read the [synthetic opportunity notice](data/synthetic-opportunity-notice.md), [synthetic opportunity summary](data/synthetic-opportunity-summary.md), and [synthetic opportunity input CSV](data/synthetic-opportunity-input.csv). Use the CSV's `status` column to identify known, partial, or unknown fields.
3. Read the [synthetic review criteria](data/synthetic-review-criteria.md) and [synthetic customer context](data/synthetic-customer-context.md). Preserve the conflicting on-site-session note as unresolved.
4. Review the [synthetic capability statement](data/synthetic-capability-statement.md), [past-performance snapshots](data/synthetic-past-performance-snapshots.csv), [delivery-capacity data](data/synthetic-delivery-capacity.csv), and [staffing and partner notes](data/synthetic-staffing-and-partner-notes.csv).
5. Review the [opportunity intake template](templates/opportunity-intake.md) and [bid/no-bid brief template](templates/bid-no-bid-brief.md).
6. Compare the drafts with the [expected output guide](expected-output-guide.md).

## Try 2: Public Opportunity Practice

Use the public-SAM prompt only after completing the fully synthetic first run. It uses one public opportunity as the practice target and the repository's synthetic organization files as pretend company evidence. If a learner has not chosen an opportunity, treat that as the next optional step rather than a mistake.

## Success Standard

The drafts should make the team's reasoning and missing information easier to review. A successful first run is not a perfect answer. It is a draft that helps a learner see the source facts, ask better reviewer questions, and notice where Codex may be too confident.

This training does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice. The output is a draft internal workflow aid requiring qualified human review.
