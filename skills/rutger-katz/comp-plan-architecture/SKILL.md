---
name: comp-plan-architecture
title: Comp plans that survive disputes, mergers and audits
description: "Sales comp that leaks trust and money because the system around the plan was never designed: credit settled by negotiation, exceptions remembered instead of logged, three legacy plans after an acquisition, a plan change a works council can block, commissions an auditor cannot capitalize. Use when reps argue about who gets credit for a deal, split or double credit creeps past 130% of revenue, nobody owns disputes, legacy comp plans must be merged, a change touches Germany, the Netherlands, France, the UK or the Nordics, a CFO raises IFRS 15 or ASC 606 commission capitalization, or a commission tool is on the table. Produces a crediting rulebook, a governance charter with dispute SLA and exception register, a CCOS-based harmonization sequence, a per-country constraint map, a separable plan design for contract-cost accounting, and tooling selection criteria. Trigger phrases: who gets credit for this deal, comp committee, changing the plan mid-year, works council, Betriebsrat, CCOS."
category: RevOps
tags: [RevOps, Sales]
---

# Compensation Plan Architecture: Crediting, Governance and Lawful Change

Applies when the comp problem is not the numbers but the machinery around them: who gets credited, who approves changes, how disputes resolve, whether a change is lawful in each country, and whether the plan survives an audit.

Produces a crediting rulebook, a governance charter, a CCOS-based harmonization sequence, a per-jurisdiction constraint map, a plan design whose capitalizable slice is separable, and selection criteria for commission tooling.

A comp plan is a contract, an accounting input and a behavior design system at once. Most failures come from designing it as only the third.

## Find where they are in the sequencing chain

Compensation is settled last. Each step is unanswerable until the one above it is decided: coverage model (standalone, connected, overlay specialists or fully integrated; this one choice fixes the crediting design), job architecture and leveling, territory and account assignment, quota methodology (top-down with a 10 to 20 percent buffer as a practice rule, validated bottom-up against pipeline coverage and historical conversion), plan mechanics, and pay levels last, because levels are the expensive part and the part that can be grandfathered. A bonus problem is usually a leveling problem in disguise. If the room is arguing about accelerator curves while the coverage model is unresolved, say so first.

## Write the crediting rulebook before the mechanics

First establish which crediting rules are actually in force, as opposed to written down, and who resolved last period's disputes on what basis. Two principles: pay for persuasion (credit belongs to whoever moved the customer), and credit stops when the seller is no longer accountable. Start from the coverage model, choose split, double or layered credit, then enumerate every uncomfortable scenario: two legacy sellers on one account, a rep leaving before collection, a deal churning inside the clawback window. 16% of companies pay on 130% or more of actual revenue (Alexander Group and WorldatWork survey assets, undated, directional); write a total-credit ceiling into the rulebook. Read `references/crediting-rules.md` for the mechanics table, the fourteen scenarios, clawback design and the dispute loop.

## Harmonize on CCOS, never on day one

With two or more legacy plans, compute compensation cost of sales per entity at actual attainment first (base plus variable over revenue or bookings; cross-industry B2B benchmark 7.9%, Alexander Group). Three entities give three numbers, which turns a fight about fairness into arithmetic about cost. Crediting, account ownership, the dispute path and the plan document cannot wait; pay levels, accelerators and SPIFs can be grandfathered. Propose common architecture with entity-calibrated economics in year one, one plan family in year two. Read `references/harmonization.md` for the failure-mode evidence, the three level-up scenarios and the retention data.

## Establish jurisdiction before any plan change

In Europe a plan change is a negotiation or an individual consent exercise, not an announcement. Germany requires works council agreement, or a binding conciliation board ruling, on the structure of a commission scheme, though not on the value per point; the Netherlands a consent right on a change of the remuneration system, not its outputs; France consent to any change of the contractual pay structure; the UK a consent campaign with a consultation calendar, under rules that are still moving. Consultation runs longer than design, so start it in parallel. Read `references/eu-legal-constraints.md` for every jurisdiction, the citations and the Pay Transparency Directive.

## Design for the auditor

Keep the capitalizable slice (a flat-rate, contract-level commission on new and expansion ACV) structurally separable from quota bonuses, team kickers and SPIFs. Two traps: a substantive continued-service condition can move the payment out of contract-cost accounting, and a manager override or SPIF is incremental only where the payout depends on nothing but obtaining contracts; the auditor rules on both. Read `references/ifrs15-commissions.md` whenever a CFO, controller or auditor is in the room.

## Govern it

A comp committee (comp owner, finance, HR, commercial lead; monthly during change, quarterly in steady state) approves every change and every exception, and exceptions go in a register, never into memory. Disputes enter through one channel, resolve inside a fixed SLA (ten working days is the practice rule), and a novel case amends the published rulebook. No verbal plan changes. The designer owes five documents (rationale, plan per role, rulebook, calculation specification, charter), not a spreadsheet. Read `references/governance.md` for the documents, the annual calendar and the health check.

## Choose tooling by criteria, not by brand

Over 80% of non-trivial spreadsheets contain at least one error (Panko and the EuSpRIG research). Before any purchase, ask what the existing ERP already does for capitalizing contract acquisition costs, a different capability from revenue recognition. Then rank candidates on a real contract-cost sub-ledger, overlay splits above 100%, multi-entity and multi-currency, works council posture and EU data residency. Read `references/spm-tooling.md` for the criteria, tool categories and pricing anchors.

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
