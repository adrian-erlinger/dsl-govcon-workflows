# Past Performance and Teaming Prompt

```text
Use only these synthetic training files:
- workflows/past-performance-teaming/data/synthetic-target-requirements.csv
- workflows/past-performance-teaming/data/synthetic-past-performance.csv
- workflows/past-performance-teaming/data/synthetic-staff-capabilities.csv
- workflows/past-performance-teaming/data/synthetic-partner-profiles.csv
- workflows/past-performance-teaming/templates/evidence-fit-brief.md
- workflows/past-performance-teaming/templates/teaming-gap-analysis.md

Create:
- workflows/past-performance-teaming/draft-evidence-fit-brief.md
- workflows/past-performance-teaming/draft-teaming-gap-analysis.md

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
- Do not determine qualification, eligibility, acceptability, or final partner selection.
- State that both outputs, including any teaming recommendation, are draft internal planning aids requiring qualified human review.
- Do not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.

Before editing, summarize the approved sources and planned files. Then create the drafts.
```
