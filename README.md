# gym-retention-analysis
- This project analyzes gym member data to identify key factors driving customer churn. The goal is to uncover patterns in member behavior and provide actionable recommendations to improve retention.

##  Business Problem

- Gym management wants to understand:

- Which members are most likely to churn
- What factors contribute to churn
- How to improve retention and long-term membership value
   ## Dataset

The dataset includes:

- Age
- Membership Type (Monthly, Quarterly, Yearly)
- Visits Per Month
- Churn Status (Yes/No)
   ##Tools Used
- SQL (Google BigQuery)
- Google Sheets / Excel
- Tableau (for visualization)
   ## Key Analysis Performed
- Churn rate by age group
- Churn rate by membership type
- ombined analysis (Age Group + Membership Type)
- verage visits vs churn behavior
   ## Key Insights
- Members 40+ had the highest churn rate (~28.8%)
- Quarterly memberships (40+) had the highest churn overall (35%)
- Monthly memberships showed consistently high churn across age groups (~29–31%)
- Visit frequency differences were not as significant as expected
   ## Recommendations
- Incentivize members to switch from monthly → yearly plans
- Introduce loyalty perks for 40+ age group
- Investigate why quarterly plans underperform (pricing, commitment, or value)
- Conduct surveys targeting high-risk churn groups
## Conclusion

From my analysis, membership type stood out as the strongest driver of churn — more than age or visit frequency.
Members on monthly and quarterly plans consistently had higher churn rates across all age groups. While the 40+ group did show elevated churn overall, the data suggests that the level of commitment tied to the membership plays a bigger role than demographics or usage alone.
Based on this, there’s a clear opportunity to improve retention by encouraging more members to transition into longer-term plans, which could lead to stronger long-term engagement and customer value.
