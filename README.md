# Ad-Campaign-Analysis
In 2024, a reputable marketing agency launched two major digital advertising campaigns: Facebook Ads and Google Ads to promote the same product line.  The goal was to evaluate which platform delivers better performance, higher conversions, and greater cost efficiency.     

**Analysis done:**

· Exploratory Data Analysis

· Distribution Analysis

· Hypothesis Testing

· Linear Regression

· Time Series Analysis

**Business Problem**

As a marketing agency, our goal is to help clients achieve maximum returns from their ad spend. In 2024, we launched two major advertising campaigns: Facebook and Google, both designed to drive traffic, conversions, and revenue for the same product line.

We need to determine which platform yields better results in terms of clicks, conversions, and overall cost-effectiveness.

**Why The Need To Act**

Without clear visibility into which platform performs best, our marketing spend risks inefficiency and potential waste.

· Budget Misallocation: Continuing to invest evenly across both channels may not be the most effective use of resources.

· Missed Growth Opportunities: The lack of insight into platform performance prevents us from scaling the more successful campaign.

· Poor Decision-Making: Without data-driven insights, campaign optimization becomes based on assumptions rather than measurable performance trends.

By acting now, the agency can make evidence-based budget allocation decisions, improve client satisfaction, and strengthen overall campaign ROI.

**Business Objectives**

Compare performance metrics between Facebook and Google campaigns to identify which platform generates better engagement, conversions, and ROI
Uncover performance patterns across days, weeks, and months to understand when and where each platform performs best.
Determine cost-effectiveness by analyzing metrics such as CPC and total spend across both campaigns.
Provide actionable recommendations for optimizing future ad budgets, targeting strategies, and platform selection.

**ANALYSIS**
 
 **Exploratory Data Analysis**

 <img width="914" height="176" alt="image" src="https://github.com/user-attachments/assets/d0b27d72-60cc-44cc-b42d-7da8905382c7" />

 <img width="1710" height="362" alt="image" src="https://github.com/user-attachments/assets/68678a00-cff6-45d2-8160-86585fda6918" />

 <img width="1015" height="305" alt="image" src="https://github.com/user-attachments/assets/1a927bff-b65d-4f21-ba8a-17a5ced622d8" />

 <img width="1463" height="699" alt="image" src="https://github.com/user-attachments/assets/c7d14314-b85b-46a2-afaf-0e8abb31b75d" />

**Comparing Campain Performance**

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








 









