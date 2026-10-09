**Overview**

Housing has become less affordable relative to income in many parts of the United States, but some counties have experienced greater changes than others. This project aims to measure how housing affordability changed across U.S. counties between 2015–2019 and 2020–2024 and identify the economic and demographic factors associated with these changes.

We will combine county-level data from Zillow’s Home Value Index, the Census Bureau’s American Community Survey (ACS) five-year estimates, and the Bureau of Labor Statistics’ Local Area Unemployment Statistics. We will also use mortgage rate and Consumer Price Index data from FRED to estimate mortgage payments and adjust monetary values for inflation. These datasets will be combined using county FIPS codes and time periods.

Our approach will involve downloading and cleaning the datasets, checking for missing counties and inconsistent identifiers, evaluating ACS margins of error, and converting monetary values to 2024 dollars. We will then calculate price-to-income and mortgage payment-to-income ratios to compare affordability across counties and periods. Using summary statistics, county-level maps, and regression analysis, we will examine which counties experienced the largest affordability changes and how these changes relate to local economic and demographic conditions.

Finally, we will document our variables and build a reproducible Python pipeline so that others can run the analysis and verify our results.



○ Team: Clearly define team member roles and planned responsibilities.
-Eman worked on Overview and Business Questions

○ Research or Business Question(s): How did housing affordability change across U.S. counties between 2015–2019 and 2020–2024? We will measure affordability using the ratio of typical home value to median household income and an estimated annual mortgage payment-to-income ratio.

Type	Generic template
Relationship: Is there a relationship between [variable from A] and [variable from B] across [geographic unit]?
Trend over time: How has [measure] changed from [year] to [year], and does it differ by [group/region]?
Comparison: How do [regions/groups] differ in [outcome] after accounting for [factor from dataset C]?
Influencing factors: Which of [factor X, Y, Z] is most associated with [outcome]?
Hotspots/disparities: Which [areas/entities] have the highest [outcome] relative to [context variable]?
Impact of an event: Did [event, policy, or season] coincide with a change in [outcome]?
Business framing: Where should [an organization] focus resources to improve [outcome], given [conditions]?
