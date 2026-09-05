# RFP Compliance Matrix and Proposal Responsibility Tracker

## Audience

Proposal managers, operations leads, capture teams, and contributors who coordinate response work.

## Practical Need

Solicitation instructions can be spread across sections, attachments, tables, Q&A logs, amendments, and deadlines. Compliance work often involves high-friction, detail-oriented artifacts. This workflow drafts a requirement matrix and responsibility tracker from a synthetic source packet.

This is an additional example workflow. Complete the canonical Opportunity Triage workflow first, then use this workflow to practice source extraction and requirement tracking.

## Draft Outputs

- requirement and source reference;
- response artifact and proposed owner role;
- due date and dependencies;
- evidence needed;
- compliance risk and review status;
- routing notes for specialist review.

Generated drafts belong in [outputs/](outputs/) so each workflow keeps its practice results separate from source files, prompts, and templates.

The workflow uses general proposal-management discipline: clear ownership, source traceability, review gates, responsiveness, and human confirmation. Codex can help organize stated requirements and handoffs, but qualified reviewers still determine meaning, completeness, and compliance. It does not reproduce proprietary methods or imply affiliation with any proposal methodology provider.

The output may omit or misinterpret requirements. It is not legal interpretation, automated compliance certification, or a final proposal review. It is a draft internal workflow aid requiring qualified human review.

## Try This Workflow

1. Open [Instructions](instructions.md).
2. Start with the [Source Packet Index](data/source-packet-index.md), then read the approved synthetic files in `data/`.
3. Review the example format in the [Compliance Matrix Template](templates/compliance-matrix.csv) and [Responsibility Tracker Template](templates/responsibility-tracker.csv).
4. Use [prompt.md](prompt.md). Codex will explain the planned files and ask before creating them in `outputs/`.
5. After generation, compare both drafts with the [Expected Output Guide](expected-output-guide.md).

## Your First Practice Run

You can begin by simply telling Codex: **"Let's do the RFP compliance workflow. Help me get started."**

Codex should first explain the exercise and the two planned files. It will not create anything until you explicitly approve that step in the chat. You do not need to understand every RFP term or every spreadsheet column at the start.

The first file, the compliance matrix, is a working list of stated RFP instructions with a pointer back to each source. The second, the responsibility tracker, is a working list of proposed coordinating and review roles. The point is to practice finding, tracing, and questioning requirements; it is not to decide that a response is compliant.

## Take A Guided Tour

Before creating anything, you can tell Codex: **"Walk me through the RFP Compliance Matrix workflow."**

Codex should lead a short conversation in three stages: understand the job, see how one instruction becomes a checkable item, and see how unclear information stays visible. It should introduce only the details needed for the current stage and create no files during the tour.
