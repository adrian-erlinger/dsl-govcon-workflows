# Opportunity Triage and Bid/No-Bid Brief

## Audience

Founders, business development leads, capture managers, and small-business teams.

## Practical Need

Teams receive opportunity signals from many places but may lack a consistent first-pass triage process. This workflow helps you practice turning an opportunity notice and company evidence into a structured discussion aid.

This is the canonical first workflow in the repository. In the guided first run, you use a real public SAM.gov opportunity as the opportunity being reviewed and the repository's synthetic company files as the pretend internal evidence. That lets you practice with a realistic public notice without using real company data.

The repository also includes a fully synthetic opportunity packet for closed rehearsals and facilitator-led demos.

Codex helps the team get to a more structured, evidence-based conversation faster. The pursuit decision still belongs to the team.

## Practice Inputs

For the guided first run:

- a real public SAM.gov opportunity link, notice ID, solicitation number, or pasted opportunity text;
- the synthetic capability statement;
- synthetic past-performance snapshots;
- synthetic delivery-capacity data;
- synthetic staffing and partner-readiness notes;
- synthetic review criteria as a practice scoring frame;
- blank Markdown templates for the two draft outputs.

For the fully synthetic rehearsal:

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
- inspect the public opportunity source and synthetic company evidence before asking Codex to act;
- use a structured prompt with named inputs and expected outputs;
- create draft Markdown workflow aids;
- inspect a Codex diff;
- identify unsupported assumptions and revise the draft.

## Workflow Sequence

| Step | Activity |
|---|---|
| 1 | Read the safety boundaries and workflow instructions |
| 2 | Choose a public SAM.gov opportunity for the guided first run, or use the fully synthetic packet |
| 3 | Inspect the synthetic company evidence and blank output templates |
| 4 | Run the starter prompt, review the planned files, and explicitly approve their creation |
| 5 | Review the diff and trace findings to sources |
| 6 | Revise one weak assumption, overstated score, or unclear reviewer question |
| 7 | Reflect on how the pattern could later apply to an approved real workflow |

## Try This Workflow

Use the path your facilitator gives you. If you are practicing on your own, start with the guided first run.

1. Open [First-Run Starter Prompt](../../FIRST-RUN-PROMPT.md).
2. Give Codex a public SAM.gov link, notice ID, solicitation number, or pasted opportunity text when it asks for the opportunity.
3. Let Codex compare that public opportunity with the synthetic company evidence.
4. Review the planned draft files, then explicitly tell Codex to create them. Their filenames should include the solicitation number.
5. Ask Codex to explain one score, risk, missing fact, or reviewer question that seems unclear.
6. Use [Reviewing Codex Diffs](../../guides/reviewing-codex-diffs.md) and the [Human Review Checklist](../../guides/human-review-checklist.md) before accepting any draft.

For a closed synthetic rehearsal, use [prompt.md](prompt.md). That version uses only the files listed in the [Source Packet Index](data/source-packet-index.md).

Facilitators can also review [Facilitator Notes](facilitator-notes.md) before running a live session.

## Deeper Review Options

Use these only after completing the basic Opportunity Triage path. Do not add the other workflows to this starting path.

- Re-check the capability statement and past-performance evidence.
- Add or revise reviewer questions tied to weak evidence.
- Identify one place where the draft treats partial evidence too strongly.
- Identify one place where the draft should preserve a source conflict instead of resolving it too soon.
- Discuss how approved internal documents could replace the synthetic files in a later governed setting.
