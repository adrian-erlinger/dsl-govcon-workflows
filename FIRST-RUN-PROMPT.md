# First-Run Starter Prompt

Use this if you are opening the repository in Codex for the first time and want to try the main workflow without deciding what to ask.

Copy the text between `BEGIN PROMPT` and `END PROMPT` into Codex.

```text
BEGIN PROMPT

I am a first-time user trying the GovCon training repository.

Please help me run the canonical Opportunity Triage and Bid/No-Bid workflow using only the synthetic files already included in this repository.

Start by reading:
- START-HERE.md
- SAFETY-AND-BOUNDARIES.md
- workflows/opportunity-triage/README.md
- workflows/opportunity-triage/instructions.md
- workflows/opportunity-triage/prompt.md

Then follow the Opportunity Triage prompt to create:
- workflows/opportunity-triage/draft-opportunity-intake.md
- workflows/opportunity-triage/draft-bid-no-bid-brief.md

Before editing, briefly summarize in plain language:
- which approved synthetic source files you will use;
- what appears known, partially supported, unknown, or conflicting;
- what files you plan to create.

As you draft, keep these boundaries:
- use only the supplied synthetic training files;
- distinguish source facts from analysis;
- treat scores as discussion aids, not mathematical rules or final decisions;
- surface risks, weak evidence, unanswered questions, and missing information;
- route review questions to roles such as BD, capture, technical, pricing, contracts, or leadership;
- state that the preliminary recommendation is not the final bid/no-bid decision;
- do not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.

After creating the drafts, tell me what changed and what I should review first.

END PROMPT
```
