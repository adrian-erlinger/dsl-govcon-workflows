# Codex Setup and Navigation

Use this guide if this is your first time opening Codex or if you have never opened a local repository in Codex before.

## What Codex Is Doing Here

In this repository, Codex is working with local Markdown and CSV files. You will ask Codex to inspect the synthetic source files, draft two reviewable workflow aids, and show you the proposed file changes before you decide what to keep.

Codex is not making a final bid/no-bid decision. It is helping you draft and review files.

## Put The Repository Somewhere Easy To Find

Before opening Codex, make sure the repository folder exists on your computer.

1. Create or choose a folder where you keep working files. A simple choice is:
   - macOS: `Documents`
   - Windows: `Documents`
2. Put the repository folder there. The folder should be named:
   `dsl-govcon-workflows`
3. Open that folder in Finder or File Explorer.
4. Confirm that you can see files and folders such as:
   - `START-HERE.md`
   - `SAFETY-AND-BOUNDARIES.md`
   - `workflows/`
   - `guides/`

If you received the repository as a `.zip` file, unzip it first. Open the unzipped folder, not the `.zip` file.

## Open Codex

1. Open the ChatGPT desktop app.
2. If the app opens in regular ChatGPT chat, look near the top-left of the app for the product or mode menu and switch to Codex.
3. In Codex, choose the option to open a local folder or project.
4. Select the `dsl-govcon-workflows` folder.
5. Start a new chat for this repository.

If you are not sure whether you opened the right folder, ask Codex:

```text
What folder are you working in, and can you see START-HERE.md?
```

If Codex asks for permission to read or edit files, check that the requested action is limited to this repository before approving it.

## What You Will See In Codex

Codex may look slightly different depending on the version or surface you use, but the main areas are:

- **Chat:** where you type requests and read Codex's responses.
- **Repository files:** the local files Codex can inspect and edit.
- **Review or diff view:** where you inspect proposed file changes before accepting them.
- **Chat history:** where you can return to earlier Codex conversations.
- **Settings or permissions:** where Codex may ask before reading, editing, running commands, or using external access.

For this repository, focus on the chat, the files, and the review or diff view. You do not need to use integrations, plugins, external services, or production tools.

## Find The Important Areas

- `START-HERE.md` tells you where to begin.
- `SAFETY-AND-BOUNDARIES.md` explains what data to use and what to avoid.
- `workflows/opportunity-triage/` contains the starting workflow.
- `workflows/opportunity-triage/data/` contains the synthetic case packet.
- `workflows/opportunity-triage/templates/` contains blank output structures.
- `workflows/opportunity-triage/prompt.md` contains the prompt you will copy into Codex.
- `guides/` contains review checklists and supporting instructions.
- `prompts/` contains reusable prompt templates for later. You do not need this folder to begin.

## First Codex Conversation

Begin with a simple request like this:

```text
Please inspect START-HERE.md and the Opportunity Triage workflow. Summarize what files I should read first. Do not edit any files yet.
```

This helps you confirm that Codex is looking at the right repository and understands the starting workflow.

## Ask Codex To Inspect Before Drafting

Before asking Codex to create outputs, ask it to inspect the source packet:

```text
Please inspect the Opportunity Triage source packet and summarize the known facts, partial evidence, and unknowns. Do not edit files yet.
```

Check whether the summary matches the synthetic files. If it invents information, ask Codex to correct the summary before moving on.

## Use The Workflow Prompt

When you are ready to create the draft files:

1. Open `workflows/opportunity-triage/prompt.md`.
2. Copy the text between `BEGIN PROMPT` and `END PROMPT`.
3. Paste it into Codex.
4. Send the prompt.
5. Let Codex create the draft files named in the prompt.

## Review The Proposed Changes

After Codex drafts files, review the proposed changes before accepting them.

Ask:

1. Which files changed?
2. Did Codex only create the expected draft files?
3. Can each material fact be traced to the synthetic source files?
4. Did Codex preserve unknowns and caveats?
5. Does the draft still require qualified human review?

Use [Reviewing Codex Diffs](reviewing-codex-diffs.md) and the [Human Review Checklist](human-review-checklist.md) for a more detailed review.

## Revise Instead Of Starting Over

If something is wrong, ask Codex for a focused revision:

```text
Revise the draft so the partner-readiness score does not treat the potential partner as committed. Keep the rest of the draft unchanged.
```

Focused revisions are easier to review than asking Codex to regenerate everything.

## Good Habits

- Keep one chat focused on one workflow.
- Ask Codex to inspect files before drafting.
- Ask Codex to summarize its planned changes before editing.
- Review every diff before accepting changes.
- Challenge confident claims that are not supported by the synthetic files.
- Treat all outputs as drafts until qualified people review them.
