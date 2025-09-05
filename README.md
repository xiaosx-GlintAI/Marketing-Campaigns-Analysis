# Marketing Campaign Analysis

## 1. Project Overview

This repository contains a detailed analysis of a **marketing campaign dataset**, aimed at uncovering actionable insights to drive strategic decisions. Using **Python** and key data science libraries, this project evaluates **campaign effectiveness** by dissecting user conversion funnels, **retention rates**, and the **impact of various marketing strategies**. The analysis is presented from the perspective of a Marketing Data Analyst, focusing on translating data into measurable business impact.

## 2. Key Business Questions Addressed

This analysis was designed to answer critical questions for the marketing team:

- **Overall Performance**: What are the baseline conversion and retention rates for our campaigns?

- **Segmentation Analysis**: How do conversion rates vary across different marketing channels, user languages, and age demographics?

- **Temporal Patterns**: Are there specific days of the week where marketing efforts yield higher returns?

- **Anomaly Detection**: Can we identify and quantify the business impact of technical glitches or unexpected campaign behavior?

- **A/B Testing**: Was a personalization strategy in the email channel effective, and was the result statistically significant?

## 3. Methodology

The project followed a structured analytical approach:

- **Data Preparation**: The raw dataset was loaded using pandas, where date columns were parsed and new features, like day_of_week, were engineered to enrich the analysis.

- **Exploratory Data Analysis (EDA)**: Core marketing KPIs were calculated and visualized using matplotlib. The data was then segmented to compare performance across different user cohorts and channels.

- **Bug Impact Analysis**: A significant drop in performance for the "House Ads" channel was investigated.

  - **Diagnosis**: The root cause was identified as a technical bug that served ads in the incorrect language to non-English speaking users.

  - **Quantification**: A pre-bug performance benchmark was established to forecast expected conversions. The financial impact was then quantified by calculating the difference between expected and actual subscribers during the bug period.

- **Statistical A/B Test Analysis**: The effectiveness of a personalization test in the email channel was rigorously evaluated.

  - **Performance Lift**: Conversion rates for the control and personalization groups were calculated to determine the percentage lift.

  - **Statistical Significance**: A t-test was conducted using SciPy to confirm that the observed improvement was not due to random chance.

## 4. Key Findings & Actionable Insights

This analysis yielded several high-impact insights that can directly inform marketing strategy:

- **Insight 1: Personalization Drives Conversions**

  The A/B test demonstrated that the personalized email campaign variant resulted in a 41.54% lift in conversions. This result was statistically significant, providing a clear business case for investing further in personalization technology and strategies.

- **Insight 2: Technical Bugs Have a Measurable Financial Impact**

  A bug that served incorrectly localized "House Ads" was found to have caused a direct loss of approximately 1,200 potential subscribers over a 20-day period. This finding underscores the critical need for robust QA processes in marketing operations to protect revenue.

- **Insight 3: Channel Performance is Time-Sensitive**

  Analysis revealed that conversion rates for different marketing channels peaked on different days of the week. This allows for the optimization of ad spend by scheduling campaigns on the days they are most likely to be effective.

## 5. Technologies Used

  **Python**: Core language for analysis.

  **Pandas**: For data manipulation, cleaning, and aggregation.

  **NumPy**: For efficient numerical computations.

  **Matplotlib**: For creating static, high-quality visualizations.

  **SciPy**: For conducting statistical significance testing (t-test).

## 6. Analysis Report

<img width="690" height="873" alt="image" src="https://github.com/user-attachments/assets/1a861d3c-1a0d-4cb2-a9e1-7fba1dec8c82" />

<img width="689" height="594" alt="image" src="https://github.com/user-attachments/assets/f875019d-66b3-4449-934b-d60aa873f8a7" />

<img width="674" height="792" alt="image" src="https://github.com/user-attachments/assets/d1b63227-697a-4c9e-befc-dcd3fe0b8cf3" />

<img width="648" height="879" alt="image" src="https://github.com/user-attachments/assets/71a42a0c-ebce-48a0-b75e-fbe0ff3e448c" />

<img width="658" height="532" alt="image" src="https://github.com/user-attachments/assets/230d024d-79a5-4c79-bf7e-7c1fc7d80395" />

<img width="648" height="869" alt="image" src="https://github.com/user-attachments/assets/4f3afdc9-b0fb-4ba2-a427-19aecd41ae76" />

<img width="646" height="408" alt="image" src="https://github.com/user-attachments/assets/8cabf0da-7e48-4e45-89d0-c18f513eb673" />








