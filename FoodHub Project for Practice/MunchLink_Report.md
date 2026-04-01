# MunchLink Food Hub
## Stakeholder Business Report

Prepared for: Business, Operations, Marketing, and Partner Management Stakeholders  
Data source: munchlink_orders_enhanced.csv  
Total records analyzed: 1,898 orders

---

## 1. Executive Summary

MunchLink is performing well in core demand and revenue generation, with strong order volume and healthy commission income. The business has clear growth opportunities, especially around high-performing restaurant partnerships and top cuisines.

At the same time, three operating gaps need attention:

1. Customer feedback coverage is low (many orders are unrated).
2. A meaningful share of orders are too slow (over 60 minutes end-to-end).
3. Service quality varies by location, with Uptown underperforming versus other zones.

If MunchLink executes targeted improvements in ratings capture, weekday delivery efficiency, and zone-level operations, it can improve customer trust, reduce complaints, and protect revenue growth.

---

## 2. Business Context and Scope

This report translates technical analysis into practical business decisions. It focuses on:

- Demand patterns: What customers order and when.
- Partner performance: Which restaurants drive volume and quality.
- Operations: Delivery speed, slow-order exposure, and zone-level service quality.
- Revenue: Commission performance across cuisines and order value tiers.
- Customer satisfaction: Ratings behavior and quality signals.

The purpose is to provide easy-to-understand findings and action steps that can be used immediately by decision makers.

---

## 3. Headline KPI Snapshot

| KPI | Value | What It Means |
|---|---:|---|
| Total orders | 1,898 | Solid demand base for analysis |
| Total platform commission | $6,166.50 | Healthy revenue generated from transaction fees |
| Average delivery time | 24.16 minutes | Delivery leg is reasonably fast on average |
| Orders above 60 minutes | 10.54% | About 1 in 10 orders is a high-risk slow experience |
| Orders without rating | 38.8% (736 orders) | Major customer feedback gap |
| Top restaurant by volume | Shake Shack (219 orders) | Key strategic partner |
| Strongest commission cuisine | American | Main revenue driver |
| Highest service issue zone | Uptown (~13.22%) | Priority operational hotspot |

---

## 4. What We Learned (Plain Language Findings)

### 4.1 Demand and Customer Ordering Behavior

- Weekend demand is much higher than weekday demand.
- American cuisine is the strongest demand category, followed by Japanese and Italian.
- Order values cluster in the middle range, with a meaningful high-value segment above $20.

Business meaning:
- MunchLink has predictable demand spikes and clear category winners.
- Marketing and staffing should be planned around weekend intensity and top cuisines.
- High-value orders are important because they carry stronger commission economics.

### 4.2 Restaurant Performance

- A small group of restaurants contributes a large share of total order volume.
- Shake Shack leads in volume and is a critical partner.
- Multiple restaurants show strong ratings at scale, making them reliable candidates for promotions.

Business meaning:
- Partner concentration is both a strength and a risk.
- Strong top partners should be protected with retention plans.
- Highly rated high-volume partners should be used in growth campaigns.

### 4.3 Delivery and Operations

- Average delivery time is acceptable overall, but weekday performance is slower than weekend performance.
- 10.54% of orders exceed 60 minutes total fulfillment time.
- Uptown has the highest service issue rate and needs focused intervention.

Business meaning:
- The business is not facing a system-wide breakdown, but has specific bottlenecks.
- Weekday congestion and zone-level imbalance are likely drivers of poor experiences.
- Reducing long-tail delays (slowest orders) will improve satisfaction more than optimizing already-fast orders.

### 4.4 Customer Satisfaction and Ratings

- When customers rate, scores are generally high.
- However, 38.8% of orders have no rating, reducing visibility into real customer experience.
- Faster deliveries are associated with slightly better ratings, but not dramatically.

Business meaning:
- Ratings signal quality, but the signal is incomplete.
- MunchLink needs more rating participation, not just better average ratings.
- Speed matters, but food quality and partner consistency also likely shape customer sentiment.

### 4.5 Revenue and Monetization

- Total commission is strong for the dataset size.
- Revenue is concentrated in top cuisines, especially American and Japanese.
- Higher-value order tiers make a disproportionate contribution to commission.

Business meaning:
- Revenue can be scaled efficiently by protecting high-demand cuisines and increasing high-value order frequency.
- Strategic menu and promotion design can shift more customers into profitable baskets.

---

## 5. Root-Cause View (Why These Gaps Likely Exist)

### Gap A: High Unrated Order Share (38.8%)
Likely causes:
- Rating request appears too late or is easy to dismiss.
- Customers are not incentivized to leave feedback.
- Friction in the post-delivery flow.

Business impact:
- Reduced quality visibility.
- Slower problem detection for poor-performing partners/zones.
- Weaker trust in decision making.

### Gap B: Slow Orders Over 60 Minutes (10.54%)
Likely causes:
- Weekday traffic and route congestion.
- Imbalance in driver supply by time block.
- Delay accumulation from prep plus delivery segments.

Business impact:
- Lower customer trust.
- Higher support burden and potential refunds.
- Long-term churn risk from repeated poor experiences.

### Gap C: Uptown Service Quality Underperformance
Likely causes:
- Longer travel distances and route complexity.
- Driver allocation mismatch.
- Possible restaurant-side readiness delays in that area.

Business impact:
- Uneven brand experience by geography.
- Higher complaint concentration in one zone.
- Risk of localized reputation damage.

---

## 6. Strategic Recommendations (Prioritized)

## Priority 1: Increase Rating Participation

Actions:
- Trigger in-app rating prompt immediately after delivery confirmation.
- Add one-tap quick rating first, then optional comment.
- Offer small loyalty incentives for completed ratings (for example, points or next-order credit).
- Run A/B tests on prompt timing and wording.

Target outcomes (90 days):
- Reduce unrated share from 38.8% to below 25%.
- Improve confidence in zone and partner quality tracking.

Why this matters:
- Better feedback coverage strengthens every downstream decision.

## Priority 2: Reduce Slow-Order Exposure

Actions:
- Introduce a live watchlist for orders at risk of crossing 60 minutes.
- Add escalation logic at the 45-minute mark for at-risk orders.
- Adjust weekday driver scheduling based on historical load windows.
- Improve dispatch logic for high-congestion corridors.

Target outcomes (90 to 120 days):
- Lower >60-minute orders from 10.54% to under 7%.
- Reduce customer support tickets linked to delivery delays.

Why this matters:
- Preventing the worst experiences has outsized impact on retention and brand trust.

## Priority 3: Run Uptown Recovery Program

Actions:
- Audit Uptown by time-of-day, driver availability, and partner prep delays.
- Increase driver supply during peak slots.
- Pilot micro-zoning or tighter dispatch radii in Uptown.
- Co-design prep readiness improvements with top Uptown partner restaurants.

Target outcomes (120 days):
- Reduce Uptown issue rate from ~13.22% to below 10%.
- Bring Uptown closer to network average.

Why this matters:
- Zone-specific fixes are faster and cheaper than broad system changes.

## Priority 4: Protect and Grow Top Partner/Cuisine Revenue

Actions:
- Build partner success plans for top restaurants (including Shake Shack and other high-volume leaders).
- Offer high-visibility campaign slots to high-rated, high-volume partners.
- Launch weekend bundles for top cuisines.
- Use high-value basket nudges (combos, premium add-ons, group order offers).

Target outcomes (90 to 180 days):
- Increase commission per order.
- Grow weekend conversion in top-performing categories.

Why this matters:
- Revenue concentration can be turned from risk into managed growth.

## Priority 5: Establish Operational Governance Dashboard

Actions:
- Track weekly KPIs at company and zone level.
- Publish a simple scorecard for operations, marketing, and partner teams.
- Define alert thresholds and ownership for each KPI.

Target outcomes:
- Faster response to service deterioration.
- Better cross-team execution alignment.

Why this matters:
- Consistent governance prevents performance drift.

---

## 7. 30-60-90 Day Action Plan

### First 30 Days (Quick Wins)

- Deploy improved rating prompt flow.
- Start weekday capacity review for delivery supply.
- Launch weekly zone performance report.
- Identify top 10 partners for retention and co-marketing planning.

### Day 31 to Day 60 (Pilot and Optimize)

- Pilot delay escalation workflow for at-risk orders.
- Run Uptown operations pilot (driver + dispatch + partner readiness).
- Launch one weekend campaign focused on top cuisines.
- Begin rating incentive A/B test.

### Day 61 to Day 90 (Scale What Works)

- Scale best-performing rating and delay interventions.
- Standardize zone-level playbook for any underperforming area.
- Expand high-value basket strategy to more restaurant partners.
- Roll out executive KPI dashboard cadence.

---

## 8. KPI Targets and Ownership

| KPI | Current | 90-Day Target | Owner Team |
|---|---:|---:|---|
| Unrated order share | 38.8% | <25% | Product + CRM |
| Orders >60 min | 10.54% | <7% | Operations + Dispatch |
| Uptown issue rate | ~13.22% | <10% | Regional Operations |
| Avg weekday delivery time | ~28.34 min | <25 min | Operations |
| Commission growth (monthly) | Baseline | +8% to +12% | Growth + Partner Mgmt |
| Top partner retention | Baseline | 100% retained | Partner Mgmt |

---

## 9. Risks and Mitigation

### Risk 1: Driver shortage during weekday peaks
Mitigation:
- Dynamic shift incentives.
- Forecast-based scheduling.

### Risk 2: Rating incentives reduce margin
Mitigation:
- Cap incentives and target only unrated segments.
- Compare lift versus cost in A/B tests.

### Risk 3: Over-reliance on top partners
Mitigation:
- Diversify volume through second-tier high-performing restaurants.
- Expand category campaigns beyond top 2 cuisines over time.

### Risk 4: Zone pilot results do not generalize
Mitigation:
- Use standardized experiment design and success criteria.
- Roll out incrementally with measurement gates.

---

## 10. Decisions Needed From Stakeholders

1. Approve rating participation program (product + CRM budget).
2. Approve weekday operations improvement pilot budget.
3. Approve Uptown recovery plan with dedicated owner.
4. Approve top-partner co-marketing package for next quarter.
5. Confirm weekly KPI governance cadence and executive sponsor.

---

## 11. Conclusion

MunchLink has strong market demand and healthy commission fundamentals. The next growth step is not only acquiring more orders, but improving service consistency and feedback quality so the platform can scale with confidence.

The recommended plan is focused, measurable, and practical:

- Capture more ratings,
- Reduce the slowest deliveries,
- Fix Uptown service quality,
- Grow high-value revenue through top partners and cuisines,
- Govern performance through clear KPI ownership.

Executing these actions over the next 90 days should improve customer trust, operational reliability, and revenue efficiency.

---

Confidential: Internal stakeholder use only.
