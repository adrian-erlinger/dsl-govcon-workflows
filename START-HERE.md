# Start Here

Welcome. You do not need to be a software engineer to use this repository.

The default 90-minute workflow is **Opportunity Triage & Bid/No-Bid Brief**.

## Before You Begin

1. Read [Safety and Boundaries](SAFETY-AND-BOUNDARIES.md).
2. Confirm that you will use only the synthetic files already provided.
3. Choose the workshop path your facilitator identifies:
   - [90-minute guided build](workshops/90-minute-guided-build.md)
   - [3-hour hands-on lab](workshops/3-hour-hands-on-lab.md)
4. Open the selected workflow's `participant-instructions.md`.
5. Read the inputs before using the prompt.
6. Ask Codex to create or update the output files.
7. Review the changes using [Reviewing Codex Diffs](participant/reviewing-codex-diffs.md).
8. Apply the [Human Review Checklist](participant/human-review-checklist.md).

## First-Time Participant Path

For the default 90-minute workflow, open these files in order:

1. [90-Minute Guided Build](workshops/90-minute-guided-build.md)
2. [Opportunity Triage Participant Instructions](workflows/opportunity-triage/participant-instructions.md)
3. [Synthetic Opportunity Summary](workflows/opportunity-triage/data/synthetic-opportunity-summary.md)
4. [Synthetic Opportunity Input](workflows/opportunity-triage/data/synthetic-opportunity-input.csv)
5. [Opportunity Intake Template](workflows/opportunity-triage/templates/opportunity-intake.md)
6. [Bid/No-Bid Brief Template](workflows/opportunity-triage/templates/bid-no-bid-brief.md)
7. [Opportunity Triage Prompt](workflows/opportunity-triage/prompt.md)
8. [Expected Output Guide](workflows/opportunity-triage/expected-output-guide.md)
9. [Reviewing Codex Diffs](participant/reviewing-codex-diffs.md)
10. [Human Review Checklist](participant/human-review-checklist.md)

## Past Performance & Teaming Participant Path

When your facilitator selects **Past Performance & Teaming Evidence Finder**, open these files in order:

1. [Workflow Overview](workflows/past-performance-teaming/README.md)
2. [Participant Instructions](workflows/past-performance-teaming/participant-instructions.md)
3. [Target Requirements](workflows/past-performance-teaming/data/synthetic-target-requirements.csv)
4. [Past Performance](workflows/past-performance-teaming/data/synthetic-past-performance.csv)
5. [Staff Capabilities](workflows/past-performance-teaming/data/synthetic-staff-capabilities.csv)
6. [Partner Profiles](workflows/past-performance-teaming/data/synthetic-partner-profiles.csv)
7. [Evidence-Fit Brief Template](workflows/past-performance-teaming/templates/evidence-fit-brief.md)
8. [Teaming Gap Analysis Template](workflows/past-performance-teaming/templates/teaming-gap-analysis.md)
9. [Workflow Prompt](workflows/past-performance-teaming/prompt.md)
10. [Expected Output Guide](workflows/past-performance-teaming/expected-output-guide.md)
11. [Reviewing Codex Diffs](participant/reviewing-codex-diffs.md)
12. [Human Review Checklist](participant/human-review-checklist.md)

## A Simple Working Pattern

Use this cycle for every workflow:

**Inspect → Prompt → Review → Question → Revise**

- **Inspect:** Understand the source files and identify what is missing.
- **Prompt:** Give Codex a bounded task and a specific output format.
- **Review:** Examine each proposed file change.
- **Question:** Challenge assumptions, invented facts, weak evidence, and false certainty.
- **Revise:** Correct the draft before a qualified person decides whether it is useful.

All outputs are draft internal workflow aids. They are not authoritative and are not ready for live use without qualified human review.
