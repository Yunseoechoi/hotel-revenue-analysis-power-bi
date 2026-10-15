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
SQL queries that extract, clean, and transform the booking data in a database. A Power BI dashboard that tracks revenue, ADR, nights stayed, discounts, and parking usage over time.

SQL: CTEs, joins, aggregate functions

Power BI: Data visualization, DAX, calculated columns and measures

Excel: Import Data

## Results & Business Recommendations

The dashboard gives stakeholders visibility into hotel performance overall and by year, so they can answer questions on their own instead of requesting one-off reports. 

The analysis showed that:

Revenue growth: Revenue peaked in 2019 by roughly 400% compared to previous years. Later dropped by 36% in 2020. The trend is driven by booking volume and longer stays. 
Parking: 2.36% of bookings included parking, and usage peaked at 2.5% in the later quarter of the year. This suggests the current lot is not limiting revenue.
Trends: More sales during the later months of the year, discounts did not increase revenue, and resort hotels fluctuate more in revenue while city hotels are more consistent.

Because the biggest revenue opportunities appear to be in the longer stays, I recommend:

Adjust discounts in peak months to raise the ADR.
Hold off on expanding parking. 
Promote longer-stay packages and offers.

I believe these adjustments will best capture the largest revenue opportunities with the smallest operational changes.

## Next Steps
Measure the impact of longer-stay offers on revenue per booking.
Find factors that caused the surge of longer stays starting in 2018.
