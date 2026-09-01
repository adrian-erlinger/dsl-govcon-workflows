# Start Here

Welcome. 

In the workshop, you will inspect a synthetic Opportunity Triage case packet, ask Codex to draft an opportunity intake and bid/no-bid brief, and review and revise the proposed file changes. You are building reviewable Markdown and CSV workflow assets to learn how to use Codex.

Opportunity Triage is the canonical first workflow in this repository. The other workflows are additional examples you can explore after you complete this starting path.

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

1. Read [Safety and Boundaries](SAFETY-AND-BOUNDARIES.md).
2. Read [Codex Setup and Navigation](guides/codex-setup-and-navigation.md) to familiarize yourself with how to navigate Codex.
3. Practice with the [synthetic data files already provided](workflows/opportunity-triage/data/source-packet-index.md).
4. Begin with the [Opportunity Triage and Bid/No-Bid Brief workflow](workflows/opportunity-triage/README.md).
5. Use the **Opportunity Triage & Bid/No-Bid Brief** path below as the starting workflow.

When you [review a diff](guides/reviewing-codex-diffs.md), you are reviewing the file changes Codex proposes. You do not need to know Git commands or programming to do this.

## 10-Minute Quick Start

Use this lane if you want to try the repository before reading every source file in detail.

1. Read [Safety and Boundaries](SAFETY-AND-BOUNDARIES.md).
2. Open [First-Run Starter Prompt](FIRST-RUN-PROMPT.md).
3. Copy the prompt into Codex.
4. Let Codex create the two Opportunity Triage draft files.
5. Review the proposed changes before accepting them.
6. Compare the drafts with the [Expected Output Guide](workflows/opportunity-triage/expected-output-guide.md).
7. Ask Codex one follow-up question about a weak score, missing fact, or reviewer question.

This quick start is enough to see the workflow in action. Use the detailed path below when you want to understand the source packet more carefully.

## Detailed First-Time Path

For the starting workflow:

1. **Read the instructions:** Open the [Opportunity Triage Workflow Overview](workflows/opportunity-triage/README.md) and [Opportunity Triage Instructions](workflows/opportunity-triage/instructions.md).
2. **Inspect the synthetic inputs:** Start with the [Source Packet Index](workflows/opportunity-triage/data/source-packet-index.md), then read the [Synthetic Opportunity Notice](workflows/opportunity-triage/data/synthetic-opportunity-notice.md), [Synthetic Opportunity Summary](workflows/opportunity-triage/data/synthetic-opportunity-summary.md), [Synthetic Opportunity Input](workflows/opportunity-triage/data/synthetic-opportunity-input.csv), [Synthetic Review Criteria](workflows/opportunity-triage/data/synthetic-review-criteria.md), [Synthetic Customer Context](workflows/opportunity-triage/data/synthetic-customer-context.md), [Synthetic Capability Statement](workflows/opportunity-triage/data/synthetic-capability-statement.md), [Past Performance Snapshots](workflows/opportunity-triage/data/synthetic-past-performance-snapshots.csv), [Delivery Capacity](workflows/opportunity-triage/data/synthetic-delivery-capacity.csv), and [Staffing and Partner Notes](workflows/opportunity-triage/data/synthetic-staffing-and-partner-notes.csv).
3. **Review the blank output structures:** Open the [Opportunity Intake Template](workflows/opportunity-triage/templates/opportunity-intake.md) and [Bid/No-Bid Brief Template](workflows/opportunity-triage/templates/bid-no-bid-brief.md).
4. **Create the drafts:** Use the [Opportunity Triage Prompt](workflows/opportunity-triage/prompt.md).
5. **Check the result:** Compare the drafts with the [Expected Output Guide](workflows/opportunity-triage/expected-output-guide.md).
6. **Review and revise:** Use [Reviewing Codex Diffs](guides/reviewing-codex-diffs.md) and the [Human Review Checklist](guides/human-review-checklist.md).
7. **Connect the pattern to your work:** Read [Replacing Synthetic Data](guides/replacing-synthetic-data.md) to see which approved organizational files could replace each synthetic training file later, outside this training repository.
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
