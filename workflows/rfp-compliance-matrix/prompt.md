# RFP Compliance Matrix Prompt

```text
Use only these synthetic training files:
- workflows/rfp-compliance-matrix/data/synthetic-rfp-excerpt.md
- workflows/rfp-compliance-matrix/data/synthetic-deliverables.csv
- workflows/rfp-compliance-matrix/data/synthetic-team-roles.csv
- workflows/rfp-compliance-matrix/templates/compliance-matrix.csv
- workflows/rfp-compliance-matrix/templates/responsibility-tracker.csv

The template rows labeled `EXAMPLE-ONLY` demonstrate CSV format. They are not source requirements. Do not copy them automatically into the drafts; extract requirements only from the approved synthetic data files.

Create:
- workflows/rfp-compliance-matrix/draft-compliance-matrix.csv
- workflows/rfp-compliance-matrix/draft-responsibility-tracker.csv

For the compliance matrix:
1. Create a separate row for each distinct instruction, required response, attachment, limit, deadline, or review need.
2. Quote no more source language than needed to identify the requirement.
3. Cite the exact synthetic section or attachment.
4. Distinguish explicit source requirements from analysis.
5. Use `compliance_risk` for source-based omissions, ambiguities, mismatches, or uncertainties that need human attention. Do not state a legal or compliance conclusion.
6. Do not claim that the matrix identifies every requirement.

For the responsibility tracker:
1. Use `proposed_owner_role` for the role responsible for coordinating the response item. Use `consulted_role` for a specialist who should review or provide input.
2. Propose either role only when the synthetic team-role description and RFP content support the routing.
3. Mark every owner as proposed until a person confirms it.
4. Use only dates found in the synthetic RFP. If an internal draft date is needed but not supplied, leave `due_date` blank and set `due_date_status` to `Needs human planning`.
5. Use `review_gate` for the human checkpoint needed before the task can be treated as complete.
6. Use `routing_note` for the routing reason and unanswered specialist question.
7. Route contract terms, instructions, submission conditions, exceptions, representations, flowdowns, and contractual-risk questions to `contracts_reviewer`.
8. Route legal-interpretation or legal-risk questions requiring qualified legal judgment to `legal_reviewer`.
9. Route to `devops_reviewer` only when the supplied synthetic RFP includes operational, deployment, hosting, automation, CI/CD, or environment-management evidence. Do not manufacture a DevOps task merely because the role exists.
10. Route security, technical, pricing, proposal, and other specialist questions only when the supplied inputs support that routing.
11. Do not answer specialist questions or invent approval.

Rules:
- Use no outside information.
- Do not interpret laws, clauses, security obligations, or pricing requirements.
- Do not invent requirements, dates, owners, evidence, or status.
- Preserve unknown and conflicting information.
- Treat both files as draft internal workflow aids requiring qualified human review.
- Do not repeat the general safety boundary mechanically in every CSV row. Use `human_review_note` and `routing_note` only for item-specific review needs.
- State that this work does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.
- State that the drafts may omit or misinterpret requirements and do not identify every solicitation requirement.

Before editing, summarize the approved sources and planned files. Then create the drafts.
```
