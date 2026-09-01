# Build Reviewable GovCon AI Workflows With Codex

This private training repository helps GovCon professionals use Codex to create structured, reviewable internal workflow assets from synthetic data. Professionals learn to build briefs, trackers, checklists, and review questions in Markdown and CSV.

The repository is designed for zero setup before learning: a first-time user should be able to download or clone it, open the folder in Codex, read [START-HERE.md](START-HERE.md), inspect the supplied synthetic opportunity notice, structured data, capability statement, past-performance records, review criteria, customer context, and delivery-capacity notes, then run the Opportunity Triage learning path without creating, uploading, or modifying source data first.

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

Start with [START-HERE.md](START-HERE.md). If you want the fastest self-guided path, use [First-Run Starter Prompt](FIRST-RUN-PROMPT.md) to have Codex walk through the Opportunity Triage workflow with you.

Opportunity Triage is the polished test use case for learning how the repository works. After completing it, read [Replacing Synthetic Data](guides/replacing-synthetic-data.md) to see where approved organizational documents would substitute for the training files in a governed environment.

When you are ready to move beyond the first exercise, read [After The Basics](guides/after-the-basics.md). It explains the two next paths: replacing synthetic data with approved real data in a governed workspace, and designing your own GovCon workflows in Codex.

## Important Boundary

This training does not provide legal, procurement, compliance, pricing, cybersecurity, or proposal advice. It teaches participants how to create draft internal workflow assets, templates, checklists, and review questions using Codex. Every output requires review by qualified personnel before use in any live procurement activity.

All repository data is fictional and synthetic so you can practice safely. In this training repository, do not add real company data, proposal data, procurement data, client data, secrets, confidential information, or proprietary material. The goal is to learn a pattern that can later be applied to real workflows, but real organizational use should only be applied in an approved workspace with the approved data-privacy, security, confidentiality, and review controls.

## Markdown and CSV

This repository uses Markdown and CSV files:

- **Markdown** keeps briefs, prompts, instructions, and review notes readable as plain text.
- **CSV** keeps structured records visible in familiar rows and columns.
- Both formats make Codex changes easy to inspect, compare, question, and revise.

The goal is to practice building reviewable workflow assets, not to develop software. The repository includes no application, package dependencies, live integrations, automated submissions, or connections to external systems.
