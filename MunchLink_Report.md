# MunchLink Food Hub
## Public Project Report

Data source: munchlink_orders_enhanced.csv  
Analysis basis: MunchLink_Analysis.ipynb  
Dataset size: 1,898 orders

---

## Project Purpose

This project analyzes food delivery order data to understand customer demand, delivery performance, ratings behavior, and commission patterns.

The goal is to turn raw order data into simple business insights that show:

- what customers order most often,
- where delivery performance is strongest or weakest,
- how ratings behave,
- and which parts of the business generate the most value.

---

## Key Findings

## 1. Demand is concentrated in a few cuisines and restaurants

- American cuisine leads total order volume.
- Weekend demand is much higher than weekday demand.
- A small number of restaurants account for a large share of total orders.

What this means:
MunchLink demand is not evenly spread across the platform. A few categories and partners drive much of the activity.

## 2. Delivery performance is acceptable on average, but extreme delays still matter

- Average delivery time is about 24 minutes.
- Average total fulfillment time is about 51 minutes.
- Roughly 10.5% of orders exceed 60 minutes end-to-end.

What this means:
The overall system performs reasonably well, but a meaningful slow-order tail still affects customer experience.

## 3. Customer feedback is incomplete

- Around 38.8% of orders do not have a rating.
- Among rated orders, scores are generally high.

What this means:
Customers who rate are usually satisfied, but the large share of missing ratings means the platform does not see the full picture.

## 4. Service quality differs by location

- Uptown shows the highest service issue rate.
- Other zones perform better and more consistently.

What this means:
Operational challenges are not evenly distributed. Some areas need more attention than others.

## 5. Revenue is driven by strong categories and higher-value orders

- American cuisine generates the highest commission contribution.
- Higher-value orders contribute disproportionately to commission revenue.

What this means:
Business value depends not only on order count, but also on order mix and customer basket size.

---

## Business Interpretation

This project shows a common marketplace pattern:

- a few demand drivers create most of the volume,
- average performance can hide weak outliers,
- and incomplete customer feedback makes improvement harder.

For a delivery platform, strong growth depends on both scale and consistency.

In simple terms:
- popular categories should be protected,
- slow-order risk should be reduced,
- and better feedback collection would improve decision-making.

---

## Literature Connection (Recent and Real)

The findings in this project are consistent with recent research in customer experience, digital platforms, and online food delivery.

### Customer experience across touchpoints
Lemon and Verhoef (2016) explain that customer experience is shaped across the full journey, not at one single point.

Connection to this project:
- order placement, delivery time, and post-delivery rating are all important touchpoints.

### Digital feedback and decision systems
Kannan and Li (2017) show that digital businesses need strong customer feedback loops to improve performance.

Connection to this project:
- the high share of unrated orders limits how well platform decisions can be guided by real customer signals.

### Online food delivery behavior
Yeo, Goh, and Rezaei (2017) find that customer experience strongly affects attitudes and intention to reuse online food delivery services.

Connection to this project:
- delays and service inconsistency likely affect repeat usage more than averages alone suggest.

### Reviews and marketplace trust
Luca (2016) shows that reviews and ratings influence demand and trust in digital marketplaces.

Connection to this project:
- better rating participation would improve platform transparency and partner evaluation.

### Delivery market economics
McKinsey (2021) notes that food delivery growth depends on operational efficiency and retention, not just order expansion.

Connection to this project:
- the most useful next step is quality-led growth, not volume growth alone.

---

## Practical Lessons From the Project

This project highlights five useful lessons for business analytics:

1. Averages alone are not enough. Outliers often matter more.
2. Missing customer feedback can weaken the value of otherwise strong data.
3. Geographic breakdowns help reveal hidden operational issues.
4. Revenue quality matters as much as order quantity.
5. Simple, well-explained findings can be more useful than overly technical output.

---

## Conclusion

MunchLink appears to be a strong platform with healthy demand, but its long-term performance depends on consistency.

The data suggests that the most important opportunities are:

- reducing severe delays,
- improving visibility through better ratings capture,
- and focusing attention on the zones and categories that matter most.

This makes the project a good example of how business analytics can move from description to action.

---

## References

1. Lemon, K. N., and Verhoef, P. C. (2016). Understanding Customer Experience Throughout the Customer Journey. Journal of Marketing.
2. Kannan, P. K., and Li, H. "Alice" (2017). Digital Marketing: A Framework, Review and Research Agenda. International Journal of Research in Marketing.
3. Yeo, V. C. S., Goh, S.-K., and Rezaei, S. (2017). Consumer Experiences, Attitude and Behavioral Intention Toward Online Food Delivery Services. Journal of Retailing and Consumer Services.
4. Luca, M. (2016). Reviews, Reputation, and Revenue: The Case of Yelp.com. Harvard Business School Working Paper.
5. McKinsey and Company (2021). Ordering In: The Rapid Evolution of Food Delivery.
