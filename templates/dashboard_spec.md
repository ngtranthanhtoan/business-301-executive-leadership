# Dashboard Spec

## Blank Template

### Top Layer: Executive Dashboard
Audience: [Audience]  
Update Cadence: [Cadence]  
Tool: [Tool]  

| Metric | DRI | Target | Current | Status | Narrative |
|--------|-----|--------|---------|--------|-----------|
| [NSM] | [DRI] | [Target] | [Current] | [G/Y/R] | [Notes] |
| [KPI1] | [DRI] | [Target] | [Current] | [G/Y/R] | [Notes] |

### Middle Layer: Functional Dashboards
#### [Function] Dashboard
- [Metric]: [Target]
- [Metric]: [Target]

### Bottom Layer: Operational Dashboards
#### [Ops Area]
- [Metric]: [Target]

### Data Sources & Ownership
- [Sources]
- [Review process]

## Practical Example

### Top Layer: Executive Dashboard
Audience: Board & Exec Team  
Update Cadence: Weekly  
Tool: Google Data Studio  

| Metric | DRI | Target | Current | Status | Narrative |
|--------|-----|--------|---------|--------|-----------|
| North Star: Monthly Active Users (MAU) | CEO | 500K | 480K | Green | Steady growth; Q2 campaigns driving uplift. |
| Revenue | CFO | $2M/mo | $1.9M | Yellow | Slight miss due to churn spike; mitigation in place. |
| Churn Rate | VP Product | <5% | 4.8% | Green | Improved onboarding reducing early churn. |
| Customer Acquisition Cost (CAC) | VP Marketing | <$100 | $95 | Green | Optimized ad spend yielding better ROI. |

### Middle Layer: Functional Dashboards
#### Product Dashboard
- Activation Rate: 65% (Target: 70%)
- Feature Adoption: Top 3 features usage trends
- Bug Resolution Time: Avg 48h (Target: <72h)

#### Marketing Dashboard
- Lead Conversion: 25% (Target: 30%)
- Campaign ROI: By channel
- Website Traffic: Sources and bounce rates

### Bottom Layer: Operational Dashboards
#### Support Ops
- Ticket Volume: Daily trends
- Resolution SLA: % met (Target: 95%)
- CSAT Score: Per agent

#### Eng Ops
- Uptime: 99.99% (Target: 99.95%)
- Deploy Frequency: Weekly avg
- Error Rates: By service

### Data Sources & Ownership
- All metrics pulled from single source (Mixpanel + Stripe + Zendesk).
- Weekly review in WBR; anomalies flagged immediately.
- DRI responsible for accuracy and narrative updates.

## Referenced In
Chapter 12: Measuring What Matters
