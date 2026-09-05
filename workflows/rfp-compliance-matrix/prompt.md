# RFP Compliance Matrix Prompt

```text
Use only these synthetic training files:
- workflows/rfp-compliance-matrix/data/source-packet-index.md
- workflows/rfp-compliance-matrix/data/synthetic-rfp-excerpt.md
- workflows/rfp-compliance-matrix/data/synthetic-submission-instructions.md
- workflows/rfp-compliance-matrix/data/synthetic-evaluation-factors.md
- workflows/rfp-compliance-matrix/data/synthetic-amendment-log.csv
- workflows/rfp-compliance-matrix/data/synthetic-qa-log.csv
- workflows/rfp-compliance-matrix/data/synthetic-deliverables.csv
- workflows/rfp-compliance-matrix/data/synthetic-team-roles.csv
- workflows/rfp-compliance-matrix/templates/compliance-matrix.csv
- workflows/rfp-compliance-matrix/templates/responsibility-tracker.csv

The template rows labeled `EXAMPLE-ONLY` demonstrate CSV format. They are not source requirements. Do not copy them automatically into the drafts; extract requirements only from the approved synthetic data files.

This is a guided first-time practice exercise. When the user asks to start or asks for help getting started, begin with a short, welcoming orientation before reading or creating files. Explain in plain language:

- this practice uses a fictional RFP packet, so the learner can safely see how the workflow works;
- a compliance matrix is a working list of the RFP's stated instructions and where each came from;
- a responsibility tracker is a separate working list that proposes which role should coordinate each item and who should review it;
- Codex will first introduce the supplied packet and the two planned drafts, then create them only after the learner approves.

Do not imply that the learner should already know RFP compliance terminology, CSV files, or the repository structure. Do not open with a completion statement or a list of created files.

For a request to "help me get started," do not create, edit, replace, or overwrite draft files. Give a self-contained orientation, name the two files that would be created, state that no files have been created yet, and ask: "Would you like me to create these two practice drafts now?" Then stop and wait for an explicit affirmative answer in the chat. Starting the workflow, opening this prompt, or an available approval control does not itself authorize file creation. If either target file already exists, show its name and ask for explicit permission before replacing it.

For a request to "walk me through" this workflow, use a read-only teaching conversation. Do not create, edit, replace, or overwrite files, and do not ask for draft-creation approval unless I explicitly change the request to creating drafts.

Start with the outcome, not a repository path or file list: explain that this fictional exercise turns scattered RFP instructions into two simple working lists, one for what the RFP asks for and one for proposed coordination and review handoffs. State that no files have been created. In the first reply, guide me through only the first of three short stages:

1. See the job: RFP instructions can appear in more than one place, so the goal is to make each instruction easy to find and discuss.
2. Turn an instruction into a checkable item: when one statement asks for two distinct things, make two separate items and point each back to its source.
3. Keep questions visible: when information changes, is unclear, or needs specialist input, record that rather than guessing.

Use one ordinary example, such as: "If the packet asks for a discovery approach and a workshop plan, those are two separate things to track." Then invite me to continue to the next stage. Do not lead with repository paths, a list of source files, output filenames, row IDs, amendment IDs, or specialist role names. Introduce those details only when they are useful in a later stage.

Create:
- workflows/rfp-compliance-matrix/outputs/draft-compliance-matrix.csv
- workflows/rfp-compliance-matrix/outputs/draft-responsibility-tracker.csv

For the compliance matrix:
1. Create a separate row for each distinct instruction, required response, attachment, limit, deadline, or review need.
2. Quote no more source language than needed to identify the requirement.
3. Cite the exact synthetic section or attachment.
4. Reflect amendment impacts when the source packet shows that a requirement changed.
5. Distinguish explicit source requirements from analysis.
6. Use `compliance_risk` for source-based omissions, ambiguities, mismatches, or uncertainties that need human attention. Do not state a legal or compliance conclusion.
7. Do not claim that the matrix identifies every requirement.

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
- Do not provide legal interpretation, automated compliance certification, or a final proposal review.
- Do not invent requirements, dates, owners, evidence, or status.
- Preserve unknown, amended, unanswered, partial, and conflicting information.
- Treat both files as draft internal workflow aids requiring qualified human review.
- Do not repeat the general safety boundary mechanically in every CSV row. Use `human_review_note` and `routing_note` only for item-specific review needs.
- State that this work does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.
- State that the drafts may omit or misinterpret requirements and do not identify every solicitation requirement.

After the learner explicitly approves creating the drafts, summarize the approved sources and planned files, and say what you will look for first: stated instructions, amendments, unanswered questions, and review handoffs. Then create the drafts.

After creating the drafts, explain what the learner has just practiced. Name the two files in plain language, choose two or three beginner-friendly rows, and explain why they are useful examples. Invite one small review action, such as opening a named row and checking its source reference. Keep the boundary note short and place it after the orientation: the drafts are practice aids for qualified human review, not a determination that a response is complete or compliant.
```
