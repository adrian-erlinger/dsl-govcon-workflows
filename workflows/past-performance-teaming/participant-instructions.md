# Participant Instructions: Past Performance and Teaming

## Goal

Match synthetic evidence to synthetic opportunity requirements without overstating what the evidence proves.

## Synthetic Input Guide

- `synthetic-target-requirements.csv`: the fictional opportunity targets and expected evidence.
- `synthetic-past-performance.csv`: fictional prior projects, documented outcomes, and evidence limits.
- `synthetic-staff-capabilities.csv`: fictional staff experience, availability, and qualification limits.
- `synthetic-partner-profiles.csv`: fictional potential-partner capabilities, evidence, interest, and limitations.

## Evidence Ratings

- **Strong:** The supplied synthetic record directly supports the target requirement.
- **Partial:** The supplied record is relevant, but a threshold, method, scale, recency, capacity, outcome, or confirmation is missing.
- **Unsupported:** Available records do not support the claim.
- **Unknown:** The supplied data does not allow a determination.

Use only these four ratings. A strong rating does not establish qualification or guarantee acceptability to a customer, prime, or agency.

## Beginner Terms

- **Best fit:** The record best supported by the supplied synthetic evidence—not an externally validated or guaranteed acceptable example.
- **Material gap:** Missing or insufficient evidence important to a target requirement.
- **Desired partner evidence:** Specific evidence a potential partner would need to provide to help address a material gap.
- **Diligence questions:** Questions qualified reviewers must resolve before relying on a record, capability, or potential partner.

## Steps

1. Read the target requirements, past performance, staff capabilities, and partner profiles in `data/`.
2. Rate candidate evidence as strong, partial, unsupported, or unknown using the definitions above.
3. Review the output structures in `templates/`.
4. Copy the prompt from `prompt.md` into Codex. The prompt already tells Codex to create both draft files.
5. Inspect the diff and trace every match to a CSV record ID.
6. Compare both drafts with `expected-output-guide.md`.
7. Find at least one match that Codex may have overstated.
8. Revise the draft and apply the participant human-review checklist.

Multiple records may be cited together when their contributions remain separate. For example, `PP-02` supports remote workshop delivery and `ST-02` supports remote facilitation experience, but together they still do not prove delivery of hybrid workshops for 100 learners.

## Success Standard

The draft should help a capture team ask better questions. It must not invent past performance, certifications, staff qualifications, partner commitments, contract values, outcomes, customer approval, or availability.

Both output files, including any teaming recommendation, are draft internal planning aids requiring qualified human review. This training does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.
