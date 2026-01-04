## Purpose of This Repository

This repository documents the **end-to-end journey of building a unified Pricing, Software, and Service Analytics solution at ECO3**.

What started as individual reporting requests evolved into a **centralized Sales Analytics application**, designed to act as a **single source of truth** for commercial performance across pricing, software revenue, and service contracts.

This solution is used across multiple business levels and is designed for scalability, governance, and future expansion.

All examples are conceptual and use dummy representations to respect confidentiality.

---

## Why This Solution Was Needed (Business Context)

Before this initiative, pricing, software, and service data existed in:
- Disconnected files
- Manual extracts
- Partially overlapping reports
- Inconsistent logic across teams

This caused:
- Conflicting numbers
- Time spent reconciling instead of analyzing
- Limited trust in commercial KPIs
- No holistic view of sales performance

The business needed:
- **One source of truth**
- **Consistent KPI definitions**
- **Reliable decision-making**
- **A scalable analytics foundation**

---

## Journey Overview (From Request to Application)

### Phase 1 – Pricing Analytics (August)

A new Pricing Marketing Manager requested a pricing-focused report.

I built the solution:
- Starting from raw data
- Validating pricing logic
- Designing KPIs aligned with business reality

What was delivered:
- A complete Pricing Performance report
- Clear KPI definitions
- Trustworthy outputs

This immediately became a reference point for pricing decisions.

---

### Phase 2 – Service & Software Contract Analytics (September)

Colleagues from the Warsaw office requested a Service Contracts report to track:
- Contract start and end dates
- Expiry timelines
- Client-specific conditions
- Service-related KPIs

During this work, it became clear that:
- Service contracts include both **machines and software**
- Software revenue analytics was also required
- Treating these separately would recreate silos

### Key Decision

I merged **Service** and **Software** analytics into a **single unified solution**, ensuring:
- Consistent logic
- Shared dimensions
- Cross-domain insights

---

## Unified Sales Analytics Application

The result is a **Sales Analytics foundation** that integrates:

- Pricing
- Software revenue
- Service contracts

This solution now acts as the **commercial performance backbone**.

---

## Key KPIs Covered

### Pricing KPIs
- Price performance
- Price waterfalls
- Target vs actual price
- Budget vs floor price
- Regional and product-level comparisons

### Software Revenue KPIs
- Revenue trends
- Year-over-year comparisons
- Budget vs actual
- Customer-level revenue insights
- Product and region performance

### Service Contract KPIs
- Active contracts
- Contract start & end dates
- Expiry timelines
- Service coverage indicators
- Client-specific contract conditions

---

## Business Questions Answered

This application answers key questions such as:

- Are we selling at or below target price?
- Where are price leaks occurring?
- Which products or regions underperform pricing expectations?
- How is software revenue evolving year over year?
- Which customers drive the most commercial value?
- Which contracts are nearing expiry?
- What service obligations exist per customer?
- How do pricing, software, and service interact commercially?

---

## Designed for All Business Levels

The application is built to support:

- Executives → High-level performance overview
- Management → Tactical monitoring & comparison
- Analysts → Detailed drill-down and validation
- Commercial teams → Day-to-day decision support

This is achieved through:
- Layered KPIs
- Clear navigation
- Intuitive visuals
- Consistent logic

---

## Security & Governance

Security is built in by design:

- Role-based access
- Controlled visibility by region / product / customer
- Dataset-level governance
- No reliance on manual filters

This ensures:
- Data confidentiality
- Trust in numbers
- Safe enterprise-wide usage

---

## Automation & Maintainability

The solution is designed to be:
- Easy to refresh
- Easy to enhance
- Easy to maintain

Key principles:
- Clean semantic models
- Transparent transformations
- Minimal hardcoded logic
- Scalable data structure

---

## Current State

- Actively used by the business
- Stable and trusted KPIs
- Supporting commercial decision-making
- Integrated into ongoing reporting cycles

This is no longer just a report — it is an **analytics product**.

---

## Future Vision – Full Sales Analytics App

This repository represents the **foundation** of a broader Sales Analytics application.

Planned and potential extensions include:
- Sales volume analytics
- Margin analysis
- Advanced KPI benchmarking
- Deeper customer profitability views
- Integration with future BDM 2.0 databases
- AI-ready structures for forecasting and recommendations

The long-term goal is a **single, unified Sales Analytics platform** supporting ECO3 at scale.

---

## How This Repository Fits in the Bigger Journey

This repository represents **Phase 1** of a broader transformation:

- **Phase 1:** [`ECO3-legacy-reporting-environment-analysis`](https://rutang-bhatiya.github.io/ECO3-legacy-reporting-environment-analysis/)
- **Phase 2:** [`ECO3-operational-BI-ownership`](https://rutang-bhatiya.github.io/ECO3-operational-BI-ownership/)
- **Phase 3:** [`Pricing-Software-Service--Sales-analytics (this repo)`](https://rutang-bhatiya.github.io/ECO3-Pricing-Software-Service--Sales-analytics/)
- **Phase 4:** [`ECO3-data-engineering-BDM-2-future-architecture`](https://rutang-bhatiya.github.io/ECO3-data-engineering-BDM-2-future-architecture/)

Each phase is documented separately to keep clarity and focus.


---

## Suggested Diagrams to Add (Optional – Later)

1. **Sales Analytics Scope Diagram**
   - Pricing + Software + Service → Unified App

2. **KPI Layering Diagram**
   - Executive → Manager → Analyst views

3. **Security Model Diagram**
   - Users → Roles → KPIs → Data

---

## Confidentiality Notice

All descriptions use abstracted logic and dummy representations.

No proprietary ECO3 data, pricing logic, or customer information is exposed.

---

## Navigation

- **Overview:** [`About Me`](https://rutang-bhatiya.github.io/Rutang-Bhatiya/){:target="_blank"}
  *It contain links to My portfolio and all major pages and projects*

- **NielsenIQ:** [`NielsenIQ-Enterprise-Analytics-Journey`](https://rutang-bhatiya.github.io/Enterprise-Analytics-Journey-NielsenIQ/){:target="_blank"}
  *Links to all Nielsen Repo*

- **ECO3:** [`ECO3-enterprise-analytics-journey`](https://rutang-bhatiya.github.io/ECO3-enterprise-analytics-journey/){:target="_blank"}
  *Links to all ECO3 Repo*
