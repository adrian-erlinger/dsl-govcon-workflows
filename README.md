# Build Reviewable GovCon AI Workflows With Codex

This public training repository helps GovCon professionals use Codex to create structured, reviewable internal workflow assets. It includes synthetic data so first-time users can practice immediately, and it shows how the same pattern can later be applied with approved organizational data.

The repository is designed for zero setup before learning: a first-time user should be able to download or clone it, open the folder in Codex, read [START-HERE.md](START-HERE.md), and run the synthetic Opportunity Triage learning path without creating, uploading, or modifying source data first.

## Who This Workshop Is For

This training is for professionals who structure, coordinate, or review GovCon opportunity, capture, proposal, teaming, and operations work. Participants may include founders, business development leads, capture managers, proposal managers, operations leads, and other technical or non-technical contributors.

No software-engineering experience is required.

## What You Will Build

In the workshop, you will create and review one canonical first workflow:

1. an opportunity intake and bid/no-bid brief.

The repository also includes two reference examples that show how the same Markdown-first and CSV-first method can apply to other GovCon workflows:

2. an RFP compliance matrix and proposal responsibility tracker;
3. a past-performance evidence-fit brief and teaming-gap analysis.

These assets organize source information, reasoning, unknowns, ownership, risks, and review questions. They support qualified human review; they do not make final pursuit, proposal, compliance, or teaming decisions.

## What You Will Practice

You will learn how to:

- inspect structured inputs before asking Codex to act;
- use reusable prompts with clear boundaries and output formats;
- create Markdown briefs, CSV trackers, checklists, and questions;
- review Codex changes and challenge unsupported conclusions;
- revise draft outputs before anyone relies on them.

The canonical first workflow and primary training test fixture is:

1. [Opportunity Triage and Bid/No-Bid Brief](workflows/opportunity-triage/README.md)

The reference examples are:

2. [RFP Compliance Matrix and Proposal Responsibility Tracker](workflows/rfp-compliance-matrix/README.md)
3. [Past Performance and Teaming Evidence Finder](workflows/past-performance-teaming/README.md)

## Start Here

Start with [START-HERE.md](START-HERE.md). The fastest self-guided path is a 15-minute synthetic Opportunity Triage exercise using [First-Run Starter Prompt](FIRST-RUN-PROMPT.md). Try a public SAM.gov opportunity only after that first success.

Opportunity Triage is the polished test use case for learning how the repository works. After completing it, read [Replacing Synthetic Data](guides/replacing-synthetic-data.md) to see where approved organizational documents would substitute for the training files in a governed environment.

When you are ready to move beyond the first exercise, read [After The Basics](guides/after-the-basics.md). It explains the two next paths: replacing synthetic data with approved real data in a governed workspace, and designing your own GovCon workflows in Codex.

The repository also includes reusable Codex Skill blueprints in `skills/` for the three workflow examples. These are best discussed after participants have tried the prompt-based workflow once.

## Public Use

You may explore this public repository, clone it, and use the included fictional source packet for individual learning or facilitator-led training. Review [Public Use and Boundaries](PUBLIC-USE.md) before adapting, redistributing, or combining these materials with other sources.

Completed draft artifacts are kept in [examples/](examples/) so they remain distinct from the empty learner-output folders in each workflow.

## Important Boundary

This training does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice. It teaches participants how to create draft internal workflow assets, templates, checklists, and review questions using Codex. Every output requires review by qualified personnel before use in any live procurement activity.

All included example data is fictional and synthetic so you can practice safely. Synthetic data is the starting fixture, not a limitation on the workflow. If your organization already has approved opportunity, proposal, capture, past-performance, staffing, or partner data ready for Codex, you can apply the same pattern with that data in a workspace that matches your organization's data-privacy, security, confidentiality, access-control, and review requirements. Do not use material you are not authorized to use.

## Markdown and CSV

This repository uses Markdown and CSV files:

- **Markdown** keeps briefs, prompts, instructions, and review notes readable as plain text.
- **CSV** keeps structured records visible in familiar rows and columns.
- Both formats make Codex changes easy to inspect, compare, question, and revise.

The goal is to practice building reviewable workflow assets, not to develop software. The repository includes no application, package dependencies, live integrations, automated submissions, or connections to external systems.
