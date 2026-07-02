# Past Performance and Teaming Evidence Finder

## Audience

Small businesses, capture leads, teaming leads, and growth teams preparing for larger opportunities.

## Practical Need

Teams may struggle to compare prior work, staff capabilities, and potential partner evidence with a new opportunity. This workflow makes candidate evidence and gaps visible.

## Draft Outputs

- best-fit synthetic past performance examples;
- requirement-by-requirement evidence assessment;
- evidence and capability gaps;
- preliminary teaming needs;
- a desired partner profile;
- questions for the capture lead.

This workflow does not determine qualification, eligibility, acceptability, or partner selection. The output is a draft internal workflow aid requiring qualified human review.

## Synthetic Inputs

- [Target Requirements](data/synthetic-target-requirements.csv): what the fictional opportunity expects and what evidence would support each requirement.
- [Past Performance](data/synthetic-past-performance.csv): fictional prior-project records, documented outcomes, and evidence limits.
- [Staff Capabilities](data/synthetic-staff-capabilities.csv): fictional staff experience, availability status, and qualification limits.
- [Partner Profiles](data/synthetic-partner-profiles.csv): fictional potential-partner capabilities, evidence, interest, and limitations.

## Participant Path

1. Open [Participant Instructions](participant-instructions.md).
2. Inspect the four synthetic CSV files described above.
3. Review the [Evidence-Fit Brief Template](templates/evidence-fit-brief.md) and [Teaming Gap Analysis Template](templates/teaming-gap-analysis.md).
4. Use [prompt.md](prompt.md). It already tells Codex which draft files to create.
5. After generation, compare both drafts with the [Expected Output Guide](expected-output-guide.md).

Both outputs are draft internal planning aids requiring qualified human review.
