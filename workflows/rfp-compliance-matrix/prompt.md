# RFP Compliance Matrix Prompt

```text
Use only these synthetic training files:
- workflows/rfp-compliance-matrix/data/synthetic-rfp-excerpt.md
- workflows/rfp-compliance-matrix/data/synthetic-deliverables.csv
- workflows/rfp-compliance-matrix/data/synthetic-team-roles.csv
- workflows/rfp-compliance-matrix/templates/compliance-matrix.csv
- workflows/rfp-compliance-matrix/templates/responsibility-tracker.csv

Create:
- workflows/rfp-compliance-matrix/draft-compliance-matrix.csv
- workflows/rfp-compliance-matrix/draft-responsibility-tracker.csv

For the compliance matrix:
1. Create a separate row for each distinct instruction, required response, attachment, limit, deadline, or review need.
2. Quote no more source language than needed to identify the requirement.
3. Cite the exact synthetic section or attachment.
4. Distinguish explicit source requirements from analysis.
5. Mark ambiguous items and explain the ambiguity.
6. Do not claim that the matrix identifies every requirement.

For the responsibility tracker:
1. Propose an owner role only when a role description supports the routing.
2. Mark every owner as proposed until a person confirms it.
3. Include internal draft dates only when the training data supplies them or label them for confirmation.
4. Route specialist questions to roles such as contracts, legal review, DevOps, security, technical subject-matter expert, pricing, or proposal lead as appropriate.
5. Do not answer specialist questions or invent approval.

Rules:
- Use no outside information.
- Do not interpret laws, clauses, security obligations, or pricing requirements.
- Do not invent requirements, dates, owners, evidence, or status.
- Preserve unknown and conflicting information.
- State in routing notes that the files are draft internal workflow aids requiring qualified human review.
- State that this work does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.

Before editing, summarize the approved sources and planned files. Then create the drafts.
```

