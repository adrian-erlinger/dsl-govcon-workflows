# Opportunity Triage and Bid/No-Bid Brief

## Audience

Founders, business development leads, capture managers, and small-business teams.

## Practical Need

Teams receive opportunity signals from many places but may lack a consistent first-pass triage process. This workflow turns a synthetic opportunity packet into a structured discussion aid.

This is the canonical first workflow in the repository. It is the polished test fixture for learning the pattern before exploring the additional examples.

Codex helps the team get to a more structured, evidence-based conversation faster. The pursuit decision still belongs to the team.

## Inputs

- synthetic opportunity notice;
- synthetic opportunity summary;
- structured opportunity fields;
- incomplete synthetic review criteria;
- synthetic customer context;
- mock synthetic capability statement;
- synthetic past-performance snapshots;
- synthetic delivery-capacity data;
- synthetic staffing and partner-readiness notes;
- known dates, unknown information, and one deliberate source conflict.

## Draft Outputs

- fit score with reasoning;
- red flags and unknowns;
- preliminary pursuit recommendation;
- next-step capture questions.

A score is a discussion aid. It helps make assumptions and evidence visible; it is not a mathematical rule and not the final pursuit decision.

The output is a draft internal workflow aid. It is not a final bid/no-bid decision and requires qualified human review.

## Learning Outcomes

You will practice how to:

- understand the permitted-data and professional-advice boundaries;
- inspect a synthetic case packet before asking Codex to act;
- use a structured prompt with named inputs and expected outputs;
- create draft Markdown workflow aids;
- inspect a Codex diff;
- identify unsupported assumptions and revise the draft.

## Workflow Sequence

| Step | Activity |
|---|---|
| 1 | Read the safety boundaries and workflow instructions |
| 2 | Inspect the synthetic opportunity case packet |
| 3 | Review the blank output templates |
| 4 | Run the Opportunity Triage prompt and create the draft files |
| 5 | Review the diff and trace findings to sources |
| 6 | Revise one weak assumption, overstated score, or unclear reviewer question |
| 7 | Reflect on how the pattern could later apply to an approved real workflow |

## Try This Workflow

1. If Codex is new to you, read [Codex Setup and Navigation](../../guides/codex-setup-and-navigation.md).
2. Open [Instructions](instructions.md).
3. Inspect the [Source Packet Index](data/source-packet-index.md) and approved files in `data/`.
4. Read the [Synthetic Opportunity Notice](data/synthetic-opportunity-notice.md), [Synthetic Opportunity Summary](data/synthetic-opportunity-summary.md), [Synthetic Opportunity Input](data/synthetic-opportunity-input.csv), [Synthetic Review Criteria](data/synthetic-review-criteria.md), [Synthetic Customer Context](data/synthetic-customer-context.md), [Synthetic Capability Statement](data/synthetic-capability-statement.md), [Past Performance Snapshots](data/synthetic-past-performance-snapshots.csv), [Delivery Capacity](data/synthetic-delivery-capacity.csv), and [Staffing and Partner Notes](data/synthetic-staffing-and-partner-notes.csv).
5. Review the [Opportunity Intake Template](templates/opportunity-intake.md) and [Bid/No-Bid Brief Template](templates/bid-no-bid-brief.md).
6. Use [prompt.md](prompt.md).
7. Compare the result with [Expected Output Guide](expected-output-guide.md).
8. Use [Reviewing Codex Diffs](../../guides/reviewing-codex-diffs.md) and the [Human Review Checklist](../../guides/human-review-checklist.md) before accepting any draft.

Facilitators can also review [Facilitator Notes](facilitator-notes.md) before running a live session.

## Deeper Review Options

Use these only after completing the basic Opportunity Triage path. Do not add the other workflows to this starting path.

- Re-check the capability statement and past-performance evidence.
- Add or revise reviewer questions tied to weak evidence.
- Identify one place where the draft treats partial evidence too strongly.
- Identify one place where the draft should preserve a source conflict instead of resolving it too soon.
- Discuss how approved internal documents could replace the synthetic files in a later governed setting.
