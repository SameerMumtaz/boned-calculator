# 🚗 Will This Car Bone Me?

A comprehensive vehicle cost-of-ownership calculator and depreciation prediction engine — built to compete with Edmunds and KBB.

**[Live Demo →](https://yourusername.github.io/will-this-car-bone-me/)**

---

## What It Does

Answers the question every car buyer should ask before signing: **"What will this vehicle actually cost me?"**

Enter a vehicle, financing terms, and mileage — get back a complete ownership cost breakdown including depreciation, equity position, loan payoff analysis, and true monthly cost.

## Features

### 📉 Depreciation Prediction Engine (v3.1)
- **198 models** across 30 brands with real depreciation data
- **683 trim-level MSRPs** from Edmunds for precise valuations
- Powered by **iSeeCars data (15M+ vehicles analyzed)**
- 5-layer prediction model: anchor interpolation → trim modifiers → mileage adjustment → market index → discontinuation impact
- Compare up to 5 vehicles side-by-side with interactive charts
- Fritsch-Carlson monotonic cubic spline interpolation for smooth lifecycle curves

### 📊 Data Explorer
- **Retention Leaders** — Top and bottom vehicles sorted by 3yr, 5yr, or 10yr retention
- **Segment Overview** — 13 vehicle segments with average retention curves and top performers
- **Vehicle vs Segment** — Interactive comparison showing how any model stacks up against its segment average
- **Data Coverage** — Tier distribution, model counts, confidence breakdown

### 💰 Full Cost Calculator
- Purchase price auto-populated from depreciation engine (mileage-adjusted)
- Loan amortization with extra payment modeling
- Equity tracking at any analysis point
- Private party vs trade-in value split
- Mileage impact assessment
- Condition adjustment
- Operating costs (insurance, maintenance, registration)
- Credit score impact analysis

### 🔄 Scenario Comparison
- Auto-generated financing alternatives
- Side-by-side monthly cost and total cost breakdowns
- "What if" analysis for different terms, rates, and down payments

### ⚖️ Vehicle Comparison
- Compare up to 3 vehicles across all cost dimensions
- Winner/loser indicators per metric

### 💰 Lease Calculator
- Lease vs buy analysis
- Monthly payment breakdown with money factor conversion

## Tech

Single HTML file. No build step. No dependencies to install.

- **Vanilla JS** — zero frameworks, zero npm packages
- **Chart.js** (CDN) — for all interactive charts
- **Inter** (Google Fonts) — typography
- **CSS** — custom dark glassmorphism design system with full responsive support

### Responsive Design
- Desktop, tablet, and mobile optimized
- Touch-friendly with 44px minimum tap targets
- Reduced motion support
- Print stylesheet
- Safe area support for notched phones

## Data Sources

| Source | What | Coverage |
|--------|------|----------|
| iSeeCars | Depreciation anchor points (3yr, 5yr, 7yr, 10yr) | 198 models, 15M+ transactions |
| Edmunds | Trim-level MSRPs | 683 trims across 30 brands |

### Tier System

| Tier | Anchors | Confidence | Count |
|------|---------|------------|-------|
| T1 ★ | 4/4 (3yr, 5yr, 7yr, 10yr) | Highest | ~60% of models |
| T2 | 3/4 | High | ~20% |
| T3 | 2/4 | Moderate | ~12% |
| T4 | 1/4 | Directional | ~8% |

## Hosting

This is a single `index.html` file. Drop it anywhere:

### GitHub Pages
1. Create a repo
2. Add `index.html` to root
3. Settings → Pages → Deploy from branch → main
4. Done

### Any Static Host
Works on Netlify, Vercel, Cloudflare Pages, S3, or literally any web server. Just serve the HTML file.

---

*Built with data, not opinions.*

