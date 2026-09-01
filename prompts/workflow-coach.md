# Workflow Coach Prompt

Use this after you have completed the Opportunity Triage workflow and want Codex to help you design a new GovCon workflow.

This prompt is for planning and coaching first. It should not create or modify workflow files until you explicitly ask for edits.

```text
I have completed the synthetic Opportunity Triage workflow and want to design a new GovCon workflow for Codex.

Please coach me through the workflow design before writing any files.

The workflow idea is:
[Describe the workflow you want to create.]

Intended users:
[Name the people or roles who would use it.]

The draft output should help them:
[Describe the discussion, review, or decision the output should support.]

Known source files or source types:
[List the approved synthetic files, sample files, or approved organizational source types you expect to use. Use real data only when your organization has approved the data, workspace, access, and review process.]

Please help me define:
1. the purpose of the workflow;
2. the approved input files or synthetic files it would need;
3. the output files it should create;
4. the sections or columns those outputs should contain;
5. the reviewer roles that should receive unanswered questions;
6. the boundaries: what Codex must not decide, certify, infer, or invent;
7. a small synthetic test case that would make the workflow safe to practice;
8. an expected-output guide so humans know how to review the draft.

Keep the workflow Markdown-first and CSV-first unless there is a strong reason not to.

Do not create applications, live integrations, automated submissions, external connections, or production systems.

Do not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.

Do not write or edit files yet. First ask me any necessary design questions and propose a simple workflow outline.
```
