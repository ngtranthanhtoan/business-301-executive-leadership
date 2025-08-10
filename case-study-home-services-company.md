# Case Study: Home Services Company — Applying Executive Leadership 301 End-to-End

## Context Snapshot
- Company: Acme Home Services (plumbing, HVAC, electrical)
- Footprint: 6 cities, 180 field technicians, 25 dispatchers, 12 sales reps
- Stage: $48M ARR, EBITDA 11%, private-equity backed; goal to 2x in 24 months
- Initial symptoms: Late arrivals, first-time fix rate at 68%, NPS 41, tech churn 28%, weekly flameouts in scheduling, board surprises on margin variance

---

## 0–30 Days: The Executive Shift Installed
- Calendar audit across Four Rooms; temporarily biased to 50% Machine, 30% Map for the first month given reliability issues
- Published 1‑page Executive Charter with 90‑day outcomes: reliability, routing efficiency, tech retention, cash cycle
- Installed core rituals (WBR/MBR/Quarterly Strategy Review) and decision rights (RAPID). Defined one-way vs two-way doors (pricing changes Type 1; routing tweaks Type 2)

### Executive Charter (excerpt)
- Scope: Multi-city field ops, dispatch, customer experience, platform
- Bets: (1) Reliability first; (2) First-time fix; (3) Route density & utilization; (4) Maintenance plan subs
- 90‑day outcomes: On-time arrival +15 pts; FTF +10 pts; Utilization +8 pts; Tech churn -5 pts

---

## Strategy & Narrative

### Strategy Kernel
- Diagnosis: Utilization loss from poor routing and variable job scoping; parts unavailability drives repeat visits; incentives reward speed over quality
- Guiding Policy: Reliability before speed; standardize scoping & parts readiness; densify routes by zip; direct incentives to first-time fix and 5-star outcomes
- Coherent Actions: Switch to parts pre-kitting; adopt dynamic routing; train scoping checklist; launch maintenance plan pilot; revise incentives

### Executive Narrative (stack)
- North Star statement: "We deliver trusted, on-time fixes the first time."
- Pillars: Reliability, First-Time Fix, Route Density
- Proof points: On-time %, FTF %, Repeat visit rate, 5-star reviews
- Stories: "Grandma’s AC first-time fix in July heat"; "Same-day water heater rescue"
- Call to action: "Run the scoping checklist, update parts status in-app, and keep routes tight."

---

## The Operating System (OS)

### Cadence
- Weekly WBR: Reliability, FTF, Utilization, Safety, Cash cycle deltas; 60 minutes, variance notes pre-read
- Monthly MBR: Portfolio of bets, budget, kill/accelerate decisions
- Quarterly Strategy Review: Market, expansion, pricing, platform roadmap

### Forums and Standards
- WBR inputs: Single dashboard; owner variance notes (max 3 bullets); top blockers; decisions needed
- Standards: Single metrics source; DRIs on every metric; decision brief required for Type 1 proposals; project health codes (G/Y/R)

### Sample WBR Owner Slice
- Ops DRI: On-time arrival, First-time fix
- Dispatch DRI: Route density (jobs per route), Average drive time
- Supply DRI: Parts unavailability rate, Backorder SLA
- CX DRI: 5-star %, Repeat call rate

---

## Capital Allocation

### Portfolio mix
- Core (55%): Reliability program (SLOs, parts pre-kitting), Dynamic routing, Scoping training
- Growth (25%): Maintenance plan subscriptions; cross-sell electrical to HVAC customers; 2-city expansion
- Options (20%): Partner marketplace for specialty repairs; AI-assisted triage pilot; mobile inventory vans

### Kill criteria (attached to briefs)
- Maintenance plan: <5% attach rate by Q2 → stop
- AI triage: <10% average handle time improvement by month 2 → stop
- Marketplace: <30% NPS for specialty partners after 100 jobs → stop/replace vendors

---

## Org Design & Talent Density

### Structure follows strategy
- Created Regional Pods (Ops Manager + Dispatch Lead + CX Lead + Supply Lead) per metro to drive local reliability
- Central Platform Team for routing, data, and tooling

### Spans & layers
- Field Supervisors 8–10 DRs; Dispatch Leads 6–8 DRs; reduced layers from 5 → 4 to speed decisions

### Talent moves
- Top 10% techs assigned as "Scoping Champions"; underperforming supervisors coached for 30 days with clear outcomes; recruiting bar raised; referral incentives

### Succession
- Ready-now leads identified for each region; 9-box completed for top 50 roles; backfills planned for two at-risk regions

---

## Decision Architecture

### Type 1 vs Type 2 examples
- Type 1: Entering a new metro; pricing model change; selecting routing platform vendor
- Type 2: Daily route balancing; spare-part substitutions; scoping checklist tweaks

### RAPID roles (example: Switch to dynamic routing platform)
- Recommend: Platform Lead (brief owner)
- Agree: Finance (unit economics), Ops (SLA impact)
- Perform: Dispatch and Field Ops
- Input: CX (NPS impact), Supply (parts timing)
- Decide: COO

### Escalation ladder
- Level 1: Dispatch Lead/Regional Pod
- Level 2: Ops Director
- Level 3: COO/Exec team (rare; Type 1 only)

---

## Executive Communication

### Upward (board/PE)
- One-pager structure: What changed since last, key metrics, decisions needed, risks/mitigations

### Downward (regions/techs)
- Weekly note: Reliability wins, single focus, safety call-out, short story, CTA

### Outward (partners/customers)
- "Reliability First" campaign: arrival windows, 2-way SMS, parts-ready badge

---

## Governance & Stakeholders
- Board packet TOC: Changes-and-asks cover; NSM/FTF/Utilization; portfolio; risks; hiring; cash
- Stakeholder map: PE sponsor (ally, high influence); city licensing (neutral → educate); major suppliers (ally); marketplace partners (varied)
- Compliance embedded in OS: Safety metrics in WBR; licensing audits quarterly

---

## Culture by Design

### Values (applied)
1) Safety is sacred  2) Reliability over speed  3) Own the outcome  4) Respect the home

### Behaviors
- Safety: PPE always; "stop work" authority
- Reliability: Run the checklist; confirm parts
- Ownership: Close the loop; document learnings
- Respect: Shoe covers; clean-up photo required

### Rituals
- "Safety Minute" opens every WBR and standup
- "First-Time Fix Friday" demo: showcase saves and learnings
- Monthly "Customer Story" rotation

---

## Product & Platform Scaling

### Platform priorities
- Reliability before speed: SLOs for dispatch API and mobile app
- Observability: Job state trace; route ETA accuracy metrics
- Modularity: Vendor-agnostic routing adapter; inventory service

### Build/Buy/Partner
- Buy: Best-in-class routing engine (time-to-value); partner with maps provider
- Build: Scoping checklist workflow + parts pre-kit logic (our moat)
- Partner: Marketplace for specialty repairs with NPS gating

---

## Crisis Leadership

### Scenario: Viral post of late arrival + water damage claim
- Incident Commander: Regional Ops Manager
- Ops Lead: Dispatch Lead; Comms Lead: CX Director; Legal/Risk: GC; Liaison: COO
- First 2 hours: Acknowledge, service pause in block, on-site remediation, claim process started; internal/external aligned update cadence
- 72-hour debrief: Root cause (parts not ready + unrealistic routing window), fixes (harder routing constraints, parts SLA), story of recovery to customers

---

## Measuring What Matters

### North Star Metric (NSM)
- "On-Time First-Time Fixes per Technician per Day (5-star verified)"

### KPI Tree
```mermaid
flowchart TB
  NSM[On-Time FTF/Tech/Day (5-star)] --> REL[On-Time Arrival %]
  NSM --> FTF[First-Time Fix %]
  NSM --> UTIL[Technician Utilization]
  NSM --> CSAT[5-star % / NPS]
  REL --> ETA[ETA Accuracy]
  REL --> DRIVE[Avg Drive Time]
  FTF --> PARTS[Parts Readiness %]
  FTF --> SCOPE[Scoping Checklist Compliance]
  UTIL --> DENS[Route Density]
  UTIL --> AHT[Avg Handle Time]
  CSAT --> REPEAT[Repeat Visit Rate]
  CSAT --> COMPL[Complaints per 100 Jobs]
```

### Metric design
- Each metric has a DRI; counter-metrics: Speed ↔ Quality (AHT vs 5-star %); Growth ↔ Safety (Jobs/Day vs Safety Incidents)

### Dashboards & cadence
- Weekly: WBR page (max 10 metrics), traffic-light, owner notes
- Monthly: KPI review; budget shifts tied to metrics
- Quarterly: NSM validation; reset targets

---

## 30/60/90 Day Plan (Applied)
- 0–30: Charter, OS install, reliability blitz, checklist training, routing vendor selection
- 31–60: Pre-kitting live in 3 cities, dynamic routing rollout, incentive redesign, NSM dashboard live
- 61–90: Maintenance plan pilot, 2-city expansion decision, decision audit #1, governance refresh

---

## Artifacts Produced (links)
- Executive Charter → `templates/executive_charter.md`
- Decision Rights Map (RAPID) → `templates/decision_rights_map.md`
- Operating Cadence → `templates/operating_cadence.md`
- WBR/MBR Agendas → `templates/wbr_agenda.md`, `templates/mbr_agenda.md`
- Decision Brief (routing switch) → `templates/decision_brief.md`
- Build/Buy/Partner Scorecard → `templates/build_buy_partner_scorecard.md`
- KPI Tree Worksheet, Dashboard Spec → `templates/kpi_tree_worksheet.md`, `templates/dashboard_spec.md`
- Crisis Playbook (ICS) → `templates/crisis_playbook.md`
- Culture Doc → `templates/culture_doc.md`
- Board Packet TOC → `templates/board_packet_toc.md`
- Stakeholder Map, Risk Register → `templates/stakeholder_map.md`, `templates/risk_register.md`

---

## Outcomes After 2 Quarters (hypothetical)
- On-time arrival: 74% → 90%
- First-time fix: 68% → 82%
- Tech utilization: +11 pts; avg drive time -18%
- 5-star reviews: 46% → 66%; NPS: 41 → 62
- Repeat visit rate: -28%
- EBITDA: +3.5 pts; cash cycle -9 days; tech churn: 28% → 18%

---

## Connects to Chapters
- Strategy & Narrative → `chapter-02-strategy-and-narrative.md`
- Operating System → `chapter-03-the-operating-system.md`
- Capital Allocation → `chapter-04-capital-allocation.md`
- Org & Talent → `chapter-05-org-design-and-talent-density.md`
- Decision Architecture → `chapter-06-decision-architecture.md`
- Executive Communication → `chapter-07-executive-communication.md`
- Governance & Stakeholders → `chapter-08-governance-and-stakeholders.md`
- Culture by Design → `chapter-09-culture-by-design.md`
- Product & Platform Scaling → `chapter-10-product-and-platform-scaling.md`
- Crisis Leadership → `chapter-11-crisis-leadership.md`
- Measuring What Matters → `chapter-12-measuring-what-matters.md`
