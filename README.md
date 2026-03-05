# Khan Academy User Retention Analysis

Analysis of month 1 behavioral patterns and their relationship to month 3 retention for a cohort of 7,612 users.

## Overview

This project examines user engagement patterns in the first month and identifies factors associated with long-term retention. The analysis reveals key insights about user behavior segmentation, the impact of registration on retention, and acquisition channel quality differences.

## Key Findings

- **Baseline retention:** 10.3% of users remain active at month 3
- **Long-tail distribution:** 60% of users visit once and never return; 25% have zero activity
- **Registration impact:** Registered users retain at 2x the rate of unregistered users (18.6% vs 9.3%, p<0.001)
- **Consistency matters:** Days active shows strongest correlation with retention (r=0.094, p<0.001)
- **Traffic quality varies:** Organic search (59% of users) has lowest retention at 9.5%

## Analysis Approach

1. **Data Processing:** Aggregated 16,394 event-level activity records to 5,684 user-level profiles
2. **Exploratory Analysis:** Examined engagement distributions and user segmentation patterns
3. **Statistical Testing:** Compared retained vs not retained users using t-tests and chi-square tests
4. **Correlation Analysis:** Quantified relationships between behaviors and retention
5. **Segmentation:** Analyzed retention across user types, channels, and content choices

## Recommendations

1. **Encourage multi-day engagement** through day 2 email interventions and streak gamification
2. **Simplify registration** with prompts after first success and one-click social login
3. **Optimize acquisition** toward higher-quality channels (email, direct) vs organic search volume
4. **Expand parent segment** through targeted features and acquisition

## Technical Stack

- **Python:** pandas, numpy, scipy
- **Visualization:** matplotlib, seaborn
- **Statistical Methods:** t-tests, chi-square tests, Pearson correlations

## Files

- `User_Behavior_and_3_Month_Retention_Analysis.ipynb` - Complete analysis notebook
- `images/` - Key visualizations from the analysis

## Contact

Victoria McCray | [LinkedIn](https://linkedin.com/in/victoria-mccray-99399514a) | [Website](https://victoriamccray.github.io/)

---

*Note: This was a take-home assignment for a data science role. Data provided by Khan Academy for evaluation purposes.*
