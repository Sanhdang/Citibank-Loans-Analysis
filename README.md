# Citibank-Loans-Analysis
An unorthodox, numbers-first portfolio brief that goes straight to decisions. It shows a scaling book—38.6K apps → ~$435.8M funded → ~$473.1M received (~108.6% cash-through), 12.05% APR, 13.33% DTI—with one clear vulnerability: larger tickets in bad loans inflate loss dollars.
## What this is
A concise, decision-oriented analysis of a consumer loan portfolio built from three dashboards (Overview, Summary, Detail). It uses a conclusion-first narrative, minimal boilerplate, and hard numbers as anchors to move from data → insight → action quickly.

## Who it’s for
Credit & risk leaders who need a clear read on quality, growth, and loss economics

Finance/treasury teams tracking cash-through and cohort seasoning

Growth & marketing owners deciding where to lean in (purpose, tenor, geography)

## Data sources & scope
Source: static dashboard snapshots you provided (three images).

Scope: portfolio-level aggregates and distributions; no direct DB/loan-level access.

Period: life-to-date plus latest month-to-date (as shown on tiles).

Rounding: figures rounded to two decimals or nearest thousand; minor totals may differ due to rounding.

## Key stats at a glance
38.6K applications → ~$435.8M funded → ~$473.1M received (≈ 108.6% cash-through)

Avg APR ~12.05%, Avg DTI ~13.33%

MTD: ~$54.0M funded / ~$58.1M received; MoM: +13.0% funded, +15.8% received

Quality: ~86.2% “good” vs ~13.8% “bad”; statuses align (~83.33% fully paid, ~13.82% charged off)

Asymmetry: bad-loan average ticket > good-loan ticket (~$12.36K vs ~$11.15K)

## How to read this report
Start with the cash engine (applications → funded → received) to gauge scale and pacing.

Check quality alignment (good/bad vs fully paid/charge-off) to validate underwriting.

Locate the asymmetry (bigger tickets inside bad loans) to understand loss dollars.

Scan mix levers (purpose × tenor × geography) for where to push or pull.

Finish with the playbook (90-day actions + KPI panel) to operationalize.

## Core takeaways
The portfolio is scaling without wobble: funded and received climb in parallel; cash-in keeps pace with cash-out.

Borrowers aren’t stretched (DTI ~13.33%), and pricing is disciplined (APR ~12.05%).

Underwriting labels hold: “good vs bad” at booking maps to end-states.

Single vulnerability: larger tickets in the bad cohort inflate loss dollars per default.

Fix is surgical, not sweeping: limit caps, micro-pricing, tenor-sensitive DTI, autopay + day-1–30 focus.

## Recommended 90-day actions (high impact, low disruption)
Tighten max ticket exactly where charge-offs over-index (e.g., 60-month + credit-card refi in weaker states).

Micro-price (+50–150 bps) where expected loss is measurably higher.

Differentiate DTI caps by tenor (stricter at 60M than 36M).

Autopay by default and early outreach (D1–D30) for high-ticket/high-risk accounts.

Lean in where proof is strongest: debt consolidation to mortgage-holders; long-tenure and mid-tenure (2–5y) earners.

## KPI panel to keep “always-on”
Funnel: Applications → Approvals → Funded by channel/state

Avg ticket by grade × purpose × term

DPD 1–30 and rolls 30→60→90

Charge-off & recovery by cohort (static-pool)

MTD/MoM funded & received (cash pacing)

Loss-$ per originated-$ in the few risky slices (tracks the red-flag asymmetry)

## Assumptions & limitations
Snapshot-based; no cohort-level or loan-level file was available.

Geographic and purpose distributions were read from charts without raw tables; mix insights are directional where exact labels were absent.

Economic profit is not inferred from cash-through; cohort net yield needs fees, prepay, charge-off timing, and servicing costs.



