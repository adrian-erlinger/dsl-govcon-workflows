# Start Here

Welcome. 

This repository is a practice space for learning how to use Codex on GovCon workflow tasks. You will ask Codex to organize source information, draft reviewable Markdown and CSV files, and then help you inspect the changes before anything is accepted.

You do not need to understand the whole repository before you begin. Start with one guided exercise, notice what Codex creates, and then review the draft like a careful human reviewer.

## If Your Facilitator Said To Launch The First-Run Prompt

Open [FIRST-RUN-PROMPT.md](FIRST-RUN-PROMPT.md). It gives you a ready-to-use message for Codex.

In that first run, you will practice an early go/no-go review using:

- one real public SAM.gov opportunity as the opportunity being reviewed;
- the repository's synthetic company files as the pretend internal evidence.

Codex will guide you through the next small step. If you have not picked a SAM.gov opportunity yet, that is okay.

## What You Are Practicing

Opportunity Triage is the canonical first workflow in this repository. It helps you practice a first-pass pursuit conversation: What do we know, what is weak, what is missing, what should a qualified person review, and what preliminary recommendation is supported by the sources?

The other workflows are additional examples you can explore after you complete this starting path.

## A Simple Working Pattern

Use this cycle for every workflow:

**Inspect → Prompt → Review → Question → Revise**

- **Inspect:** Understand the source files and identify what is missing.
- **Prompt:** Give Codex a bounded task and a specific output format.
- **Review:** Examine each proposed file change.
- **Question:** Challenge assumptions, invented facts, weak evidence, and false certainty.
- **Revise:** Correct the draft before a qualified person decides whether it is useful.

Success means producing, checking, questioning, and revising a draft. Review every Codex change before accepting it.

## Before You Begin

Use this section when you want the full map. In a live workshop, your facilitator may send you directly to [FIRST-RUN-PROMPT.md](FIRST-RUN-PROMPT.md), and that is a perfectly good place to start.

1. Read [Safety and Boundaries](SAFETY-AND-BOUNDARIES.md).
2. Read [Codex Setup and Navigation](guides/codex-setup-and-navigation.md) to familiarize yourself with how to navigate Codex.
3. Begin with the [Opportunity Triage and Bid/No-Bid Brief workflow](workflows/opportunity-triage/README.md).
4. Use [First-Run Starter Prompt](FIRST-RUN-PROMPT.md) when you are ready for Codex to guide the first practice run.
5. Use the [synthetic data packet](workflows/opportunity-triage/data/source-packet-index.md) when you want a fully fictional rehearsal.

When you [review a diff](guides/reviewing-codex-diffs.md), you are reviewing the file changes Codex proposes. You do not need to know Git commands or programming to do this.

## 10-Minute Quick Start

Use this lane if you want to try the repository before reading every source file in detail.

1. Read [Safety and Boundaries](SAFETY-AND-BOUNDARIES.md).
2. Open [First-Run Starter Prompt](FIRST-RUN-PROMPT.md).
3. Copy the prompt into Codex.
4. When Codex asks for a SAM.gov opportunity, provide a public link, notice ID, solicitation number, or pasted opportunity text.
5. Let Codex create the two Opportunity Triage draft files in `workflows/opportunity-triage/outputs/`, with the solicitation number in each filename.
6. Review the proposed changes before accepting them.
7. Ask Codex one follow-up question about a weak score, missing fact, or reviewer question.

This quick start is enough to see the workflow in action. Use the detailed path below when you want to understand the practice sources and templates more carefully.

## Detailed First-Time Path

For the starting workflow:

1. **Read the instructions:** Open the [Opportunity Triage Workflow Overview](workflows/opportunity-triage/README.md) and [Opportunity Triage Instructions](workflows/opportunity-triage/instructions.md).
2. **Understand the practice inputs:** For the guided first run, the opportunity comes from a real public SAM.gov notice and the company evidence comes from synthetic files in this repository. For a closed synthetic rehearsal, the repository also includes a fictional opportunity packet.
3. **Inspect the synthetic company evidence:** Start with the [Synthetic Capability Statement](workflows/opportunity-triage/data/synthetic-capability-statement.md), then review [Past Performance Snapshots](workflows/opportunity-triage/data/synthetic-past-performance-snapshots.csv), [Delivery Capacity](workflows/opportunity-triage/data/synthetic-delivery-capacity.csv), and [Staffing and Partner Notes](workflows/opportunity-triage/data/synthetic-staffing-and-partner-notes.csv).
4. **Review the blank output structures:** Open the [Opportunity Intake Template](workflows/opportunity-triage/templates/opportunity-intake.md) and [Bid/No-Bid Brief Template](workflows/opportunity-triage/templates/bid-no-bid-brief.md).
5. **Create the drafts:** Use [First-Run Starter Prompt](FIRST-RUN-PROMPT.md) for the public SAM.gov exercise, or use the [Opportunity Triage Prompt](workflows/opportunity-triage/prompt.md) for the fully synthetic exercise.
6. **Review and revise:** Use [Reviewing Codex Diffs](guides/reviewing-codex-diffs.md) and the [Human Review Checklist](guides/human-review-checklist.md). Ask Codex to explain any score, risk, source reference, or missing information that feels unclear.
7. **Connect the pattern to your work:** Read [Replacing Synthetic Data](guides/replacing-synthetic-data.md) to see which approved organizational files could replace each synthetic training file when your organization is ready.
8. **Plan your next workflow:** Read [After The Basics](guides/after-the-basics.md) when you are ready to replace synthetic data in a governed workspace or design your own GovCon workflow.

## Additional Example: RFP Compliance

The RFP Compliance Matrix & Proposal Responsibility Tracker files remain in the repository as an additional example workflow.

1. **Read the instructions:** Open the [RFP Workflow Overview](workflows/rfp-compliance-matrix/README.md) and [RFP Instructions](workflows/rfp-compliance-matrix/instructions.md).
2. **Inspect the synthetic inputs:** Start with the [RFP Source Packet Index](workflows/rfp-compliance-matrix/data/source-packet-index.md), then read the approved synthetic files in `workflows/rfp-compliance-matrix/data/`.
3. **Review the blank output structures:** Open the [Compliance Matrix Template](workflows/rfp-compliance-matrix/templates/compliance-matrix.csv) and [Responsibility Tracker Template](workflows/rfp-compliance-matrix/templates/responsibility-tracker.csv).
4. **Create the drafts:** Use the [RFP Workflow Prompt](workflows/rfp-compliance-matrix/prompt.md).
5. **Check the result:** Compare the drafts with the [RFP Expected Output Guide](workflows/rfp-compliance-matrix/expected-output-guide.md).
6. **Review and revise:** Use [Reviewing Codex Diffs](guides/reviewing-codex-diffs.md) and the [Human Review Checklist](guides/human-review-checklist.md).

## Additional Example: Past Performance & Teaming

The Past Performance & Teaming Evidence Finder files remain in the repository as an additional example workflow.

1. **Read the instructions:** Open the [Workflow Overview](workflows/past-performance-teaming/README.md) and [Past Performance and Teaming Instructions](workflows/past-performance-teaming/instructions.md).
2. **Inspect the synthetic inputs:** Start with the [Past Performance Source Packet Index](workflows/past-performance-teaming/data/source-packet-index.md), then read the approved synthetic files in `workflows/past-performance-teaming/data/`.
3. **Review the blank output structures:** Open the [Evidence-Fit Brief Template](workflows/past-performance-teaming/templates/evidence-fit-brief.md) and [Teaming Gap Analysis Template](workflows/past-performance-teaming/templates/teaming-gap-analysis.md).
4. **Create the drafts:** Use the [Workflow Prompt](workflows/past-performance-teaming/prompt.md).
5. **Check the result:** Compare the drafts with the [Expected Output Guide](workflows/past-performance-teaming/expected-output-guide.md).
6. **Review and revise:** Use [Reviewing Codex Diffs](guides/reviewing-codex-diffs.md) and the [Human Review Checklist](guides/human-review-checklist.md).

All outputs are draft internal workflow assets. They are not authoritative and are not ready for implementation without qualified human review.

## After You Master The Basics

Once you understand the Opportunity Triage pattern, use [After The Basics](guides/after-the-basics.md) to choose a next path:

- replace synthetic files with approved organizational equivalents in a governed workspace;
- ask Codex to coach you through designing a new GovCon workflow.

For workflow design coaching, use [Workflow Coach Prompt](prompts/workflow-coach.md). It asks Codex to help you define the purpose, approved inputs, outputs, reviewer roles, boundaries, and synthetic test case before any files are written.
