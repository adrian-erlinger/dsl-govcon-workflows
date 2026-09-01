# After The Basics

After you complete the synthetic Opportunity Triage workflow, the next goal is transfer. You should be able to recognize how the pattern applies to your real work when your organization has approved source materials ready.

There are two next paths:

1. replace synthetic data with approved organizational data in a governed workspace;
2. design your own GovCon workflow for Codex.

## Path A: Replace Synthetic Data Later

Use the synthetic workflow first. Then identify the approved organizational equivalents for each training file.

Start with [Replacing Synthetic Data](replacing-synthetic-data.md). That guide maps training files to likely organizational equivalents, such as:

- approved opportunity notices;
- approved capability statements;
- approved past-performance records;
- approved capture or customer context;
- approved review criteria;
- approved delivery-capacity or staffing information.

You may apply the workflow to real organizational data when the data and workspace are approved for that use. The key is not whether the file is synthetic or real; the key is whether the source material is authorized, appropriate for the workspace, and subject to the right data protections, access controls, confidentiality rules, and human-review process.

Before using real data, a qualified person should confirm:

- which source files are approved for use;
- who may access the workspace;
- what information is confidential, controlled, proprietary, or otherwise sensitive;
- what outputs may be saved, shared, or reused;
- which roles must review the draft before anyone relies on it.

## Path B: Build Your Own GovCon Workflow

A good Codex workflow starts with a repeatable work problem, not a clever prompt.

Look for a workflow where your team already needs to:

- organize scattered source information;
- compare requirements against evidence;
- create a first-pass brief, matrix, checklist, tracker, or question list;
- preserve unknowns, conflicts, and weak evidence;
- route issues to qualified reviewers;
- review a draft before using it.

Good early candidates include:

- opportunity intake;
- capture question log;
- proposal responsibility tracker;
- past-performance evidence finder;
- teaming-gap review;
- amendment impact tracker;
- draft review checklist;
- meeting-notes-to-action-items workflow.

Avoid first workflows that require live integrations, automated submissions, legal conclusions, pricing decisions, cybersecurity determinations, or final procurement judgments.

## Design Checklist

When creating your own workflow, define:

| Design item | Question to answer |
|---|---|
| Purpose | What decision, discussion, or review will the draft support? |
| Audience | Who will use or review the output? |
| Approved inputs | What source files may Codex use? |
| Output format | Should the result be Markdown, CSV, or both? |
| Required sections or columns | What does the reviewer need to see? |
| Reviewer roles | Who should review unanswered questions or weak evidence? |
| Boundaries | What must Codex not decide, certify, invent, or infer? |
| Expected-output guide | How will a human know whether the draft is useful? |

## Coaching Prompt

Use [Workflow Coach Prompt](../prompts/workflow-coach.md) when you are ready to ask Codex to help you design a new GovCon workflow.

Use [Reusable Workflow Builder Prompt](../prompts/workflow-builder.md) when you already know the purpose, inputs, and output format.

Use [Reusable Workflow Adapter Prompt](../prompts/workflow-adapter.md) when you want to modify one of the existing synthetic workflows while preserving the training boundaries.

## Reusable Skills

The `skills/` folder contains reusable Codex Skill blueprints for the three training workflows:

- `skills/opportunity-triage/SKILL.md`
- `skills/rfp-compliance-matrix/SKILL.md`
- `skills/past-performance-teaming/SKILL.md`

These files package the same workflow patterns into reusable, task-specific instructions. They are useful after participants understand the basic flow and want to see how a repeatable GovCon workflow can become a Codex Skill.

First-time users should still begin with `START-HERE.md` and `FIRST-RUN-PROMPT.md`.

## The Pattern To Preserve

Whether you are replacing synthetic data or designing a new workflow, keep the same core pattern:

**Source packet -> bounded prompt -> draft output -> diff review -> human questions -> revision**

Codex can help structure work faster. It should not replace the people responsible for judgment, approval, compliance, pricing, security, capture, proposal, or teaming decisions.
