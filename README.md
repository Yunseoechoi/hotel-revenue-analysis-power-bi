# Hotel Revenue Analysis PowerBI
## Executive Summary:

The hotel's stakeholders want to know whether revenue is growing, whether parking capacity should expand, and what broader trends exist in booking behavior. To answer these, I built a database of hotel booking data and a Power BI dashboard tracking revenue, Average Daily Rate(ADR), nights stayed, discounts, and parking.

**Findings**

**Revenue growth:** Revenue peaked in 2019, growing almost 410%. Driven mainly by booking volume and longer stays. Then revenue dropped roughly 36% in 2020 as daily rates increased.

**Parking:** Only 2.36% of guests used parking, and it stayed steady through each month. This suggests the current lot size is not a revenue constraint.

**Trends:** Lower revenue in Jan and Feb, discounts did not improve revenue, and revenue began growing in 2018. 


## Business Problem

Hotel revenue depends on booking volume, pricing, and add-on services like parking. Stakeholders want to know the following:

1. Is our hotel revenue growing by year?
2. Should we increase our parking lot size?
3. What trends can we see in the data?

How can we use the data to answer these questions and decide where to focus pricing and capacity investments?

## Methodology
[SQL queries that extract, clean, and transform the booking data in a database.]
A Power BI dashboard that tracks revenue, ADR, nights stayed, discounts, and parking usage over time.
[Optional: a Python analysis to test the impact of changes, such as how a 1% increase in ADR or in average length of stay would change revenue.]
Skills

SQL: [CTEs, joins, CASE statements, aggregate functions]
Power BI: [DAX, calculated columns and measures, data modeling, ETL in Power Query, data visualization]
Python: [Pandas, Matplotlib, NumPy, statistics]

List only the tools you actually used. Interviewers often ask follow-up questions on anything in this section.

## Results & Business Recommendations

The dashboard gives stakeholders visibility into hotel performance overall and by [year / month / customer segment], so they can answer questions on their own instead of requesting one-off reports. [Include a time-saved claim only if it's true.]

The analysis showed that:

Revenue growth: Revenue [grew/declined] by [X%] from [year] to [year], driven mainly by [ADR / booking volume / longer stays].
Parking: [X%] of bookings included parking, and usage peaked at [X% of capacity] in [month]. This suggests [the current lot is / is not] limiting revenue.
Trends: [Seasonal peak in X], [discounts did / did not increase revenue], and [longer stays generated X% more revenue per booking].

Because the biggest revenue opportunities appear to be in [your top two drivers], I recommend:

[Adjust pricing or discounts in peak months to raise ADR.]
[Expand / hold off on expanding parking, based on utilization data.]
[Promote longer-stay packages or offers.]
[Upsell parking and other add-ons at the point of booking.]

I believe these adjustments will best capture the largest revenue opportunities with the smallest operational changes.

## Next Steps
[A/B test discount levels or promotions.]
[Track parking utilization for a full year before committing to expansion.]
[Measure the impact of longer-stay offers on revenue per booking.]
