# Start Here

Welcome. This repository is a practice space for learning how to use Codex on GovCon workflow tasks. You will organize source information, draft reviewable Markdown and CSV files, and inspect proposed changes before accepting anything.

You do not need to understand the whole repository before you begin.

## Start Here: 15-Minute Synthetic Opportunity Triage

This is the one starting lane for first-time learners. It uses only the repository's fictional source files, so you can focus on the workflow without finding, uploading, or interpreting a real opportunity.

1. Read [Safety and Boundaries](SAFETY-AND-BOUNDARIES.md).
2. Open [First-Run Starter Prompt](FIRST-RUN-PROMPT.md) and copy it into Codex.
3. Let Codex identify its sources and planned drafts; explicitly approve creation only after you have reviewed that plan.
4. Review the two proposed draft files in `workflows/opportunity-triage/outputs/`.
5. Ask Codex to show the source behind one score, claim, or reviewer question.

> **Why this matters:** You are checking what Codex is allowed to use before asking it to draft.

> **You are doing well if:** You can name one unknown or weak source before creating an output.

> **Try saying:** “Show me the source behind that score before we revise it.”

The two outputs are draft internal workflow aids, not final bid/no-bid decisions. Review every Codex change before accepting it.

## What You Are Practicing

Opportunity Triage is the canonical first workflow in this repository. It helps you practice a first-pass pursuit conversation: What do we know, what is weak, what is missing, what should a qualified person review, and what preliminary recommendation is supported by the sources?

Use this cycle for every workflow:

**Inspect → Prompt → Review → Question → Revise**

Success means producing, checking, questioning, and revising a draft. The other workflows are additional examples to explore after this starting path.

## Learn the First Workflow in More Detail

1. Read the [Opportunity Triage Workflow Overview](workflows/opportunity-triage/README.md) and [Instructions](workflows/opportunity-triage/instructions.md).
2. Inspect the [synthetic source packet](workflows/opportunity-triage/data/source-packet-index.md) and the two blank [output templates](workflows/opportunity-triage/templates/).
3. Compare the drafts with the [Expected Output Guide](workflows/opportunity-triage/expected-output-guide.md).
4. Use [Reviewing Codex Diffs](guides/reviewing-codex-diffs.md) and the [Human Review Checklist](guides/human-review-checklist.md) to challenge unsupported conclusions.

If you want help navigating Codex before the exercise, read [Codex Setup and Navigation](guides/codex-setup-and-navigation.md). You do not need Git commands or programming knowledge to review a diff.

## Try 2: Public SAM.gov Opportunity

After completing the synthetic exercise, use the detailed [Public SAM.gov Practice Reference Prompt](FIRST-RUN-REFERENCE-PROMPT.md) to compare one public opportunity with the repository's synthetic organization evidence. This optional second exercise is not a prerequisite for starting.

## Additional Example Workflows

After the first workflow, explore:

- [RFP Compliance Matrix and Proposal Responsibility Tracker](workflows/rfp-compliance-matrix/README.md)
- [Past Performance and Teaming Evidence Finder](workflows/past-performance-teaming/README.md)

All outputs are draft internal workflow assets. They are not authoritative and require qualified human review.

## After You Master the Basics

Read [After the Basics](guides/after-the-basics.md) to replace synthetic files with approved organizational equivalents in a governed workspace or to design a new workflow. Use [Workflow Coach Prompt](prompts/workflow-coach.md) when you are ready to design one.
