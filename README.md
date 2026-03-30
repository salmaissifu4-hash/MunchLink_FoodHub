# MunchLink Food Hub Analysis

## Project Overview
This repository contains a business analysis project for MunchLink Food Hub, a food delivery platform operating across multiple city zones. The project uses order-level data to examine customer behavior, restaurant performance, delivery efficiency, service issues, and platform commission revenue.

The analysis is designed to move beyond simple description of the data and provide practical business insights that can support better operational and strategic decision-making.

## Main File
- `MunchLink_Analysis.ipynb` — the main notebook containing the full analysis, visualizations, interpretations, and final findings.

## Business Questions Answered
The notebook focuses on key questions including:
- How many customers do not leave ratings?
- Which restaurants receive the highest number of orders?
- Which cuisine types are most popular, especially on weekends?
- What percentage of orders are high-value orders?
- What is the average delivery time?
- How does delivery performance differ between weekdays and weekends?
- Which delivery zones experience the most service issues?
- Which cuisine categories generate the most commission revenue?

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Insights
- 736 orders, representing 38.8% of all orders, have no customer rating.
- 10.54% of orders exceed the 60-minute fulfillment threshold.
- Shake Shack is the top restaurant by order volume with 219 orders.
- American cuisine is the strongest-performing cuisine category and leads weekend demand.
- Average delivery time is 24.16 minutes.
- Total platform commission revenue is $6,166.50.
- Weekday deliveries are slower than weekend deliveries.
- Uptown records the highest service issue rate among delivery zones.

## Business Recommendations
- Improve the customer rating process to reduce the high volume of unrated orders.
- Investigate and reduce the share of orders that exceed 60 minutes.
- Focus operational improvement efforts on Uptown, where service issues are highest.
- Strengthen partnerships with top-performing restaurants.
- Use high-demand cuisines such as American and Japanese for targeted promotions.
- Increase focus on high-value orders because they contribute more strongly to commission revenue.

## How to Run
1. Open `MunchLink_Analysis.ipynb` in VS Code or Jupyter Notebook.
2. Ensure the dataset file is available in the expected project location.
3. Run the notebook from top to bottom.
4. Review the visualizations, result explanations, and summary findings.

## Project Outcome
This project provides a clear view of how MunchLink is performing across customer feedback, restaurant demand, delivery operations, and revenue generation. It highlights both strengths and areas that need improvement, making it useful as a business intelligence and decision-support document.
