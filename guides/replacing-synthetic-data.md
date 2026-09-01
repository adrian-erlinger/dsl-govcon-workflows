# Replacing Synthetic Data

This guide explains how the synthetic workflow files map to real organizational materials later. Do not replace the training files with live data in this repository.

The workshop sequence is:

1. use the supplied synthetic case;
2. understand the workflow pattern;
3. recognize the equivalent approved documents inside your organization;
4. apply the method only in an approved environment with the right data, access, confidentiality, and human-review controls.

For the broader bridge from synthetic practice to real workflows and custom workflow design, read [After The Basics](after-the-basics.md).

## Why The Synthetic Packet Exists

The synthetic files remove the blank-page problem. They let first-time users open the repository, inspect realistic source material, use Plan mode, run the workflow, and review Codex changes without preparing any data first.

The packet also teaches that useful Codex workflows depend on organized context. The prompt matters, but the source files are what let Codex separate known facts, partial evidence, unknowns, conflicts, caveats, and reviewer questions.

## Opportunity Triage Substitution Map

| Training file | Organizational equivalent later |
|---|---|
| `workflows/opportunity-triage/data/synthetic-opportunity-notice.md` | Approved opportunity notice, market research notice, sources-sought notice, solicitation excerpt, or capture-approved opportunity materials |
| `workflows/opportunity-triage/data/synthetic-opportunity-summary.md` | Internal capture summary or facilitator-created case overview based on approved materials |
| `workflows/opportunity-triage/data/synthetic-opportunity-input.csv` | Structured opportunity facts from an approved CRM, intake form, pipeline record, or capture worksheet |
| `workflows/opportunity-triage/data/synthetic-review-criteria.md` | Approved evaluation criteria, review factors, gate criteria, or known decision criteria |
| `workflows/opportunity-triage/data/synthetic-customer-context.md` | Approved capture notes, customer context, account plan excerpts, or customer intelligence cleared for use |
| `workflows/opportunity-triage/data/synthetic-capability-statement.md` | Current approved capability statement or approved solution-area summary |
| `workflows/opportunity-triage/data/synthetic-past-performance-snapshots.csv` | Approved past-performance library, vetted project summaries, or reusable qualification records |
| `workflows/opportunity-triage/data/synthetic-delivery-capacity.csv` | Approved staffing plan, delivery-capacity view, resource forecast, or gate-readiness notes |
| `workflows/opportunity-triage/data/synthetic-staffing-and-partner-notes.csv` | Approved staffing, delivery-capacity, partner-readiness, or gate-review notes |
| `workflows/opportunity-triage/templates/opportunity-intake.md` | Organization-approved opportunity intake worksheet format |
| `workflows/opportunity-triage/templates/bid-no-bid-brief.md` | Organization-approved bid/no-bid briefing format or gate-review memo format |

## What To Preserve When Adapting

- Use approved source files, not memory or informal claims.
- Keep source facts separate from analysis.
- Mark unknown information as unknown instead of treating it as negative evidence.
- Preserve conflicting source notes instead of forcing agreement too early.
- Route questions to reviewer roles, not invented people.
- Require qualified human review before any live pursuit decision.

## What Not To Bring Into This Repository

Do not add real opportunity materials, proprietary past performance, pricing, customer intelligence, personnel information, controlled data, credentials, secrets, or confidential client material to this training repository.

Once you understand the workflow, recreate the pattern in an approved workspace using your organization's approved documents and review process.

## RFP Compliance Matrix Substitution Map

Use this map only after completing the synthetic exercise and only in an approved environment.

| Training file | Organizational equivalent later |
|---|---|
| `workflows/rfp-compliance-matrix/data/synthetic-rfp-excerpt.md` | Approved solicitation excerpt, RFP section set, or proposal instruction packet |
| `workflows/rfp-compliance-matrix/data/synthetic-submission-instructions.md` | Approved submission instructions, portal guidance, file-naming rules, or proposal operations checklist |
| `workflows/rfp-compliance-matrix/data/synthetic-evaluation-factors.md` | Approved Section M, evaluation criteria, review factors, or capture evaluation notes |
| `workflows/rfp-compliance-matrix/data/synthetic-amendment-log.csv` | Approved amendment tracker or solicitation change log |
| `workflows/rfp-compliance-matrix/data/synthetic-qa-log.csv` | Approved Q&A log, bidder questions tracker, or customer-response tracker |
| `workflows/rfp-compliance-matrix/data/synthetic-deliverables.csv` | Approved deliverables list, compliance outline, or response-volume inventory |
| `workflows/rfp-compliance-matrix/data/synthetic-team-roles.csv` | Approved proposal responsibility model, review-role map, or response team roster by role |

## Past Performance And Teaming Substitution Map

Use this map only after completing the synthetic exercise and only in an approved environment.

| Training file | Organizational equivalent later |
|---|---|
| `workflows/past-performance-teaming/data/synthetic-opportunity-context.md` | Approved capture context, opportunity summary, or target scope notes |
| `workflows/past-performance-teaming/data/synthetic-target-requirements.csv` | Approved requirement list, qualification target, evaluation themes, or teaming-needs worksheet |
| `workflows/past-performance-teaming/data/synthetic-evidence-inventory.csv` | Approved evidence inventory, artifact index, proof-point tracker, or reusable content index |
| `workflows/past-performance-teaming/data/synthetic-past-performance.csv` | Approved past-performance library or vetted project summaries |
| `workflows/past-performance-teaming/data/synthetic-staff-capabilities.csv` | Approved staff capability matrix, resume inventory, or availability record |
| `workflows/past-performance-teaming/data/synthetic-workstream-capacity.csv` | Approved capacity plan, delivery-readiness view, or staffing gap tracker |
| `workflows/past-performance-teaming/data/synthetic-partner-profiles.csv` | Approved partner landscape, teaming database, partner profiles, or vetted capability notes |
| `workflows/past-performance-teaming/data/synthetic-diligence-questions.csv` | Approved diligence tracker, teaming questions log, or capture review questions |
