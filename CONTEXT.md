# Project Context — Delhivery Local Driver App Research

## What This Is

User research project for a **full experience revamp** of the Delhivery Local driver app (intracity delivery). Research is being conducted in August 2026 to understand driver behavior, pain points, and unmet needs — then inform the redesign.

The HTML files in this repo are the deliverable: a living, interactive research document hosted on GitHub Pages.

## Who I Am

- Product designer at Delhivery, handling the **driver-facing app**
- Based in Bangalore; Tamil speaker (drivers speak Kannada/Hindi — using ops team as translators)
- Working with PMs, Ops team, and multiple stakeholders
- Timeline: Complete research within August 2026; revamp ships this quarter (Jul–Sep)

## The Product: Delhivery Local

Intracity (within-city) delivery service. Two sides:
- **Consumer-facing:** Users book shipments, select vehicle type
- **Driver-facing (my scope):** Gig workers accept and fulfill those orders

**Core driver flow:** Receive broadcast → Accept before expiry → Go to pickup → Pick order → Go to drop → Deliver → Collect cash (80% COD) → Mark delivered

**Key features built around this flow:**
- Trip Radar — browse and accept unaccepted trips
- Slots/MBG — book time slots, earn guaranteed minimum (opt-in, declining usage)
- Incentives — bonuses for hitting order/time targets
- Performance tab — view metrics
- Earnings page — view earnings

**Current state of the app:** 2 years in production. Old UI with ~5 feature entry points added randomly on homepage. Migrating to new design system "TARMAC" — using this as opportunity to rethink experience, not just reskin.

---

## The Drivers

| Attribute | Details |
|-----------|---------|
| Type | Gig workers (blue collar), multi-apping on Porter, Rapido, Uber |
| Vehicles | 2W, 3W, Tata Ace, 8ft pickup (broadcast goes to matching vehicle type) |
| Age | 25–50 years |
| Tech literacy | Varies — younger = good, older = basic but functional |
| Devices | Mid-range Android phones (Indian market) |
| Fleet size | ~79,000 registered; ~35,000–38,000 daily active |
| Cities | 6 cities (Bangalore, Delhi, Mumbai, Ahmedabad, Jaipur + 1 more) |

**Driver tiers:**
- Star (13–15% of fleet): Earn 2–3x more, performance-based, dynamic
- Non-Star: Everyone starts here, default tier

**Payout models:**
- Flexi (default): Work whenever, per-order pay, can multi-app
- Slot/MBG (opt-in, declining): Guaranteed daily earning in exchange for 8hr exclusivity + no cancellations

---

## Business Metrics & The Core Problem

**Targets:**
- Fulfillment rate >70%
- Pickup within 15 min >70%
- Deliver on time
- Decrease cancellations
- Improve gross margin

**Reality (Jun 28 – Aug 3 data):**

| Metric | Value |
|--------|-------|
| Fulfillment rate | 54.5% (target >70%) |
| Acceptance rate | ~5% (95% of broadcasts ignored) |
| Post-assignment cancellation | 21% |
| Avg deliveries/driver/day | 0.37 |
| Avg earnings/driver/day | ₹123 |
| P80 pickup time | 21 min (target <15) |
| P80 wait at merchant | 12 min (unpaid) |
| CM1 (contribution margin) | -10.35% (losing money) |
| Daily broadcasts | 450,000–510,000 |
| Orders (5-week) | 647,900 |
| Delivered | 383,467 (59.2%) |

**Key insight:** Adding more drivers hasn't improved fulfillment proportionally. The problem is behavior/engagement, not supply.

**P80 = 80th percentile** (typical worst case benchmark).

---

## PM's Key Insight

> "Don't just look through the design lens. Most problems won't be solved just by the app — it might be an operations issue."

Research findings should be categorized:
- **App-solvable:** Broadcast info insufficient, navigation surprises, feature discoverability
- **Ops-solvable:** Package not ready at pickup, merchant education, wrong vehicle assignments
- **Economics-solvable:** Fare too low for distance, MBG not competitive, no night premium
- **System-solvable:** Broadcast algorithm logic, assignment radius rules, penalty structure

---

## Top 5 Hypotheses to Validate

1. Drivers ignore broadcasts because: app in background, on another app, fare too low, info insufficient
2. Drivers cancel after accepting because: distance surprise (straight-line vs actual route), got better order on Porter, package too big
3. Drivers game the system by asking customers to cancel (avoids penalty on their record)
4. 12 min unpaid wait at pickup causes frustration and future order avoidance
5. Night fulfillment collapses because: safety concerns, no premium, driver fatigue

---

## City-Level Insight

- Ahmedabad/Jaipur perform 2x better than Bangalore/Delhi/Mumbai
- Jaipur acceptance rate: 20–30% vs Bangalore: 3–7%
- Research is in Bangalore (hardest city) — captures worst-case behavior

---

## Research Plan

**Goal:** "Understand how drivers interact with the Delhivery Local app across their daily workflow — their mental models, pain points, workarounds, and unmet needs — to inform a full experience revamp that improves fulfillment rate, reduces cancellations, and increases driver retention."

### Phase 0: Stakeholder & Data Alignment (Aug 4–8)
- Talk to PMs: pipeline features, hypotheses, priorities, known pain points
- Talk to Ops: complaints, support queries, cancellation patterns, suspension reasons
- Talk to Driver Ops (field): informal feedback, onboarding struggles, how drivers learn
- Pull analytics: acceptance rates, cancellations, feature adoption, cohort differences
- Competitive audit: Porter, Rapido, Uber driver apps
- Deliverable: "What we already know" doc

### Phase 1: Field Research (Aug 11–22)

**Method 1 — Contextual Inquiry / Ride-Alongs (primary)**
- Shadow 8–10 drivers during working hours (2–3 hrs each)
- Mix: vehicle types, experience levels (new vs veteran)
- Record screen + audio, photograph their setup
- Ops person translates

**Method 2 — In-Office Usability Testing (secondary)**
- 5–6 drivers, task-based scenarios on current app
- Think-aloud protocol (translated)
- Record sessions

**Method 3 — Quick Intercept Surveys (bonus)**
- 20–30 drivers at driver hubs
- 5-min Google Form: satisfaction, feature awareness, competitor usage

**Recruitment criteria:**
- Vehicle type: 2W, 3W, 4W
- Tenure: <3 months, 3–12 months, >12 months
- Activity: High performers vs low/at-risk
- Age: 25–30 vs 35–50

### Phase 2: Synthesis (Aug 22–29)
- Affinity mapping → themes
- Journey mapping → pain points at each stage
- Persona creation → 2–3 behavior-based personas
- Opportunity scoring → frequency × severity × business impact
- Insight statements → "We observed X, because Y, which means Z"

### Phase 3: Recommendations (End of Aug)
- Google Doc: Executive summary → Insights → Journey map → Opportunities → Recommendations → Appendix
- Present with "Now, Next, Later" framework
- Also hosted as interactive website

---

## Meeting Agendas

### PM Sync (30–45 min)
Purpose: Align research with existing knowledge and pipeline.
- Existing pain points or driver feedback already collected?
- Hypotheses about what's broken?
- Features/changes already planned this quarter?
- Business priorities beyond the known metrics?
- Areas we shouldn't touch or decisions already locked in?

### Ops Team Sync (45–60 min)
Purpose: Ground-level insights from the team closest to drivers.

**Driver complaints & pain points**
- Most frequent complaints (app and non-app)?
- Screens/features drivers always ask for help with?
- "Why can't the app just do X?" — what's X usually?
- Things that used to be complained about but got fixed?

**Support queries**
- Top 5 reasons drivers contact support?
- Categorized support ticket data available?
- Repeat queries — same drivers, same issues?
- Peak support times and why?

**Cancellations & suspensions**
- Why drivers cancel — observed patterns?
- Vehicle type or area differences?
- How drivers react to suspension?
- Do they understand why they were suspended?

**Churn & retention**
- Why drivers leave or go inactive?
- Specific drop-off point (time/event)?
- Do they come back? What brings them back?
- Loyal drivers vs churned — what's different?

**Onboarding & learning**
- How new drivers learn the app?
- First things they struggle with?
- Informal community/help between drivers?
- Time to feel comfortable?

**Multi-app behavior**
- What they know about drivers using competitors?
- What drivers prefer about those apps?
- Open comparisons drivers make?
- Times of day drivers switch to competitor apps?

**Driver behavior patterns**
- Typical day: high performer vs low-activity?
- Location strategy (where they wait)?
- Feature understanding (Trip Radar, Slots, Incentives)?
- Features built but barely used?

**COD & cash handling**
- Issues with cash (wrong amounts, no change, disputes)?
- How they manage cash throughout the day?

**Field research support**
- Kannada/Hindi translators available for Aug 11–22?
- Driver hubs/waiting spots in Bangalore?
- Tips for building rapport?

---

## Checklist — Don't Forget

- [ ] Speak with Ops about top support queries and complaints
- [ ] Check with PMs about pipeline features/changes
- [ ] Check with PMs about existing hypotheses
- [ ] Get churn data and reasons from data/ops
- [ ] Check how new drivers learn the app (onboarding gap)
- [ ] Competitive audit: Porter, Rapido driver apps yourself
- [ ] Language tips: brief translator beforehand, use visual/show-me methods, screen recordings, observation templates, card-sorting exercises

---

## Constraints & Decisions

- **Language:** Tamil speaker researching Kannada/Hindi drivers. Ops team translates.
- **City:** Bangalore only (Chennai not launched yet)
- **Timeline:** Research done by end of August
- **Budget:** Team covers driver incentives for office visits
- **Scope:** Entire app (not just specific flows)
- **Stakeholders:** Multiple (beyond just manager)
- **Onboarding:** Happens in separate app; driver app has no onboarding flow
- **Recording:** Sessions can be recorded with driver consent
- **Deliverable format:** Google Doc + interactive website (GitHub Pages)

---

## Current Status (Aug 4, 2026)

- ✅ Research plan created
- ✅ Analytics data pulled and analyzed (Jun 28 – Aug 3)
- ✅ PM & Ops interview questions prepared
- ⬜ Stakeholder conversations (Week 1: Aug 4–8)
- ⬜ Field research / ride-alongs (Week 2–3: Aug 11–22)
- ⬜ Synthesis & report (Week 4: Aug 25–29)

---

## Key Files

- `index.html` — Landing page linking to both sections
- `research-plan.html` — Methodology, phases, timeline, interview questions, recruitment criteria
- `data-findings.html` — 41 quantitative findings from analytics data, organized in 6 categories

## Deployment

- Repo: https://github.com/jeganathanc-pd/delhivery-local-driver-app-research
- Live site: https://jeganathanc-pd.github.io/delhivery-local-driver-app-research/
- Deploy: GitHub Actions → GitHub Pages

## Working Agreements

- All content in HTML files (web-based living document)
- Data findings and research plan are separate pages
- Accordions/collapsibles for dense reference content
- Push to GitHub after significant changes
