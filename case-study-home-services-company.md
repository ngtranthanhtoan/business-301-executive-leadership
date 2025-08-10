# Case Study: Home Services Company — Applying Executive Leadership 301 End-to-End

## Context Snapshot
- Company: Acme Home Services (plumbing, HVAC, electrical)
- Footprint: 6 cities, 180 field technicians, 25 dispatchers, 12 sales reps
- Stage: $48M ARR, EBITDA 11%, private-equity backed; goal to 2x in 24 months
- Initial symptoms: Late arrivals, first-time fix rate at 68%, NPS 41, tech churn 28%, weekly flameouts in scheduling, board surprises on margin variance

### How to Use This Case Study
- Skim the section headers in order; each mirrors the book’s chapter sequence.
- In each section, first read the cross-company choices, then the department breakdowns.
- Copy the artifacts list and adapt templates under `templates/` to your org.

### Notation (in this file)
- DRI = Directly Responsible Individual
- SLO = Service Level Objective
- Ops = Operations (we use “Operations” for headings and “Ops” in examples)
- CX = Customer Support
- FTF = First-Time Fix

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

### Department OKRs & Contributions (Quarter 1)
- Operations
  - Objective: Reliable, dense daily routes
  - KRs: On-time arrival 90%; Avg drive time -15%; Jobs/route +10%
  - Contribution: Own routing cadence; enforce variance notes; unblock cross-metro resource shifts
- Technicians
  - Objective: First-time fix as the norm
  - KRs: FTF 82%; Repeat visit rate -25%; Safety incidents/10k jobs < 1
  - Contribution: Scoping checklist compliance 95%; parts readiness confirmations
- Engineering (Platform)
  - Objective: Make reliability the default in tooling
  - KRs: Dispatch API SLO 99.9%; ETA MAPE < 10%; Mobile app crash rate < 0.5%
  - Contribution: Routing adapter, inventory service, observability
- Customer Support (CX)
  - Objective: Transparent, trust-building experience
  - KRs: 5‑star reviews 65%; NPS 60+; Complaint rate/100 jobs -30%
  - Contribution: 2-way SMS, proactive delay alerts, closed-loop follow-ups
- Supply Chain
  - Objective: Parts ready before wheels roll
  - KRs: Parts unavailability rate < 5%; Backorder SLA < 24h; Pre-kit accuracy 98%
  - Contribution: Pre-kitting flow, vendor SLAs, cycle counts

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
- Operations DRI: On-time arrival, First-time fix
- Dispatch DRI: Route density (jobs per route), Average drive time
- Supply Chain DRI: Parts unavailability rate, Backorder SLA
- Customer Support (CX) DRI: 5-star %, Repeat call rate

### Departmental Cadence Maps
- Operations
  - Daily: 15-min route readiness huddle (dispatch + supervisors)
  - Weekly: Regional operations review (variance deltas; top 3 blockers; actions/owners)
- Technicians
  - Daily: Safety + scoping standup; route preview
  - Weekly: FTF coaching, parts feedback to Supply Chain, demo of learnings
- Engineering
  - Weekly: Reliability review (SLO/error budget), incident postmortems, platform roadmap sync with Operations
  - Bi-weekly: Product/Eng sync on mobile UX for scoping/comms
- Customer Support
  - Daily: Queue health, top intents, hold/abandon metrics
  - Weekly: NPS detractor analysis; process fixes with Operations
- Supply Chain
  - Daily: Backorder review, pre-kitting exceptions
  - Weekly: Vendor scorecards; cycle count reconciliation

### Forum Inputs/Outputs by Function
- Inputs: Standardized slices from the single dashboard, per-function variance notes, cross-function dependencies
- Outputs: Decision log entries with DRIs, ETA adjustments, parts pulls, comms scripts

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

### Department Investment Plans (year-to-date)
- Operations: Routing optimization + training; telematics; supervisor coaching program
- Technicians: Tooling stipends tied to FTF; safety equipment; certification credits
- Engineering: Routing adapter; inventory service; observability stack; mobile offline mode
- Customer Support: 2‑way SMS; CRM workflow automation; QA program
- Supply Chain: Pre-kitting stations; vendor integration; regional micro-warehouses pilot

---

## Org Design & Talent Density

### Structure follows strategy
- Created Regional Pods (Operations Manager + Dispatch Lead + Customer Support Lead + Supply Chain Lead) per metro to drive local reliability
- Central Platform Team for routing, data, and tooling

### Spans & layers
- Field Supervisors 8–10 DRs; Dispatch Leads 6–8 DRs; reduced layers from 5 → 4 to speed decisions

### Talent moves
- Top 10% techs assigned as "Scoping Champions"; underperforming supervisors coached for 30 days with clear outcomes; recruiting bar raised; referral incentives

### Succession
- Ready-now leads identified for each region; 9-box completed for top 50 roles; backfills planned for two at-risk regions

### Functional Role Definitions & Interfaces
- Operations: Owns daily reliability, routing adherence, cross-metro balancing
- Technicians: Own FTF and customer experience on site; escalate blockers via app
- Engineering: Own platform reliability, routing accuracy, technician app UX
- Customer Support: Own communications, expectation-setting, recovery gestures
- Supply Chain: Own parts readiness, pre-kitting, vendor performance
- Interfaces: Defined SLAs (e.g., parts readiness SLA to Operations; delay alerts SLA to Customer Support)

---

## Decision Architecture

### Type 1 vs Type 2 examples
- Type 1: Entering a new metro; pricing model change; selecting routing platform vendor
- Type 2: Daily route balancing; spare-part substitutions; scoping checklist tweaks

### RAPID roles (example: Switch to dynamic routing platform)
- Recommend: Platform Lead (brief owner)
- Agree: Finance (unit economics), Operations (SLA impact)
- Perform: Dispatch and Field Operations
- Input: Customer Support (NPS impact), Supply Chain (parts timing)
- Decide: COO

### Escalation ladder
- Level 1: Dispatch Lead/Regional Pod
- Level 2: Operations Director
- Level 3: COO/Exec team (rare; Type 1 only)

### Department Decision Catalogs (examples)
- Operations: Same-day route rebalancing (Type 2); overtime approvals (Type 2); cross-metro crew shifts (Type 1 if >2 days)
- Technicians: On-site part substitutions within price guardrails (Type 2); warranty replacements (Type 2); specialty subcontract (Type 1 if safety risk)
- Engineering: Feature flags for routing changes (Type 2); vendor switch (Type 1); SLO target changes (Type 1)
- Customer Support: Service recovery credits up to threshold (Type 2); public statements in incidents (Type 1)
- Supply Chain: Vendor backorder substitution lists (Type 2); vendor replacement (Type 1)

---

## Executive Communication

### Upward (board/PE)
- One-pager structure: What changed since last, key metrics, decisions needed, risks/mitigations

### Downward (regions/techs)
- Weekly note: Reliability wins, single focus, safety call-out, short story, CTA

### Outward (partners/customers)
- "Reliability First" campaign: arrival windows, 2-way SMS, parts-ready badge

### Function-Specific Scripts
- Operations: “This week’s reliability lever” + decision asks; concise ETA changes
- Technicians: “FTF tip of the week” + safety reminder + story
- Engineering: “Error budget status” + what changed behind the scenes
- Customer Support: “Top 3 intents and how we’re fixing them” + recovery language

---

## Governance & Stakeholders
- Board packet TOC: Changes-and-asks cover; NSM/FTF/Utilization; portfolio; risks; hiring; cash
- Stakeholder map: PE sponsor (ally, high influence); city licensing (neutral → educate); major suppliers (ally); marketplace partners (varied)
- Compliance embedded in OS: Safety metrics in WBR; licensing audits quarterly

### Controls by Function
- Operations: Safety audits; route adherence reviews; vehicle/telematics compliance
- Technicians: Certification tracking; ride-alongs; job-site photo verification
- Engineering: Change management; access controls; incident response SOPs
- Customer Support: Call QA; privacy/PII handling; adverse event scripts
- Supply Chain: Vendor compliance; inventory accuracy; chain-of-custody logs

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

### Function-Specific Behaviors & Anti-Patterns
- Operations: Do — publish variance and fixes; Don’t — hide misses behind anecdotes
- Technicians: Do — escalate early; Don’t — improvise outside guardrails
- Engineering: Do — protect reliability; Don’t — ship silent changes that affect routes
- Customer Support: Do — acknowledge and set expectations; Don’t — overpromise ETAs
- Supply Chain: Do — broadcast shortages early; Don’t — ship partial kits without flags

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

### Engineering Enablers & Backlog Themes
- Enablers: Offline-capable mobile flows; barcode scanning for kits; push-based ETA updates
- Themes: Routing accuracy; technician UX speed; inventory integrity; incident tooling

---

## Crisis Leadership

### Scenario: Viral post of late arrival + water damage claim
- Incident Commander: Regional Operations Manager
- Operations Lead: Dispatch Lead; Comms Lead: Customer Support Director; Legal/Risk: GC; Liaison: COO
- First 2 hours: Acknowledge, service pause in block, on-site remediation, claim process started; internal/external aligned update cadence
- 72-hour debrief: Root cause (parts not ready + unrealistic routing window), fixes (harder routing constraints, parts SLA), story of recovery to customers

### Functional Runbooks (first 24 hours)
- Operations: Lock routing window; assign remediation squad; verify similar-risk jobs
- Technicians: Safety hold on water-line work until checklist pass/parts ready
- Engineering: Freeze risky flags; add temporary ETA slack; open incident room
- Customer Support: Single script; status page updates; proactive outreach to affected customers
- Supply Chain: Audit kits for the job type; rush orders; vendor review

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

### Department Scorecards (targets)
- Operations: On-time 90%; Drive time -15%; Jobs/route +10%
- Technicians: FTF 82%; Repeat -25%; Safety <1/10k jobs
- Engineering: SLO 99.9%; ETA MAPE <10%; Crash <0.5%
- Customer Support: 5‑star 65%; Complaint rate -30%; Abandon <3%
- Supply Chain: Parts ready >95%; Backorder SLA <24h; Kit accuracy 98%

---

## 30/60/90 Day Plan (Applied)
- 0–30: Charter, OS install, reliability blitz, checklist training, routing vendor selection
- 31–60: Pre-kitting live in 3 cities, dynamic routing rollout, incentive redesign, NSM dashboard live
- 61–90: Maintenance plan pilot, 2-city expansion decision, decision audit #1, governance refresh

### Department Workstreams
- Operations: Route policy, telematics rollout, supervisor coaching
- Technicians: Certification push, FTF coaching, tool stipends
- Engineering: Routing adapter MVP, observability dashboard, offline mobile
- Customer Support: 2‑way SMS rollout, QA program, recovery script library
- Supply Chain: Micro-warehouse pilot, vendor SLAs, cycle counts

---

## Risks & Dependencies
- Routing vendor reliability; vendor SLAs
- Hiring pipeline for high-density techs; supervisor bench
- Change management fatigue; communicate with consistency
- Inventory accuracy; barcode/scan adoption

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
