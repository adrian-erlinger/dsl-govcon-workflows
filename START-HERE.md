# Start Here

Welcome. You do not need to be a software engineer to use this repository.

In the default 90-minute workshop, you will inspect synthetic opportunity data, ask Codex to draft an opportunity intake and bid/no-bid brief, and review and revise the proposed file changes. You are building reviewable Markdown and CSV workflow assets—not software or a final bid/no-bid decision.

## A Simple Working Pattern

Use this cycle for every workflow:

**Inspect → Prompt → Review → Question → Revise**

- **Inspect:** Understand the source files and identify what is missing.
- **Prompt:** Give Codex a bounded task and a specific output format.
- **Review:** Examine each proposed file change.
- **Question:** Challenge assumptions, invented facts, weak evidence, and false certainty.
- **Revise:** Correct the draft before a qualified person decides whether it is useful.

Success means producing, checking, questioning, and revising a draft—not accepting every Codex change or completing every workflow.

## Before You Begin

1. Read [Safety and Boundaries](SAFETY-AND-BOUNDARIES.md).
2. Confirm that you will use only the synthetic files already provided.
3. Follow the workshop path selected by your facilitator:
   - [90-minute guided build](workshops/90-minute-guided-build.md)
   - [3-hour hands-on lab](workshops/3-hour-hands-on-lab.md)
4. If no path was assigned, use the default 90-minute **Opportunity Triage & Bid/No-Bid Brief** path below.

When you [review a diff](participant/reviewing-codex-diffs.md), you are reviewing the file changes Codex proposes. You do not need to know Git commands or programming to do this.

## First-Time Participant Path

For the default 90-minute workflow:

1. **Read the instructions:** Open the [90-Minute Guided Build](workshops/90-minute-guided-build.md) and [Opportunity Triage Participant Instructions](workflows/opportunity-triage/participant-instructions.md).
2. **Inspect the synthetic inputs:** Read the [Synthetic Opportunity Summary](workflows/opportunity-triage/data/synthetic-opportunity-summary.md) and [Synthetic Opportunity Input](workflows/opportunity-triage/data/synthetic-opportunity-input.csv).
3. **Review the blank output structures:** Open the [Opportunity Intake Template](workflows/opportunity-triage/templates/opportunity-intake.md) and [Bid/No-Bid Brief Template](workflows/opportunity-triage/templates/bid-no-bid-brief.md).
4. **Create the drafts:** Use the [Opportunity Triage Prompt](workflows/opportunity-triage/prompt.md).
5. **Check the result:** Compare the drafts with the [Expected Output Guide](workflows/opportunity-triage/expected-output-guide.md).
6. **Review and revise:** Use [Reviewing Codex Diffs](participant/reviewing-codex-diffs.md) and the [Human Review Checklist](participant/human-review-checklist.md).

## RFP Compliance Participant Path

When your facilitator selects **RFP Compliance Matrix & Proposal Responsibility Tracker**:

1. **Read the instructions:** Open the [RFP Workflow Overview](workflows/rfp-compliance-matrix/README.md) and [RFP Participant Instructions](workflows/rfp-compliance-matrix/participant-instructions.md).
2. **Inspect the synthetic inputs:** Read the [Synthetic RFP Excerpt](workflows/rfp-compliance-matrix/data/synthetic-rfp-excerpt.md), [Synthetic Deliverables](workflows/rfp-compliance-matrix/data/synthetic-deliverables.csv), and [Synthetic Team Roles](workflows/rfp-compliance-matrix/data/synthetic-team-roles.csv).
3. **Review the blank output structures:** Open the [Compliance Matrix Template](workflows/rfp-compliance-matrix/templates/compliance-matrix.csv) and [Responsibility Tracker Template](workflows/rfp-compliance-matrix/templates/responsibility-tracker.csv).
4. **Create the drafts:** Use the [RFP Workflow Prompt](workflows/rfp-compliance-matrix/prompt.md).
5. **Check the result:** Compare the drafts with the [RFP Expected Output Guide](workflows/rfp-compliance-matrix/expected-output-guide.md).
6. **Review and revise:** Use [Reviewing Codex Diffs](participant/reviewing-codex-diffs.md) and the [Human Review Checklist](participant/human-review-checklist.md).

## Past Performance & Teaming Participant Path

When your facilitator selects **Past Performance & Teaming Evidence Finder**:

1. **Read the instructions:** Open the [Workflow Overview](workflows/past-performance-teaming/README.md) and [Participant Instructions](workflows/past-performance-teaming/participant-instructions.md).
2. **Inspect the synthetic inputs:** Read [Target Requirements](workflows/past-performance-teaming/data/synthetic-target-requirements.csv), [Past Performance](workflows/past-performance-teaming/data/synthetic-past-performance.csv), [Staff Capabilities](workflows/past-performance-teaming/data/synthetic-staff-capabilities.csv), and [Partner Profiles](workflows/past-performance-teaming/data/synthetic-partner-profiles.csv).
3. **Review the blank output structures:** Open the [Evidence-Fit Brief Template](workflows/past-performance-teaming/templates/evidence-fit-brief.md) and [Teaming Gap Analysis Template](workflows/past-performance-teaming/templates/teaming-gap-analysis.md).
4. **Create the drafts:** Use the [Workflow Prompt](workflows/past-performance-teaming/prompt.md).
5. **Check the result:** Compare the drafts with the [Expected Output Guide](workflows/past-performance-teaming/expected-output-guide.md).
6. **Review and revise:** Use [Reviewing Codex Diffs](participant/reviewing-codex-diffs.md) and the [Human Review Checklist](participant/human-review-checklist.md).

All outputs are draft internal workflow assets. They are not authoritative and are not ready for live use without qualified human review.
