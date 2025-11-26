# E-news-Express-Project


# A/B Testing Analysis of Landing Page Design — E-News Express

This project examines user engagement and subscription conversion data from E-News Express to determine whether a redesigned landing page leads to better user behavior and subscription rates. The goal was to evaluate whether the new landing page performs better than the existing one, using exploratory analysis and statistical hypothesis testing.

## Business Context

E-News Express has seen a decline in new subscriber growth. There was a concern that the existing landing page was not engaging enough to encourage conversions. The purpose of this study was to determine whether a newly designed landing page results in longer engagement time and higher subscription rates.


## Dataset Overview

- 100 users total  
- 6 columns  
- Contains both numerical and categorical variables  
- No missing values  
- No duplicate entries  


## Key Findings

### Engagement and Time on Page
- Users exposed to the new landing page spent noticeably more time on the page.
- Engagement time is significantly higher among converted subscribers compared to non-converted users.


### Landing Page Performance
Hypothesis tests showed:
- The mean time spent on the new page is significantly higher than on the old page (p-value ≈ 0.000139).  
- The conversion rate for the new landing page is significantly higher than for the old one (p-value ≈ 0.0080).  


### Effect of Language
- No statistically significant difference in conversion rates across language groups (English, French, Spanish).
- Time spent on page did not vary meaningfully by language.


## Recommendations

- Fully deploy the new landing page as the default, as it clearly improves engagement and conversions.
- Do not invest heavily in language-specific landing page versions, since language did not significantly impact engagement or conversion.
- Continue running A/B tests for incremental improvements, including personalization or targeted subscription prompts.


## Approach

- Performed EDA to investigate distributions of user engagement.
- Conducted hypothesis testing including Welch’s t-test, two-proportion Z-test, Chi-Square, and ANOVA to quantify differences between groups.
- Interpreted results in terms of business impacts and customer interaction patterns.


## Author

Sanjana Addanki  
A/B Testing Evaluation — E-News Express


## Repository Structure

