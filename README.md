# AB-Testing-Demo

## Overview
This project demonstrates A/B testing by comparing two simulated datasets for evaluating interview sucess rate. The goal is to determine if the new strategy (Group B) results in a higher success rate compared to the standard strategy (Group A), and to use statistical methods to evaluate the significance of any observed differences.

### Key Concepts:
- **A/B Testing**: A methodology used to to determine which one performs better. Group A represents the control (standard method), and Group B represents the treatment (new method).
- **Statistical Significance**: A t-test is employed to see whether the difference between the two groups’ performance is statistically significant, which means the observed difference is likely not due to random chance.

## Process Description
1. **Data Simulation**:
   I created a simulated dataset that represents the outcomes of 100 candidates in each group. Group A followed the standard interview preparation strategy, while Group B followed a new strategy. I simulated a 55% success rate for Group A and a 65% success rate for Group B to reflect a realistic scenario where the new strategy is hypothesized to perform better.

2. **Success Rate Calculation**:
   I calculated the average success rate for both groups to get a clear picture of how well each strategy performed. Group B’s success rate was higher, but it’s essential to determine whether this difference is statistically significant, not just due to random variation.

3. **Statistical Testing**:
   To test the hypothesis that the new interview preparation strategy leads to better performance, I performed a t-test. This statistical test compares the means of the two groups to see if the difference is significant enough to draw conclusions. The resulting p-value helps to determine whether the null hypothesis (that there is no difference between the two strategies) can be rejected.

4. **Result Interpretation**:
   Based on the p-value from the t-test, I interpreted whether the difference between Group A and Group B was significant. If the p-value was below the threshold (typically 0.05), I could reject the null hypothesis and conclude that the new strategy leads to a statistically significant improvement in success rates.

## Learnings and Application to Future Analysis
This A/B testing process helped solidify my understanding of how to:
- How A/B testing works.
- Use a t-test to determine whether observed differences between groups are statistically significant.

Understanding this concept is crucial for analyzing real-world experiments where decisions need to be data-driven. By applying this methodology, I am better prepared to analyze experiments in other domains, such as product changes, marketing strategies, or website optimizations, where A/B testing is commonly used to evaluate performance improvements.
