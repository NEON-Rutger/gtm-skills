---
name: comp-plan-architecture
title: Comp plans that survive disputes, mergers and audits
description: "Sales comp that leaks trust and money because the system around the plan was never designed: credit settled by negotiation, exceptions remembered instead of logged, three legacy plans after an acquisition, a plan change a works council can block, commissions an auditor cannot capitalize. Use when reps argue about who gets credit for a deal, split or double credit creeps past 130% of revenue, nobody owns disputes, legacy comp plans must be merged, a change touches Germany, the Netherlands, France, the UK or the Nordics, a CFO raises IFRS 15 or ASC 606 commission capitalization, or a commission tool is on the table. Produces a crediting rulebook, a governance charter with dispute SLA and exception register, a CCOS-based harmonization sequence, a per-country constraint map, a separable plan design for contract-cost accounting, and tooling selection criteria. Trigger phrases: who gets credit for this deal, comp committee, changing the plan mid-year, works council, Betriebsrat, CCOS."
category: RevOps
tags: [RevOps, Sales]
---

# Compensation Plan Architecture: Crediting, Governance and Lawful Change

Applies when the problem is the machinery around comp: who gets credited, who approves changes, how disputes resolve, whether a change is lawful per country, whether the plan survives an audit.

Produces a crediting rulebook, governance charter, CCOS-based harmonization sequence, per-jurisdiction constraint map, separable plan design for contract-cost accounting and tooling selection criteria.

A comp plan is a contract, an accounting input and a behavior design system at once; most failures design it as only the third.

## Find where they are in the sequencing chain

Compensation is settled last: coverage model, job architecture and leveling, territories, quota methodology, plan mechanics, then pay levels; each step waits on the one above it. Read `references/governance.md` for the six steps, quota-buffer practice rule and ten diagnostic questions.

## Write the crediting rulebook before the mechanics

Start from the rules in force, not the written ones. Pay for persuasion, stop credit when the seller stops being accountable, pick split, double or layered credit, enumerate every uncomfortable scenario and write a total-credit ceiling into the rulebook. Read `references/crediting-rules.md` for survey data, mechanics, the fourteen scenarios, clawback and the dispute loop.

## Harmonize on CCOS, never on day one

Compute compensation cost of sales per legacy entity at actual attainment first (cross-industry B2B benchmark 7.9%, Alexander Group). Crediting, account ownership, the dispute path and the plan document cannot wait; pay levels can. Read `references/harmonization.md` for the year-one shape, level-up scenarios and retention data.

## Establish jurisdiction before any plan change

In Europe a plan change is never an announcement: works council agreement or a binding conciliation ruling (Germany), consent on a system change (Netherlands), consent to any contractual pay-structure change (France), a consultation calendar (UK). Start consultation alongside design; it runs longer. Read `references/eu-legal-constraints.md` for each jurisdiction, citations and the Pay Transparency Directive.

## Design for the auditor

Keep the capitalizable slice (a flat-rate, contract-level commission on new and expansion ACV) separable from quota bonuses, team kickers and SPIFs, and settle continued-service and override treatment with the auditor at design time. Read `references/ifrs15-commissions.md` whenever a CFO or auditor is in the room.

## Govern it

A comp committee approves every change and exception, each logged. Disputes run through one channel to a fixed SLA, and a novel case amends the published rulebook. No verbal plan changes; five documents, not a spreadsheet. Read `references/governance.md` for the committee, SLA practice rule, documents, calendar and health check.

## Choose tooling by criteria, not by brand

First ask what the existing ERP already does for capitalizing contract acquisition costs (not the same as revenue recognition); then rank candidates on the five criteria in `references/spm-tooling.md`, starting with a real contract-cost sub-ledger and overlay splits above 100%.

## What good looks like

The expert's first question is where the organization sits in the sequencing chain. The second is total credit as a percentage of actual revenue: most organizations cannot state it, and that gap explains the disputes. The expert hears "exceptions" and asks for the register; when the answer is someone's memory, the model is likely drifting past the practitioner guardrail of roughly 112% without anyone deciding it should.

The mediocre version averages two legacy plans and calls it harmonization, announces a new plan in a German entity without checking for a Betriebsrat, redesigns an accelerator curve while the coverage model is unresolved, pays a retention bonus to patch a broken plan (it buys a quarter, nothing more), and hands the administrator a spreadsheet instead of a calculation specification.

The output is good when a rep can tell before working a deal whether they will be credited; total credit is bounded, written down and reconciles to revenue in the finance system; dispute volume is reported as a retention metric (roughly 22% of reps hit a commission dispute a year and around 9% leave over commission errors; aggregated vendor survey data, directional); jurisdiction, change-clause and works council status are confirmed in writing before any timeline is published; and a full parallel run has explained every old-versus-new difference line by line before anyone is paid.

## Rules

- MUST establish jurisdiction and change-clause status before discussing any plan change. A design that cannot lawfully be implemented is not a design.
- MUST compute CCOS per legacy entity before proposing a harmonized architecture.
- MUST write the crediting rulebook, with a total-credit ceiling, before the plan mechanics.
- MUST run one full parallel period before anyone is paid on new calculation logic.
- MUST re-verify every benchmark before quoting it to a client or board, and have employment counsel confirm any legal point that drives a decision.
- NEVER propose a single plan for everyone on day one of an integration.
- NEVER let credit be negotiated; negotiated credit teaches reps that escalation pays better than selling.
- NEVER claw back base salary, or more than the commission paid.
- NEVER quote a benchmark for how long harmonization takes or what leveling up costs. None is published.
- For OTE levels, pay mix, accelerator curves and role-level mechanics, design the plan itself separately; for territory and capacity, do that work first and bring the result here.

> Built by [Neon Triforce](https://neontriforce.com)
