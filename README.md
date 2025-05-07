# Explore-hypothesis-testing
#### Introduction
You work for an environmental think tank called Repair Our Air (ROA). ROA is formulating policy recommendations to improve the air quality in America, using the Environmental Protection Agency's Air Quality Index (AQI) to guide their decision making. An AQI value close to 0 signals "little to no" public health concern, while higher values are associated with increased risk to public health.

They've tasked you with leveraging AQI data to help them prioritize their strategy for improving air quality in America.

ROA is considering the following decisions. For each, construct a hypothesis test and an accompanying visualization, using your results of that test to make a recommendation:

ROA is considering a metropolitan-focused approach. Within California, they want to know if the mean AQI in Los Angeles County is statistically different from the rest of California.
With limited resources, ROA has to choose between New York and Ohio for their next regional office. Does New York have a lower AQI than Ohio?
A new policy will affect those states with a mean AQI of 10 or greater. Will Michigan be affected by this new policy?
Notes:

For your analysis, you'll default to a 5% level of significance.
Throughout the lab, for two-sample t-tests, use Welch's t-test (i.e., setting the equal_var parameter to False in scipy.stats.ttest_ind()). This will account for the possibly unequal variances between the two groups in the comparison.
