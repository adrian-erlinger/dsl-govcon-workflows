# Past Performance and Teaming Evidence Finder

## Audience

Small businesses, capture leads, teaming leads, and growth teams preparing for larger opportunities.

## Practical Need

Teams may struggle to compare prior work, staff capabilities, and potential partner evidence with a new opportunity. This workflow makes candidate evidence and gaps visible.

This is an additional example workflow. Complete the canonical Opportunity Triage workflow first, then use this workflow to practice evidence matching and teaming-gap reasoning.

Codex can help organize approved evidence, but it should never turn gaps into claims. This workflow reinforces human accountability for proposal, capture, and teaming decisions.

## Draft Outputs

- best-fit synthetic past performance examples;
- requirement-by-requirement evidence assessment;
- evidence and capability gaps;
- preliminary teaming needs;
- a desired partner profile;
- questions for capture and qualified reviewers.

Generated drafts belong in [outputs/](outputs/) so each workflow keeps its practice results separate from source files, prompts, and templates.

This workflow does not determine qualification, eligibility, acceptability, or partner selection. The output is a draft internal workflow aid requiring qualified human review.

## Synthetic Inputs

- [Target Requirements](data/synthetic-target-requirements.csv): what the fictional opportunity expects and what evidence would support each requirement.
- [Opportunity Context](data/synthetic-opportunity-context.md): fictional scenario, target scope, and capture concerns.
- [Evidence Inventory](data/synthetic-evidence-inventory.csv): available evidence artifacts and their limits.
- [Past Performance](data/synthetic-past-performance.csv): fictional prior-project records, documented outcomes, and evidence limits.
- [Staff Capabilities](data/synthetic-staff-capabilities.csv): fictional staff experience, availability status, and qualification limits.
- [Workstream Capacity](data/synthetic-workstream-capacity.csv): fictional internal capacity view for simultaneous workstreams.
- [Partner Profiles](data/synthetic-partner-profiles.csv): fictional potential-partner capabilities, evidence, interest, and limitations.
- [Diligence Questions](data/synthetic-diligence-questions.csv): open questions that qualified reviewers must resolve.

## Try This Workflow

1. Open [Instructions](instructions.md).
2. Start with the [Source Packet Index](data/source-packet-index.md), then inspect the synthetic files described above.
3. Review the [Evidence-Fit Brief Template](templates/evidence-fit-brief.md) and [Teaming Gap Analysis Template](templates/teaming-gap-analysis.md).
4. Use [prompt.md](prompt.md). Codex will explain the planned files and ask before creating them in `outputs/`.
5. After generation, compare both drafts with the [Expected Output Guide](expected-output-guide.md).

## Your First Practice Run

You can begin by simply telling Codex: **"Let's do the Past Performance and Teaming workflow. Help me get started."**

Codex should first explain the exercise and the two planned files. It will not create anything until you explicitly approve that step in the chat. You do not need to know the evidence-rating terms or every source file at the start.

The first file, the evidence-fit brief, compares each opportunity need with the records that may or may not support it. The second, the teaming-gap analysis, keeps potential gaps and unconfirmed partner information visible. The point is to practice making the limits of evidence clear; it is not to decide that a company is qualified or that a partner has been selected.

Both outputs are draft internal planning aids requiring qualified human review.
