# GTA Housing Market Dashboard

Toronto's housing market has not had a sustained buyer's market in over 20 years. This dashboard examines why — using 26 years of transaction data, current rental conditions, and a deep learning forecast — and what the numbers mean for buyers, renters, and policymakers today.

**[Live Dashboard →](https://your-username.github.io/gta-housing-dashboard)**

---

## What I Found

Rate hikes did not restore affordability. A buyer in October 2022 paid more per month than a buyer at the March 2022 price peak, despite a 16% price decline, because mortgage rates tripled simultaneously.

The rental market is structurally bifurcated. Tenants who stay in place pay 32.7% less than tenants entering the market. This gap — created by rent control and low vacancy — is not correcting; it is widening.

New supply is being built in the wrong places. February 2026 construction data shows 63% of apartment starts concentrated in suburban York Region, while inner Toronto — where vacancy is lowest and job density is highest — has near-zero new units under construction.

---

## Dashboard Features

| Tab | What it answers |
|-----|-----------------|
| Market Overview | 26-year price trend with annotated events + hero chart showing rate hikes made buyers worse off |
| Supply & Demand | SNLR, MOI, DOM, SP/LP — the mechanics behind price movements |
| Geographic View | Community-level choropleth across 65 GTA regions |
| Rental Market 2025 | CMHC vacancy, rents by bedroom, condo vs purpose-built gap |
| Outlook & Forecast | CMHC 2026 starts + TFT 2023 price forecasts by community |
| **Decision Tools** | **Personal Affordability Engine · Rent vs Buy Break-Even · Community Comparison** |

---

## Architecture

TRREB scrape (Selenium) → pandas cleaning → Jupyter EDA → PyTorch TFT model → single-file HTML dashboard (Chart.js + SVG)

136K rows · 5 data sources · No frameworks · Deploys to GitHub Pages

---

## Skills

Python · pandas · Selenium · time series analysis · deep learning (TFT/PyTorch) · Chart.js · SVG choropleth · financial modelling · GitHub Pages
