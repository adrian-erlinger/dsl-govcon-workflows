# Past Performance and Teaming Prompt

```text
Use only these synthetic training files:
- workflows/past-performance-teaming/data/source-packet-index.md
- workflows/past-performance-teaming/data/synthetic-opportunity-context.md
- workflows/past-performance-teaming/data/synthetic-target-requirements.csv
- workflows/past-performance-teaming/data/synthetic-evidence-inventory.csv
- workflows/past-performance-teaming/data/synthetic-past-performance.csv
- workflows/past-performance-teaming/data/synthetic-staff-capabilities.csv
- workflows/past-performance-teaming/data/synthetic-workstream-capacity.csv
- workflows/past-performance-teaming/data/synthetic-partner-profiles.csv
- workflows/past-performance-teaming/data/synthetic-diligence-questions.csv
- workflows/past-performance-teaming/templates/evidence-fit-brief.md
- workflows/past-performance-teaming/templates/teaming-gap-analysis.md

This is a guided first-time practice exercise. When the user asks to start or asks for help getting started, begin with a short, welcoming orientation before reading or creating files. Explain in plain language:

- this practice uses a fictional opportunity and fictional company records, so the learner can safely see how evidence matching works;
- the evidence-fit brief compares each opportunity need with the records that may or may not support it;
- the teaming-gap analysis makes visible what the fictional company may need help with and what a potential partner would still need to prove;
- Codex will first introduce the supplied records and the two planned drafts, then create them only after the learner approves.

Do not imply that the learner should already know past-performance, teaming, capture, or evidence-rating terminology, or the repository structure. Do not open with a completion statement or a list of created files.

For a request to "help me get started," do not create, edit, replace, or overwrite draft files. Give a self-contained orientation, name the two files that would be created, state that no files have been created yet, and ask: "Would you like me to create these two practice drafts now?" Then stop and wait for an explicit affirmative answer in the chat. Starting the workflow, opening this prompt, or an available approval control does not itself authorize file creation. If either target file already exists, show its name and ask for explicit permission before replacing it.

Create:
- workflows/past-performance-teaming/outputs/draft-evidence-fit-brief.md
- workflows/past-performance-teaming/outputs/draft-teaming-gap-analysis.md

Evidence ratings:
- strong = the supplied synthetic record directly supports the target requirement;
- partial = the supplied record is relevant, but a threshold, method, scale, recency, capacity, outcome, or confirmation is missing;
- unsupported = available records do not support the claim;
- unknown = the supplied data does not allow a determination.

Use only these four ratings. A strong rating does not establish qualification or guarantee acceptability to a customer, prime, or agency.

Terms:
- best fit = the record best supported by the supplied synthetic evidence, not an externally validated or guaranteed acceptable example;
- material gap = missing or insufficient evidence important to a target requirement;
- desired partner evidence = specific evidence a potential partner would need to provide to help address a material gap;
- diligence questions = questions qualified reviewers must resolve before relying on a record, capability, or potential partner.

For each target requirement:
1. Identify candidate past performance, staff, or partner evidence.
2. Rate the evidence as strong, partial, unsupported, or unknown.
3. Cite the exact synthetic record ID.
4. Explain both the match and its limitation.
5. Do not combine separate records into a stronger claim than they support.
6. Use diligence questions when evidence, availability, qualifications, buyer acceptance, or partner commitment is unresolved.

Multiple records may be cited together only when their contributions remain separate. For example, `PP-02` supports remote workshop delivery and `ST-02` supports remote facilitation experience, but together they do not prove hybrid delivery for 100 learners.

The evidence-fit brief must include:
- a requirement-to-evidence table;
- the best-fit past performance examples and why;
- material evidence gaps;
- questions for the capture lead.

The teaming-gap analysis must include:
- gaps that might require a partner;
- capabilities that may be supportable internally;
- a preliminary desired partner profile;
- relevant synthetic partner candidates without selecting or endorsing one;
- diligence questions and information still needed.

Rules:
- Use no outside information.
- Do not invent past performance, experience, outcomes, contract values, certifications, staff qualifications, staff availability, customer facts, customer approval, partner experience, or partner commitments.
- Distinguish evidence from inference.
- Do not turn gaps into claims.
- Preserve evidence limits, missing acceptance records, capacity constraints, and exploratory partner status.
- Do not determine qualification, eligibility, acceptability, or final partner selection.
- State that both outputs, including any teaming recommendation, are draft internal planning aids requiring qualified human review.
- Do not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.

After the learner explicitly approves creating the drafts, summarize the approved sources and planned files, and say what you will look for first: direct evidence, evidence limits, capacity constraints, and unconfirmed partner information. Then create the drafts.

After creating the drafts, explain what the learner has just practiced. Name the two files in plain language, choose two or three beginner-friendly examples, and explain why the evidence is strong, partial, unsupported, or unknown. Point out that a relevant potential partner is not a commitment. Invite one small review action, such as tracing a finding back to a cited record ID. Keep the boundary note short and place it after the orientation: the drafts are practice aids for qualified human review, not a determination that the company is qualified or that a partner has been selected.
```
