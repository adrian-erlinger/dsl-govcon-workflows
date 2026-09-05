# First-Run Starter Prompt

Use this if you are opening the repository in Codex for the first time and want a guided first practice run.

In this exercise, you will practice an early go/no-go review. The opportunity comes from a real public SAM.gov notice. The company evidence comes from the repository's synthetic files, so you can practice without using real company data.

Codex will create two draft Markdown files for you to review. The filenames should include the solicitation number so you can practice with more than one opportunity:

- `workflows/opportunity-triage/outputs/draft-opportunity-intake-[SOLICITATION-NUMBER].md` - a worksheet that captures the opportunity facts, source notes, unknowns, and review questions.
- `workflows/opportunity-triage/outputs/draft-bid-no-bid-brief-[SOLICITATION-NUMBER].md` - a discussion aid with fit scores, reasoning, risks, and a preliminary pursue/hold/do-not-pursue recommendation.

These draft files are the practice outputs. They are not final business recommendations, and you will review them before accepting the changes.

Copy the text between `BEGIN PROMPT` and `END PROMPT` into Codex.

```text
BEGIN PROMPT

I am a first-time user trying the GovCon training repository. Please guide me through the first practice run step by step.

Please help me practice an early Opportunity Triage and Bid/No-Bid review using:
- one real public SAM.gov opportunity as the opportunity being reviewed; and
- only the synthetic organization files in this repository as the pretend company evidence.

Start by reading:
- START-HERE.md
- SAFETY-AND-BOUNDARIES.md
- workflows/opportunity-triage/README.md
- workflows/opportunity-triage/instructions.md
- workflows/opportunity-triage/prompt.md

For the real opportunity:
- If I already provided a SAM.gov link, solicitation number, notice ID, or pasted opportunity text, use that as the public opportunity source.
- If I have not picked one yet, explain that choosing the opportunity is the next step in the exercise and invite me to send a SAM.gov link, notice ID, solicitation number, or pasted opportunity text.
- If you cannot access SAM.gov directly, explain the limitation briefly and ask me to paste the relevant public opportunity text into the chat.
- Do not describe this as a required stopping point, missing information, or something I failed to provide. Use language like: "Great, we are ready for the next step: choosing the public opportunity to practice on."

Use the repository's synthetic organization evidence only from:
- workflows/opportunity-triage/data/synthetic-capability-statement.md
- workflows/opportunity-triage/data/synthetic-past-performance-snapshots.csv
- workflows/opportunity-triage/data/synthetic-delivery-capacity.csv
- workflows/opportunity-triage/data/synthetic-staffing-and-partner-notes.csv
- workflows/opportunity-triage/data/synthetic-review-criteria.md, if useful as a practice scoring frame
- workflows/opportunity-triage/templates/opportunity-intake.md
- workflows/opportunity-triage/templates/bid-no-bid-brief.md
- workflows/opportunity-triage/outputs/

Do not use the synthetic opportunity notice, synthetic opportunity summary, synthetic opportunity input, or synthetic customer context as facts about the real SAM.gov opportunity.

After you have the public opportunity source, identify the solicitation number and create filenames that include it:
- workflows/opportunity-triage/outputs/draft-opportunity-intake-[SOLICITATION-NUMBER].md
- workflows/opportunity-triage/outputs/draft-bid-no-bid-brief-[SOLICITATION-NUMBER].md

For example, if the solicitation number is `N0003926R9450`, create:
- workflows/opportunity-triage/outputs/draft-opportunity-intake-N0003926R9450.md
- workflows/opportunity-triage/outputs/draft-bid-no-bid-brief-N0003926R9450.md

If the opportunity does not provide a clear solicitation number, ask me before choosing another identifier. If either target draft file already exists, ask me before replacing it.

Before editing, briefly summarize in plain language:
- which public SAM.gov opportunity source you will use;
- which synthetic organization files you will use;
- what appears known, partially supported, unknown, or missing;
- what files you plan to create.

Then state that no files have been created yet, ask for my explicit approval in the chat to create the two drafts, and stop until I answer affirmatively. Providing a SAM.gov opportunity or opening this prompt does not authorize file creation. If either target file already exists, show its name and ask for separate explicit permission before replacing it.

Use a coaching tone throughout. Assume I am learning both Codex and the workflow. Explain what is happening, why the next step matters, and what I should review, without making missing information sound like a mistake.

If you need me to choose the SAM.gov opportunity before drafting, respond with a friendly handoff like this:

"Great, we are ready for the next step: choosing the public opportunity to practice on.

This exercise uses one public SAM.gov opportunity as the example target, then compares it with the synthetic company evidence in this repository. Send me any one of these and I will take it from there:

- a SAM.gov link
- a notice ID
- a solicitation number
- pasted public opportunity text

If you do not have one picked out yet, that is okay. You can choose any public opportunity that looks interesting, and I can help you understand whether it is a useful practice example."

As you draft, keep these boundaries:
- use only the public SAM.gov opportunity source and the supplied synthetic organization files;
- distinguish source facts from analysis;
- treat scores as discussion aids, not mathematical rules or final decisions;
- surface risks, weak evidence, unanswered questions, and missing information;
- route review questions to roles such as BD, capture, technical, pricing, contracts, or leadership;
- state that the preliminary recommendation is not the final bid/no-bid decision;
- do not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice.

After I approve creation and you create the drafts, tell me what changed and what I should review first.

END PROMPT
```
