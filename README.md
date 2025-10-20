# Ad-Campaign-Analysis
In 2024, a reputable marketing agency launched two major digital advertising campaigns: Facebook Ads and Google Ads to promote the same product line.  The goal was to evaluate which platform delivers better performance, higher conversions, and greater cost efficiency.     

**SKILLS DEMONSTRATED**

· Exploratory Data Analysis

· Distribution Analysis

· Hypothesis Testing

· Linear Regression

· Time Series Analysis
 
 **TABLE OF CONTENTS**

- [BUSINESS PROBLEM](#BUSINESS-PROBLEM)
- [WHY THE NEED TO ACT](#WHY-THE-NEED-TO-ACT)
- [BUSINESS OBJECTIVES](#BUSINESS-OBJECTIVES)
- [ANALYSIS](#ANALYSIS)
- [OVERALL INSIGHTS](#OVERALL-INSIGHTS)
- [RECOMMENDATIONS](#RECOMMENDATIONS)
- [CONCLUSION](#conclusion)

# Business Problem

As a marketing agency, our goal is to help clients achieve maximum returns from their ad spend. In 2024, we launched two major advertising campaigns: Facebook and Google, both designed to drive traffic, conversions, and revenue for the same product line.

We need to determine which platform yields better results in terms of clicks, conversions, and overall cost-effectiveness.

# Why The Need To Act

Without clear visibility into which platform performs best, our marketing spend risks inefficiency and potential waste.

· Budget Misallocation: Continuing to invest evenly across both channels may not be the most effective use of resources.

· Missed Growth Opportunities: The lack of insight into platform performance prevents us from scaling the more successful campaign.

· Poor Decision-Making: Without data-driven insights, campaign optimization becomes based on assumptions rather than measurable performance trends.

By acting now, the agency can make evidence-based budget allocation decisions, improve client satisfaction, and strengthen overall campaign ROI.

# Business Objectives

1. Compare performance metrics between Facebook and Google campaigns to identify which platform generates better engagement, conversions, and ROI
2. Uncover performance patterns across days, weeks, and months to understand when and where each platform performs best.
3. Determine cost-effectiveness by analyzing metrics such as CPC and total spend across both campaigns.
4. Provide actionable recommendations for optimizing future ad budgets, targeting strategies, and platform selection.

# ANALYSIS
 
 **Exploratory Data Analysis**

 <img width="914" height="176" alt="image" src="https://github.com/user-attachments/assets/d0b27d72-60cc-44cc-b42d-7da8905382c7" />

 <img width="1710" height="362" alt="image" src="https://github.com/user-attachments/assets/68678a00-cff6-45d2-8160-86585fda6918" />

 <img width="1015" height="305" alt="image" src="https://github.com/user-attachments/assets/1a927bff-b65d-4f21-ba8a-17a5ced622d8" />

 <img width="1463" height="699" alt="image" src="https://github.com/user-attachments/assets/c7d14314-b85b-46a2-afaf-0e8abb31b75d" />

**Comparing Campaign Performance**

<img width="881" height="317" alt="image" src="https://github.com/user-attachments/assets/2cf7a367-1fa1-4ee9-9593-5d87b745de36" />

<img width="1451" height="660" alt="image" src="https://github.com/user-attachments/assets/3cc3ef25-39bb-42af-8a0d-a922972711b5" />

<img width="866" height="321" alt="image" src="https://github.com/user-attachments/assets/602cfcf0-4b5d-45b9-9889-2125ffd964be" />

<img width="1425" height="618" alt="image" src="https://github.com/user-attachments/assets/34bb38c3-8561-409b-aa38-1df2c83ab6cb" />

- Facebook ads received between 50–300 clicks most days, leading to around 5–50 conversions. This shows steady interest but fewer actions taken.
- Google ads had higher activity, with clicks ranging from 50–400 and conversions between 25–200, meaning some days performed extremely well.
- Facebook’s results were more consistent, but yielded conversions lesser than 50.
- Google performs more than Facebook in clicks and mostly conversions.
- Facebook built awareness, Google delivered conversions.

**How frequently do we observe days of a high number of conversions compared to days with a low number of conversions?**

<img width="724" height="414" alt="image" src="https://github.com/user-attachments/assets/d7e2e5c3-f8fe-463b-aa7a-60eb26ad0144" />

Data Overview of the New Category Conversions

<img width="1035" height="49" alt="image" src="https://github.com/user-attachments/assets/23353758-85a1-4b48-8e3b-3fcaf432018d" />

<img width="1152" height="565" alt="image" src="https://github.com/user-attachments/assets/99d871b9-be3c-44d6-8238-08a39bee9930" />

<img width="696" height="573" alt="image" src="https://github.com/user-attachments/assets/899f6df5-786c-4179-9094-0af6357dbfad" />

<img width="1461" height="643" alt="image" src="https://github.com/user-attachments/assets/438cdabe-59b2-4547-b547-a35963e50575" />

The chart shows that Facebook recorded a higher frequency of low-to-moderate conversion days, with most days (around 90–120 days) falling between “less than 15” and “31–45” conversions. Only a few days (less than 10) has high conversions. In contrast, Google had fewer low-conversion days but a much higher frequency of high-conversion days(over 160 days recorded more than 80 conversions).

Overall, Facebook’s conversions were frequent but smaller, while Google’s conversions were less frequent but more concentrated on very high-performance days. This means Google tends to deliver spikes of strong results, whereas Facebook maintains steadier but lower daily performance.

**Do more clicks on ads really lead to more sales?**

Correlation between clicks and conversions

<img width="802" height="268" alt="image" src="https://github.com/user-attachments/assets/277c6167-f112-44f9-9ed8-e359b4eb9b62" />

<img width="1257" height="545" alt="image" src="https://github.com/user-attachments/assets/c64fbbff-27a0-4c1f-9466-3c7c29a26e72" />

Calculating correlation co-efficient

<img width="885" height="721" alt="image" src="https://github.com/user-attachments/assets/a5bd507b-22c9-4ec6-a508-0ecd376d4902" />

The relationship between clicks and conversions is very different for the two platforms:

• **Facebook Ads**: The scatter plot shows no clear pattern. Conversions remain scattered regardless of the number of clicks. The correlation coefficient is -0.04, meaning there is virtually no relationship between the number of clicks and conversions. More clicks on Facebook ads do not necessarily lead to more sales.

• **Google Ads**: The data shows a strong upward trend. As clicks increase, conversions also rise noticeably. The correlation coefficient is 0.84, indicating a very strong positive relationship between clicks and conversions. The strong correlation between clicks on Google ads and sales suggests that Google advertising is highly effective in driving sales for the business. Increasing investment in Google ads or optimizing their performance could potentially lead to even higher sales.

**Hypothesis Testing:**

We need to know which of the advertising platforms is really effective in generating conversions.

**Null Hypothesis (H₀):** There is no difference or Facebook performs equally or better than Google.

**Alternative Hypothesis (H₁):** Google produces more conversions than Facebook.

Calculating mean coversions, t-stat and p-value

<img width="756" height="738" alt="image" src="https://github.com/user-attachments/assets/3bce545e-bcac-4aea-a660-a7872fc0a522" />

The mean number of conversions from Google ads (82.51) is substantially higher than the mean number of conversions from Facebook ads (26.13). This suggests that, on average, Google advertising is more effective in generating conversions compared to Facebook advertising. The p-value ( 0.0000) indicates strong evidence against the null hypothesis.

The results strongly support the alternate hypothesis, indicating that the number of conversions from Google advertising is indeed greater than the number of conversions from Facebook advertising.

Google advertising appears to be a more effective channel for generating conversions compared to Facebook advertising, based on the sample data analyzed.

Given the significant difference in conversion rates between Google and Facebook, consider reallocating resources towards Google advertising efforts. This could involve increasing ad spend, expanding targeting efforts, or experimenting with different ad formats to capitalize on the platform’s effectiveness in driving conversions.

**What will happen when we go with Google Ads? How many Google Ads conversions can we expect given a certain number of Google Ads clicks?**

We calculate R² score before calculating prediction, do we would know its predictive power.

Calculating R-squared score

<img width="923" height="641" alt="image" src="https://github.com/user-attachments/assets/b85a66b2-ca34-4ffc-8ff4-248d294c2e88" />

The regression model explains about 71% (R² = 0.71) of the variation in conversions using clicks.
It is fairly accurate at predicting how many conversions you can expect as clicks increase.

Correlation between Google clicks and conversions with trendline

<img width="999" height="127" alt="image" src="https://github.com/user-attachments/assets/b9d80965-fe8e-416a-8b38-9a5da04aa19e" />

<img width="873" height="614" alt="image" src="https://github.com/user-attachments/assets/3d0f9fd9-c538-4d45-9b41-f090a2a64a32" />

This shows a clear upward trend. More clicks on Google Ads generally lead to more conversions.

Prediction of the number of conversion from a specific number of clicks

<img width="759" height="67" alt="image" src="https://github.com/user-attachments/assets/52bf4cee-c811-493a-a7f8-73f375589909" />

<img width="854" height="122" alt="image" src="https://github.com/user-attachments/assets/b766df98-068e-4864-8580-441b9e6d274b" />

When Google Ads receives 100 clicks, you can expect around 34 conversions.
When clicks increase to 250, conversions are expected to rise to 88.

**Which ad platform is more cost-effective?**

<img width="1090" height="540" alt="image" src="https://github.com/user-attachments/assets/cc6703bb-5ba0-4db7-83f4-aba406f3c3e5" />

<img width="767" height="556" alt="image" src="https://github.com/user-attachments/assets/08e31c98-2f12-47c0-9f2a-ea0a3de09251" />

Average CPC for Google Ads is less than Average CPC for Facebook. Hypothesis testing will be carried out for further analysis to ascertain whether Google Ads really has a lower CPC than Facebook Ads.

**Hypothesis Testing**

Null Hypothesis (H₀): Google Ads’ CPC is greater than or equal to Facebook’s CPC.
Alternative Hypothesis (H₁): Google Ads’ CPC is less than Facebook’s CPC.

<img width="802" height="362" alt="image" src="https://github.com/user-attachments/assets/582e68d5-fb63-463b-b49b-09e4e75f65f6" />

<img width="482" height="105" alt="image" src="https://github.com/user-attachments/assets/e6eb48f9-3284-4605-9888-972cd0d93b88" />


The mean CPC from Facebook ads ($7.24) is substantially higher than the mean CPC from Google ads ($2.73). This suggests that, on average, Google advertising is more cost-effective in generating conversions compared to Facebook advertising. The p-value ( 0.0000) indicates strong evidence against the null hypothesis.

The results strongly support the alternate hypothesis, indicating that the Google CPC is less than the Facebook CPC
Google advertising appears to be a more cost-effective channel for generating conversions compared to Facebook advertising, based on the sample data analyzed.

**ANALYZING CAMPAIGN METRICS OVER TIME**

**At what times of the month or days of the week do we experience conversions?**

<img width="942" height="625" alt="image" src="https://github.com/user-attachments/assets/31c8522a-ef94-4fe7-bacd-8d1e31bde0c8" />

<img width="1610" height="632" alt="image" src="https://github.com/user-attachments/assets/22e292a3-6ea2-4fab-b668-ec13fc0434e6" />

Day-of-the-Week Trends:

• Conversions peak on Tuesdays, suggesting strong engagement early in the week, likely when campaigns and audiences are most active.

• There is a gradual decline from Wednesday to Friday, with Friday recording the lowest weekday conversions.

• Conversions pick up again during the weekend (Saturday and Sunday), showing renewed interest,possibly from leisure-time browsing or weekend offers.

Audience engagement is strongest early in the week (Tuesday) and again on weekends, indicating these are prime days to schedule campaigns or allocate higher budgets.

<img width="1599" height="640" alt="image" src="https://github.com/user-attachments/assets/ccaa0ac8-90cf-46a3-91f4-f8deba554e0e" />

Month-by-Month Trends:

• Conversions remain relatively stable from January to June, showing consistent campaign performance in the first half of the year.

• A notable surge occurs in August and September, reaching the highest conversion levels, possibly driven by seasonal promotions or back-to-school marketing periods.

• Conversions dip in October and November, then rebound slightly in December, which may reflect changing ad strategies or audience fatigue before year-end campaigns.

Late summer to early fall (August–September) delivers the strongest conversion performance, suggesting this period has the best responsiveness.

**How does CPC trend over time?**

<img width="686" height="247" alt="image" src="https://github.com/user-attachments/assets/a2472a4d-9950-4cbd-b8be-48835e55031d" />

<img width="1583" height="632" alt="image" src="https://github.com/user-attachments/assets/9178e76d-da9a-421d-bb01-cbe0e02ff839" />

- March records the highest CPC, suggesting a period of intense competition, likely due to seasonal campaigns or increased ad
spending early in the year.

- After March, CPC stabilizes between April and August, indicating a relatively consistent and efficient ad performance period.

- A sharp dip in September points to reduced competition, which may present an opportunity for cost-efficient ad placements.

- CPC rises again in October and November, aligning with Q4 marketing pushes (e.g., holiday promotions and end-of-year sales).

- December sees another decline, possibly as campaigns wind down and budgets are exhausted.

CPC trends suggest cyclical ad competition, peaking in March and Q4, with lower-cost opportunities in September and December for
advertisers seeking to maximize ROI.

# OVERALL INSIGHTS

Google Ads clearly outperformed Facebook Ads across all key metrics; more clicks, higher conversions (avg. 82 vs. 26), and a stronger click-to-conversion link (correlation = 0.84).

Facebook Ads delivered consistent but lower conversions, showing limited impact on driving sales.

Google Ads proved more cost-efficient, with a significantly lower CPC ($2.73 vs. $7.24).

Conversions peaked on Tuesdays and weekends, with August–September being the most productive months.

High CPC periods: March, October, and November due to increased ad competition.


# RECOMMENDATIONS

1. Reallocate Budget Strategically:

Prioritize Google Ads for conversion-driven campaigns, allocating 60–70% of total ad spend to capitalize on its stronger ROI and cost efficiency.
Maintain 30–40% for Facebook Ads to sustain brand awareness and consistent audience engagement.

2. Optimize Campaign Timing:

Schedule major ad pushes on Tuesdays and weekends, when engagement is highest.
Plan major promotions or launches in August–September, leveraging peak conversion months.

3. Cost Management:

Reduce spend during high CPC months (March, October, November) or focus on campaigns with higher ROI potential during those periods.
Increase ad activity in September and December to benefit from lower CPC and reduced competition.

4. Performance Optimization:

For Facebook: Test new ad creatives, refine audience targeting, or experiment with retargeting to improve conversion rates.
For Google: Continue investing in high-performing keywords and expand successful ad groups.

5. A/B Testing & Predictive Modeling:

Conduct ongoing A/B tests to refine campaign creatives, audiences, and bidding strategies.
Use regression insights to predict future conversions and guide budget allocation dynamically based on expected performance.


# CONCLUSION

Google Ads is the stronger, more cost-effective platform for driving conversions and ROI.
Facebook remains useful for consistent engagement and brand awareness, but Google delivers higher performance and efficiency.
A balanced, data-driven allocation strategy between both platforms will enhance campaign results, optimize budget use, and improve client ROI.

 



 






 









