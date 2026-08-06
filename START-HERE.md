# Start Here

Welcome. You do not need to be a software engineer to use this repository.

In the workshop, you will inspect a synthetic Opportunity Triage case packet, ask Codex to draft an opportunity intake and bid/no-bid brief, and review and revise the proposed file changes. You are building reviewable Markdown and CSV workflow assets to learn how to use Codex.

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

## First-Time Path

For the starting workflow:

1. **Read the instructions:** Open the [Opportunity Triage Workflow Overview](workflows/opportunity-triage/README.md) and [Opportunity Triage Instructions](workflows/opportunity-triage/instructions.md).
2. **Inspect the synthetic inputs:** Start with the [Source Packet Index](workflows/opportunity-triage/data/source-packet-index.md), then read the [Synthetic Opportunity Summary](workflows/opportunity-triage/data/synthetic-opportunity-summary.md), [Synthetic Opportunity Input](workflows/opportunity-triage/data/synthetic-opportunity-input.csv), [Synthetic Capability Statement](workflows/opportunity-triage/data/synthetic-capability-statement.md), [Past Performance Snapshots](workflows/opportunity-triage/data/synthetic-past-performance-snapshots.csv), and [Staffing and Partner Notes](workflows/opportunity-triage/data/synthetic-staffing-and-partner-notes.csv).
3. **Review the blank output structures:** Open the [Opportunity Intake Template](workflows/opportunity-triage/templates/opportunity-intake.md) and [Bid/No-Bid Brief Template](workflows/opportunity-triage/templates/bid-no-bid-brief.md).
4. **Create the drafts:** Use the [Opportunity Triage Prompt](workflows/opportunity-triage/prompt.md).
5. **Check the result:** Compare the drafts with the [Expected Output Guide](workflows/opportunity-triage/expected-output-guide.md).
6. **Review and revise:** Use [Reviewing Codex Diffs](guides/reviewing-codex-diffs.md) and the [Human Review Checklist](guides/human-review-checklist.md).

## Additional Example: RFP Compliance

The RFP Compliance Matrix & Proposal Responsibility Tracker files remain in the repository as an additional example workflow.

1. **Read the instructions:** Open the [RFP Workflow Overview](workflows/rfp-compliance-matrix/README.md) and [RFP Instructions](workflows/rfp-compliance-matrix/instructions.md).
2. **Inspect the synthetic inputs:** Read the [Synthetic RFP Excerpt](workflows/rfp-compliance-matrix/data/synthetic-rfp-excerpt.md), [Synthetic Deliverables](workflows/rfp-compliance-matrix/data/synthetic-deliverables.csv), and [Synthetic Team Roles](workflows/rfp-compliance-matrix/data/synthetic-team-roles.csv).
3. **Review the blank output structures:** Open the [Compliance Matrix Template](workflows/rfp-compliance-matrix/templates/compliance-matrix.csv) and [Responsibility Tracker Template](workflows/rfp-compliance-matrix/templates/responsibility-tracker.csv).
4. **Create the drafts:** Use the [RFP Workflow Prompt](workflows/rfp-compliance-matrix/prompt.md).
5. **Check the result:** Compare the drafts with the [RFP Expected Output Guide](workflows/rfp-compliance-matrix/expected-output-guide.md).
6. **Review and revise:** Use [Reviewing Codex Diffs](guides/reviewing-codex-diffs.md) and the [Human Review Checklist](guides/human-review-checklist.md).

## Additional Example: Past Performance & Teaming

The Past Performance & Teaming Evidence Finder files remain in the repository as an additional example workflow.

1. **Read the instructions:** Open the [Workflow Overview](workflows/past-performance-teaming/README.md) and [Past Performance and Teaming Instructions](workflows/past-performance-teaming/instructions.md).
2. **Inspect the synthetic inputs:** Read [Target Requirements](workflows/past-performance-teaming/data/synthetic-target-requirements.csv), [Past Performance](workflows/past-performance-teaming/data/synthetic-past-performance.csv), [Staff Capabilities](workflows/past-performance-teaming/data/synthetic-staff-capabilities.csv), and [Partner Profiles](workflows/past-performance-teaming/data/synthetic-partner-profiles.csv).
3. **Review the blank output structures:** Open the [Evidence-Fit Brief Template](workflows/past-performance-teaming/templates/evidence-fit-brief.md) and [Teaming Gap Analysis Template](workflows/past-performance-teaming/templates/teaming-gap-analysis.md).
4. **Create the drafts:** Use the [Workflow Prompt](workflows/past-performance-teaming/prompt.md).
5. **Check the result:** Compare the drafts with the [Expected Output Guide](workflows/past-performance-teaming/expected-output-guide.md).
6. **Review and revise:** Use [Reviewing Codex Diffs](guides/reviewing-codex-diffs.md) and the [Human Review Checklist](guides/human-review-checklist.md).

All outputs are draft internal workflow assets. They are not authoritative and are not ready for implementation without qualified human review.
