# Opportunity Triage and Bid/No-Bid Brief

## Audience

Founders, business development leads, capture managers, and small-business teams.

## Practical Need

Teams receive opportunity signals from many places but may lack a consistent first-pass triage process. This workflow helps you practice turning an opportunity notice and company evidence into a structured discussion aid.

This is the canonical first workflow in the repository. The first run uses a fully synthetic packet: the opportunity, organization evidence, review criteria, and deliberate uncertainties all come from this repository. That creates a safe, fixed scenario for learning the review loop.

After the first run, the same pattern can be practiced with a public SAM.gov opportunity and synthetic organization evidence, or later with approved organizational sources in an appropriate workspace.

Codex helps the team get to a more structured, evidence-based conversation faster. The pursuit decision still belongs to the team.

## Practice Inputs

For the first, fully synthetic run:

- synthetic opportunity notice and summary;
- structured opportunity fields and incomplete synthetic review criteria;
- synthetic customer context;
- synthetic capability statement, past-performance snapshots, delivery-capacity data, and staffing and partner-readiness notes;
- known dates, unknown information, and one deliberate source conflict;
- blank Markdown templates for the two draft outputs.

For the optional public-opportunity practice:

- a real public SAM.gov opportunity link, notice ID, solicitation number, or pasted opportunity text;
- the repository's synthetic organization evidence and blank templates.

## Draft Outputs

- fit score with reasoning;
- red flags and unknowns;
- preliminary pursuit recommendation;
- next-step capture questions.

A score is a discussion aid. It helps make assumptions and evidence visible; it is not a mathematical rule and not the final pursuit decision.

The output is a draft internal workflow aid. It is not a final bid/no-bid decision and requires qualified human review.

## Learning Outcomes

You will practice how to:

- understand permitted-data and professional-advice boundaries;
- inspect synthetic source files before asking Codex to act;
- use a structured prompt with named inputs and expected outputs;
- create draft Markdown workflow aids;
- inspect a Codex diff;
- identify unsupported assumptions and revise the draft.

## Workflow Sequence

| Step | Activity |
|---|---|
| 1 | Read the safety boundaries and workflow instructions. |
| 2 | Inspect the fully synthetic source packet and blank output templates. |
| 3 | Run the short starter prompt, review the planned files, and explicitly approve their creation. |
| 4 | Review the diff and trace one finding to its sources. |
| 5 | Revise one weak assumption, overstated score, or unclear reviewer question. |
| 6 | Reflect on how the pattern could later apply to a public opportunity or approved real workflow. |

## Try This Workflow

If you are practicing on your own, start with the fully synthetic first run.

1. Open [First-Run Starter Prompt](../../FIRST-RUN-PROMPT.md).
2. Let Codex identify the approved synthetic sources, an uncertainty, and the two planned output files.
3. Review that plan, then explicitly tell Codex to create the drafts.
4. Ask Codex to explain one score, risk, missing fact, or reviewer question that seems unclear.
5. Use [Reviewing Codex Diffs](../../guides/reviewing-codex-diffs.md) and the [Human Review Checklist](../../guides/human-review-checklist.md) before accepting any draft.

For a fuller walkthrough of the synthetic sources, use [instructions.md](instructions.md) and [prompt.md](prompt.md). For the optional second exercise with a public opportunity, use the [Public SAM.gov Practice Reference Prompt](../../FIRST-RUN-REFERENCE-PROMPT.md).

Facilitators can review [Facilitator Notes](facilitator-notes.md) before running a live session.

## Deeper Review Options

Use these only after completing the basic Opportunity Triage path. Do not add the other workflows to this starting path.

- Re-check the capability statement and past-performance evidence.
- Add or revise reviewer questions tied to weak evidence.
- Identify one place where the draft treats partial evidence too strongly.
- Identify one place where the draft should preserve a source conflict instead of resolving it too soon.
- Discuss how approved internal documents could replace the synthetic files in a later governed setting.
