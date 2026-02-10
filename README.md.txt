# Product Funnel & Conversion Analytics

## Overview
This project demonstrates an end-to-end product analytics workflow to analyze
user behavior from signup to conversion. The goal is to identify drop-off points
and understand how feature usage impacts conversion rates.

## Funnel Definition
- **Signup**: User creates an account
- **Activation**: User performs a core action (e.g., first feature use)
- **Conversion**: User completes a successful payment

## Tech Stack
- MySQL
- Python (Pandas, Matplotlib)
- Jupyter Notebook
- Power BI

## Key Analyses Performed
- Signup → Activation → Conversion funnel analysis
- Drop-off analysis at each funnel stage
- Feature-wise usage and conversion impact analysis
- Visualization of conversion rates

## Key Insights
- Overall conversion rate from signup to conversion is **40%**
- Major drop-off occurs between signup and activation
- Users engaging with **search** and **wishlist** features show significantly
  higher conversion rates compared to basic activation

## Business Recommendations
- Improve onboarding experience to reduce early drop-offs
- Encourage early usage of high-intent features such as search and wishlist
- Use feature-based nudges to improve activation and conversion rates

## Project Structure
product-funnel-conversion-analytics/
├── data/
│ ├── raw/
│ └── processed/
├── sql/
├── notebooks/
├── visuals/
└── README.md