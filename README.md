# CubeSat Mission Business Analytics: Launch Cost, Mission Feasibility & ROI Analytics

An Excel-based business analytics project comparing 40 hypothetical CubeSat mission scenarios across 1U, 3U, 6U and 12U classes. This repository includes a browser-based dashboard, the Excel workbook, and a CSV dataset.

## Open the project
After enabling GitHub Pages, open the published website URL to view the interactive dashboard. The root `index.html` is the website entry point.

## Files
- `index.html` — interactive web dashboard with summary metrics, ROI-by-class bars, searchable/filterable scenario table, and download links.
- `CubeSat_Mission_Business_Analytics.xlsx` — Excel workbook with dashboard, scenario data, assumptions, methodology and submission guide.
- `cubesat_scenario_data.csv` — 40-row scenario dataset for Excel, SQL or Power BI.
- `README_CubeSat_Project.md` — detailed project overview and methodology.

## Key metrics
- **Total Cost** = Development + Launch + Integration + Testing + (Annual Operating Cost × Lifetime)
- **Total Revenue** = Annual Revenue × Mission Lifetime
- **Net Profit** = Total Revenue − Total Cost
- **ROI (%)** = (Net Profit ÷ Total Cost) × 100
- **Break-even (years)** = Total Cost ÷ Annual Revenue

## Important data note
Costs, revenues, lifetimes, and scores are illustrative educational assumptions, not verified current market quotations or audited mission outcomes. Risk and feasibility scores are heuristic decision-support indicators, not engineering certification.

## Publish on GitHub
1. Sign in at https://github.com/new and create a **Public** repository named `cubesat-mission-business-analytics`.
2. Upload all files in this package to the repository root (especially `index.html` and `cubesat_scenario_data.csv`).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose branch `main` and folder `/ (root)`, then click **Save**.
5. Wait for deployment. GitHub Pages will show the live URL in Settings → Pages. The website URL is typically `https://YOUR-USERNAME.github.io/cubesat-mission-business-analytics/`.

The repository and live site are not created until you complete these account-specific steps. Do not submit a guessed URL; copy the actual URLs shown by GitHub.
