# Instructions: Past Performance and Teaming

## Goal

Match synthetic evidence to synthetic opportunity requirements without overstating what the evidence proves.

## What You Will See

This exercise starts with a fictional opportunity and fictional company records. Codex turns those records into two working documents so you can see how a team compares evidence with an opportunity:

- The **evidence-fit brief** connects each opportunity need to the records that may support it, while preserving the limits of each record.
- The **teaming-gap analysis** shows where additional capability or evidence may be needed and what a potential partner would still need to confirm.

You are not expected to know the evidence ratings or inspect every record at once. Start by tracing one finding back to its record ID, then notice why a relevant example can still be only a partial match.

## Synthetic Input Guide

- `synthetic-target-requirements.csv`: the fictional opportunity targets and expected evidence.
- `synthetic-opportunity-context.md`: fictional scenario, target scope, and capture concerns.
- `synthetic-evidence-inventory.csv`: available evidence artifacts and their limits.
- `synthetic-past-performance.csv`: fictional prior projects, documented outcomes, and evidence limits.
- `synthetic-staff-capabilities.csv`: fictional staff experience, availability, and qualification limits.
- `synthetic-workstream-capacity.csv`: fictional internal capacity view for simultaneous workstreams.
- `synthetic-partner-profiles.csv`: fictional potential-partner capabilities, evidence, interest, and limitations.
- `synthetic-diligence-questions.csv`: open reviewer questions tied to requirements and records.

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

1. Read `data/source-packet-index.md` to see the approved synthetic files.
2. Read the opportunity context and target requirements in `data/`.
3. Inspect the evidence inventory, past performance, staff capabilities, workstream capacity, partner profiles, and diligence questions.
4. Rate candidate evidence as strong, partial, unsupported, or unknown using the definitions above.
5. Review the output structures in `templates/`.
6. Copy the prompt from `prompt.md` into Codex. It will introduce the two planned files, then ask for your approval before creating them in `outputs/`.
7. Inspect the diff and trace every match to a record ID.
8. Compare both drafts with `expected-output-guide.md`.
9. Find at least one match that Codex may have overstated.
10. Revise the draft and apply the human-review checklist.

Multiple records may be cited together when their contributions remain separate. For example, `PP-02` supports remote workshop delivery and `ST-02` supports remote facilitation experience, but together they still do not prove delivery of hybrid workshops for 100 learners.

## Success Standard

The draft should help a capture team ask better questions. It must not invent past performance, certifications, staff qualifications, partner commitments, contract values, outcomes, customer approval, or availability. It should never turn an evidence gap into a claim.

Both output files, including any teaming recommendation, are draft internal planning aids requiring qualified human review. This training does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.
