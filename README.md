# tableau-dashboard-governance-auditor

Board-readable Kinetic Gain proof repo for **Tableau** platform and company signal coverage.

## Product thesis

Dashboards lose trust when certified sources, metric definitions, refresh health, and ownership are unclear.

This repo turns that problem into a small, inspectable product surface: synthetic fixture data, a deterministic CLI, a tested scoring model, a JSON report, and a static brief that explains the business and technical value of the signal.

## Buyer and operator fit

- **Primary audience:** Analytics leaders, revenue operations, BI owners, and board-reporting teams
- **Signal domain:** BI / Analytics
- **Executive question:** Where is this system creating exposure, waste, or decision latency?
- **Product motion:** The product checks dashboard ownership, source certification, metric lineage, refresh reliability, and decision readiness.
- **Value architecture:** Leaders can decide which reports can support board narratives and which require remediation before use.

## What this repo proves

- **Normalize:** messy Tableau operating evidence is represented as explicit lanes.
- **Score:** risk and evidence depth are measured separately so weak proof is not hidden by high urgency.
- **Route:** each lane has an owner and next action instead of a vague status.
- **Package:** CLI output, tests, JSON report, and static page all tell the same board-ready story.

## Integration boundary

Focus area: Tableau workbooks, data sources, extracts, owner metadata, certification flags, and refresh events.

This is synthetic proof only. It does not connect to live Tableau tenants, call private APIs, store secrets, publish credentials, or expose customer data.

## Local run

```bash
npm install
npm test
npm run build
npm run demo
```

## Public surface

The generated site is in `site/index.html`. The data report is in `site/report.json`.

## Keywords

- Tableau
- BI governance
- dashboard trust
- metric lineage
- certified sources
