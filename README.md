Objective
The objective of this analysis is to understand customer retention trends over with cohort analysis based on recorded columns such as event time and user ID. From this analysis,
the business can realize how long customers remain engaged from their first action and can highlight potential areas to improve in retention strategies.

Data Cleaning Steps
(a) Fill null values in string columns with "unknown" to avoid missing data.
(b) Remove UTC timezone from event_time using dt.tz_localize(None) for consistency.
(c) Rename all columns for readability.
(d) Convert event time column to datetime format for analysis.

Cohort Analysis Insight
(a) The business acquired a large number of customers in Month 1 across all cohorts.
(b) Retention drops fast after the first month, from 100% to 6% in Month 2 in September 2020.
(c) By Month 6, retention reaches to 0%, that point out almost no customers are active. 
(d) Overall retention rate is significantly low compared to other months that highlight to plan an effective strategy for customer engagement.

Recommentations
To improve customer retention,
The business should address customer complaints and increase satisfaction.
Check pricing and product quality to meet customer expectations.
Leverage personalized marketing and loyalty programs to enhance customer engagement.
Collect data from customer feedbacks to identify problems which customers face and implement sutiable strategy for long-term retention.
