# Opportunity Triage Prompt

Copy the text between `BEGIN PROMPT` and `END PROMPT` into Codex.

```text
BEGIN PROMPT

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
- Use this scale:
  - 0 = weak or no evidence in the supplied synthetic inputs.
  - 1 = partial or uncertain evidence in the supplied synthetic inputs.
  - 2 = strong evidence from the supplied synthetic inputs.
- Define customer fit as the strength of supplied evidence that Synthetic Organization Alpha has documented knowledge of or a relationship with the fictional customer. Use only the customer relationship and related information in the supplied synthetic files; do not infer familiarity from general capability fit.
- Explain each score using a named source field or summary section.
- Report the total as a discussion aid, not a mathematical decision rule.
- If the inputs do not provide enough information to assign a score, do not invent it. Mark the factor unknown, do not treat it as a negative fact, and list the information needed.

Definitions:
- A red flag is a known fact in the supplied inputs that may create pursuit or delivery risk.
- Missing information is information the supplied inputs do not provide. Record it as a question, not as a negative fact.
- Approved reviewer roles are BD lead, capture lead, proposal lead, contracts reviewer, technical SME, pricing lead, and executive reviewer.
- Reviewer roles are suggested routing labels for questions and next steps, not outside facts about a real team. Do not invent people.

The brief must include:
- source facts;
- fit score and reasoning;
- red flags;
- missing or conflicting information;
- a preliminary recommendation of pursue, hold, or do not pursue;
- conditions that could change the recommendation;
- capture next steps and questions;
- approved reviewer-role labels, not invented people.

Rules:
1. Use no outside information.
2. Do not invent customer knowledge, incumbent facts, qualifications, evidence, dates, or partner commitments.
3. Separate source facts from analysis.
4. State that the recommendation is preliminary.
5. State that both files are draft internal workflow aids requiring qualified human review.
6. Do not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.

Before editing, summarize the approved inputs and planned files. Then create the drafts.

END PROMPT
```
