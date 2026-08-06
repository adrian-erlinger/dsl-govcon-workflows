# Reusable Workflow Builder Prompt

This is a template for later, after you have tried the Opportunity Triage workflow. It is not the first prompt to use.

If you are new, start with `START-HERE.md` and use the prompt inside `workflows/opportunity-triage/prompt.md`. You do not need to invent your own workflow idea to begin.

When you are ready to adapt the pattern, replace the bracketed text below with your own approved synthetic files and desired draft output.

```text
Create a draft internal workflow aid using only the approved synthetic input files I name below.

Purpose:
[In plain language, describe what the draft should help organize or review. Example: "Help review whether a synthetic opportunity is worth further capture discussion."]

Approved inputs:
- [Input file]
- [Input file]

Required output:
- File: [Output file]
- Format: [Markdown or CSV]
- Required sections or columns: [List them]

Rules:
1. Do not use outside information.
2. Do not invent facts, requirements, evidence, owners, or deadlines.
3. Label missing or conflicting information as unknown.
4. Cite the source file and field or section for material findings.
5. Separate source facts from analysis.
6. Explain the reasoning behind scores, risks, matches, or recommendations.
7. Add questions for a qualified human reviewer.
8. State that the result is a draft internal workflow aid requiring qualified human review.
9. Do not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.

Before editing, summarize the inputs and planned output. Then make the requested file changes.
```
