<div align="center">
  <h1>EduPulse: Product-Led Growth & Churn Analytics</h1>
  <p>Comprehensive unit economy audit, acquisition channel analysis, and Aha-moment discovery for an EdTech platform</p>
  
  [![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org)
  [![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458.svg)](https://pandas.pydata.org/)
  [![Seaborn](https://img.shields.io/badge/Seaborn-Data_Visualization-388E3C.svg)](https://seaborn.pydata.org/)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
</div>

*Читать на [Русском](README.md).*

## Business Context and Solution Architecture
EduPulse is an educational platform operating on a subscription model. The project faced a classic scaling challenge: the need to strictly optimize the marketing budget while reducing customer churn. My goal in this research was to translate raw behavioral data of 1200 users into clear management decisions.

I conducted a deep audit of acquisition channels to identify traffic sources that generate the most loyal paying customers. Then, I discovered the product's Aha-moment - the core action after which a user is most likely to stick with the app long-term. Finally, I localized the technical barriers provoking churn and visualized the results on a single dashboard.

## Key Metrics and Insights
The funnel and cohort analysis revealed several critical growth points.

First, the marketing budget was spent inefficiently. VK Ads brought in an audience with an extremely high churn rate. Meanwhile, Telegram and organic traffic generated the core paying user base.

Second, I uncovered the product's Aha-moment. The metrics showed that once a user completes exactly three courses, their probability of churning drops to almost zero. This is a crucial benchmark for the product team.

Third, churn correlates directly with support tickets. Users do not forgive bugs. Every support request decreases loyalty, which is confirmed by a sharp drop in NPS.

## Project Structure
The entire analytical pipeline is consolidated in a single Jupyter Notebook `project_revise.ipynb`. The code covers the full data lifecycle: from cleaning the raw dataset `edupulse_users.csv` to calculating cohorts, correlation matrices, and generating the final visual dashboard `eda_dashboard.png`.

## Business Action Plan
Based on the numbers, I have formulated a specific action plan.

The advertising budget must be reallocated immediately. VK Ads funding should be cut and redirected to the Telegram channel.

The product team needs to focus heavily on onboarding. The primary goal is to guide every new user by the hand until they reach the three-course milestone. Additionally, a system of trigger emails offering discounts should be implemented for users whose NPS starts to drop. Most importantly, the development team must address technical debt, as app bugs are currently costing the business too much.
