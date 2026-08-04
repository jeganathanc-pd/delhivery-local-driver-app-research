# Project Context — Delhivery Local Driver App Research

## What This Is
User research plan + quantitative data findings for a **full experience revamp** of Delhivery Local's intracity delivery driver app. This is a design research project, not a code project — the HTML files are the deliverable (a living research document).

## Who's Doing This
A product designer conducting field research in Bangalore, India (August 2026). Working with PMs and Ops team. The designer is not a native speaker of the local driver languages (Kannada/Hindi) and will use an ops team member as translator during ride-alongs.

## Key Files
- `index.html` — Landing page linking to both sections
- `research-plan.html` — Methodology, phases, timeline, interview questions, recruitment criteria
- `data-findings.html` — 41 quantitative findings from analytics data, organized in 6 categories

## Current Status (as of Aug 4, 2026)
- ✅ Research plan created
- ✅ Analytics data pulled and analyzed (Jun 28 – Aug 3 data)
- ✅ PM & Ops interview questions prepared
- ⬜ Stakeholder conversations (Week 1: Aug 4-8)
- ⬜ Field research / ride-alongs (Week 2-3: Aug 11-22)
- ⬜ Synthesis & report (Week 4: Aug 25-29)

## Critical Context (Not Obvious From Files)

### PM's Key Insight
"Don't just look through the design lens. Most problems won't be solved just by the app — it might be an operations issue."

**Implication:** Research findings should be categorized into:
- **App-solvable:** Broadcast info insufficient, navigation surprises, feature discoverability
- **Ops-solvable:** Package not ready at pickup, merchant education, wrong vehicle assignments
- **Economics-solvable:** Fare too low for distance, MBG guarantee not competitive, no night premium
- **System-solvable:** Broadcast algorithm logic, assignment radius rules, penalty structure

### Driver Category System (Confirmed with PM)

**Tier: Star vs Non-Star**
- Performance-based (exact metrics unknown — likely acceptance rate, fulfillment, cancellations)
- Dynamic — drivers move between tiers. Good performance → Star. Performance drops → Non-Star.
- Star drivers: ~13-15% of fleet, earn 2-3x more
- No onboarding tier — everyone starts as Non-Star

**Payout Model: Flexi vs Slot/MBG**
- Flexi is the DEFAULT. Work whenever, paid per order, can multi-app.
- Slot/MBG is OPT-IN. Guaranteed minimum daily earning in exchange for:
  - 8 hours online in Delhivery app
  - Cannot use other apps (exclusive to Delhivery during slot)
  - Cannot cancel orders (limited exceptions)
- Slot participation is DECLINING (9.5% → 7.5%) — drivers prefer flexibility

### The Core Problem (Data Summary)
- **54.5% fulfillment** (target >70%) — nearly half of orders fail
- **5% acceptance rate** — 95% of broadcasts are ignored
- **21% post-assignment cancellation** — drivers accept then cancel
- **More drivers didn't help** — fleet tripled (8K→29K) but fulfillment barely moved
- The problem is behavior/engagement, not supply

### Top 5 Hypotheses to Validate with Drivers
1. Drivers ignore broadcasts because: app in background, on another app, fare too low, info insufficient
2. Drivers cancel after accepting because: distance surprise (straight-line vs actual route), got better order on Porter, package too big
3. Drivers game the system by asking customers to cancel (avoids penalty on their record)
4. 12 min unpaid wait at pickup causes frustration and future order avoidance
5. Night fulfillment collapses because: safety concerns, no premium, driver fatigue

### City-Level Insight
- Ahmedabad/Jaipur perform 2x better than Bangalore/Delhi/Mumbai
- Jaipur acceptance rate is 20-30% vs Bangalore at 3-7%
- Research is happening in Bangalore (the hardest city) — good for capturing worst-case behavior

### Key Numbers
| Metric | Value |
|--------|-------|
| Total registered drivers | ~79,000 |
| Daily active drivers | ~35,000-38,000 |
| Weekly active drivers | ~29,000 |
| Star drivers | ~2,000-5,000 |
| Daily broadcasts | 450,000-510,000 |
| Orders (5-week period) | 647,900 |
| Delivered | 383,467 (59.2%) |
| Overall acceptance rate | ~5% |
| Avg deliveries/driver/day | 0.37 |
| Avg earnings/driver/day | ₹123 |
| P80 pickup time | 21 min (target <15) |
| P80 pickup wait at merchant | 12 min |
| CM1 (contribution margin) | -10.35% (losing money) |

### What "P80" Means
80th percentile. "P80 pickup time = 21 min" means 80% of pickups happen within 21 minutes; 20% take longer. Used as a "typical worst case" benchmark.

## Working Agreements
- All content goes into HTML files (this is a web-based living document, deployed via GitHub Pages)
- Data findings and research plan are separate pages
- Accordions/collapsibles used for dense reference content (interview questions, etc.)
- Push to GitHub after significant changes
- Site deploys via GitHub Actions to GitHub Pages

## GitHub Pages
- Repo: https://github.com/jeganathanc-pd/delhivery-local-driver-app-research
- Live site: https://jeganathanc-pd.github.io/delhivery-local-driver-app-research/
- Deployment: GitHub Actions (needs Pages enabled with "GitHub Actions" source in repo settings)
