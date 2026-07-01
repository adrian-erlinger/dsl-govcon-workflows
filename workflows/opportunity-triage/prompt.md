# Opportunity Triage Prompt

```text
Create a draft opportunity intake worksheet and bid/no-bid briefing aid using only:
- workflows/opportunity-triage/data/synthetic-opportunity-summary.md
- workflows/opportunity-triage/data/synthetic-opportunity-input.csv
- workflows/opportunity-triage/templates/opportunity-intake.md
- workflows/opportunity-triage/templates/bid-no-bid-brief.md

Create:
- workflows/opportunity-triage/draft-opportunity-intake.md
- workflows/opportunity-triage/draft-bid-no-bid-brief.md

Scoring:
- Score customer fit, capability fit, past performance fit, delivery readiness, and partner readiness from 0 to 2.
- Explain each score using a named source field or summary section.
- Report the total as a discussion aid, not a mathematical decision rule.
- If evidence is missing, do not invent it. Mark the factor unknown and list the information needed.

The brief must include:
- source facts;
- fit score and reasoning;
- red flags;
- missing or conflicting information;
- a preliminary recommendation of pursue, hold, or do not pursue;
- conditions that could change the recommendation;
- capture next steps and questions;
- named reviewer roles, not invented people.

Rules:
1. Use no outside information.
2. Do not invent customer knowledge, incumbent facts, qualifications, evidence, dates, or partner commitments.
3. Separate source facts from analysis.
4. State that the recommendation is preliminary.
5. State that both files are draft internal workflow aids requiring qualified human review.
6. Do not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.

Before editing, summarize the approved inputs and planned files. Then create the drafts.
```

