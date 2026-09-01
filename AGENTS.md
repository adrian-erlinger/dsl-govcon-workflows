# AGENTS.md

## Project Purpose

This is a GovCon training repository for Codex. It teaches non-technical and technical users how to create reviewable internal workflow aids from organized source files. The repository includes synthetic source files so first-time users can practice immediately.

This is not a software application. Do not add application code, package dependencies, live integrations, automated submissions, external connections, or production systems unless the user explicitly asks for a new direction.

## Core Training Boundary

Default to the included synthetic training data for first-time practice, demos, and self-guided exercises.

If the user explicitly wants to apply a workflow to real organizational data, do not block them merely because the data is real. Confirm that they intend to use approved source materials in an appropriate workspace, then adapt the workflow to the files they identify. Do not use material they are not authorized to use, and do not introduce personally identifiable information, credentials, secrets, controlled information, confidential material, or proprietary material unless the user has made clear that the workspace and use are approved for that data.

Do not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice. The repository teaches draft workflow structure, source traceability, review questions, and human-review discipline.

## Workflow Priority

The canonical first workflow is:

- `workflows/opportunity-triage/`

The additional example workflows are:

- `workflows/rfp-compliance-matrix/`
- `workflows/past-performance-teaming/`

For first-time users, route them to:

1. `START-HERE.md`
2. `FIRST-RUN-PROMPT.md`
3. `workflows/opportunity-triage/README.md`

## Output Style

Prefer Markdown and CSV outputs. Keep files readable for non-technical reviewers.

When drafting workflow outputs:

- cite supplied source files, rows, fields, or sections, whether synthetic or approved organizational sources;
- separate source facts from analysis;
- preserve known, partial, unknown, missing, weak, and conflicting information;
- route unanswered questions to reviewer roles rather than invented people;
- state that outputs are draft internal workflow aids requiring qualified human review.

## Human Decision Boundaries

Do not let Codex outputs imply final decisions.

- Opportunity Triage: scores are discussion aids, not mathematical rules or final bid/no-bid decisions.
- RFP Compliance: matrices and trackers may omit or misinterpret requirements and do not certify compliance.
- Past Performance and Teaming: evidence gaps must not become claims, and partner interest must not become partner commitment.

Qualified people remain responsible for pursuit, proposal, compliance, pricing, security, capture, teaming, and leadership decisions.

## Editing Guidance

Keep changes simple and workshop-friendly. Favor clear file names, short instructions, source packet indexes, reusable prompts, templates, and expected-output guides.

Do not create completed draft outputs unless the user is intentionally running a workflow exercise. In ordinary repo-maintenance work, preserve templates and source data rather than filling in exercise outputs.

Before broad restructuring, check whether the change would make the repository easier or harder for a first-time user to open and try.
