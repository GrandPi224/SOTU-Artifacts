# SOTU-Artifacts

> "Permanent library of economic visualizations and market artifacts"

A curated, permanently hosted collection of economic insights, data visualizations, and market commentaries — built for ongoing reference and updated over time.

**Live Site:** [https://grandpi224.github.io/SOTU-Artifacts/](https://grandpi224.github.io/SOTU-Artifacts/)

---

## What This Is

SOTU-Artifacts is a GitHub Pages library that archives economic and market analysis artifacts. Each artifact is a self-contained snapshot — a titled, categorized entry with a thumbnail image and a brief description — covering topics like inflation, monetary policy, geopolitical dynamics, and fiscal risk.

This repo serves as both the source and the hosting platform. The live site rebuilds automatically every time changes are committed.

---

## Current Artifacts

| # | Title | Category | Date |
|---|-------|----------|------|
| 1 | [Market Factors and Key Considerations](https://grandpi224.github.io/SOTU-Artifacts/artifacts/2025-10-market-factors/) | Inflation & Monetary Policy | October 2025 |
| 2 | [Geopolitical Dynamics: Tensions, Trade, and Tactical Economies](https://grandpi224.github.io/SOTU-Artifacts/artifacts/2025-11-geopolitical-dynamics/) | Geopolitical Shifts | November 2025 |
| 3 | [Debt Levels and Fiscal Risks: The Leverage Effect](https://grandpi224.github.io/SOTU-Artifacts/artifacts/2025-11-debt-levels/) | Fiscal & Monetary Policy | November 2025 |

---

## Repository Structure

```
SOTU-Artifacts/
├── docs/
│   ├── index.html              ← Main library page (edit to add artifacts)
│   ├── market-factors-thumb.png
│   ├── assets/images/          ← Thumbnails for artifact cards
│   └── artifacts/              ← Individual artifact pages
├── NOTES-&-INSTRUCTIONS.md    ← Full maintenance guide
└── README.md                  ← This file
```

---

## How to Add a New Artifact

1. Go to `/docs/index.html` and click **Edit** (pencil icon)
2. Copy an existing artifact-card block and paste it at the bottom
3. Update the image path, category, title, date, and description
4. Upload the thumbnail image to `/docs/assets/images/`
5. Click **Commit changes** — the site rebuilds in ~30 seconds

For full step-by-step instructions, see [NOTES-&-INSTRUCTIONS.md](./NOTES-%26-INSTRUCTIONS.md).

---

## Deployment

This site is hosted via **GitHub Pages** from the `/docs` folder on the `main` branch.

- Every commit to `main` triggers an automatic rebuild
- After committing, hard-refresh the live site: `Ctrl + F5` (Windows) or `Cmd + Shift + R` (Mac)
- 21+ successful deployments to date

---

*Maintained by [@GrandPi224](https://github.com/GrandPi224)*
