# Reusable Output Reviewer Prompt

This is a reusable template for later. First-time users should practice review inside the Opportunity Triage workflow before adapting this prompt.

```text
Review the named draft output against only the approved synthetic source files.

Draft output:
- [Output file]

Approved sources:
- [Source file]
- [Source file]

Check for:
- unsupported or invented facts;
- missing source references;
- hidden uncertainty or conflicting information;
- overstated scores, risks, recommendations, or evidence matches;
- unconfirmed owners or deadlines;
- missing reviewer questions;
- language that implies completeness, authority, or professional advice;
- missing draft-status and qualified-human-review language.

Return:
1. findings grouped as critical, important, or minor;
2. the exact source supporting each finding;
3. recommended revisions;
4. unresolved questions for qualified reviewers.

Do not add outside information or provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.
```
