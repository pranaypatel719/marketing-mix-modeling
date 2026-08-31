# Marketing Mix Modeling – GlobeStay

Marketing mix modeling project analyzing how different advertising channels influence hotel bookings across the United States, United Kingdom, and Germany.

The goal was to measure channel effectiveness, estimate marketing elasticity, understand the role of performance versus awareness media, and identify opportunities to improve budget allocation.

## Project Objective

This project focused on questions such as:

- Which marketing channels drive bookings most effectively?
- How do performance, awareness, and offline media compare?
- Do marketing responses differ across countries?
- How do seasonality and external factors affect demand?
- How can GlobeStay optimize its marketing mix for ROI and growth?

The analysis used approximately 190 weeks of marketing and booking data across three countries. :contentReference[oaicite:0]{index=0}

## What I Did

- Cleaned and prepared weekly marketing and booking data
- Combined marketing channels into broader performance and awareness groups
- Engineered time and seasonality variables
- Created adstock-transformed marketing features to capture delayed advertising effects
- Built a marketing mix model to estimate the relationship between media spend and bookings
- Estimated channel elasticities to compare marketing effectiveness
- Evaluated performance across the US, UK, and Germany
- Conducted scenario analysis to test alternative budget allocations
- Translated model outputs into practical marketing recommendations

## Key Findings

Performance marketing was the strongest short-term demand driver.

The model estimated a performance-channel elasticity of approximately **0.70**, meaning a 10% increase in performance spend was associated with roughly a 7% increase in bookings. Awareness media had a much smaller short-term elasticity of approximately **0.009**, suggesting its value was primarily longer-term brand building rather than immediate conversion. :contentReference[oaicite:1]{index=1}

Scenario analysis also showed that reallocating marketing spend could improve efficiency without simply increasing the overall budget. :contentReference[oaicite:2]{index=2}

## Recommendations

The analysis supported three main recommendations:

- Increase investment in high-response performance marketing, particularly in the US and Germany
- Maintain a targeted awareness strategy to support long-term brand demand
- Reduce lower-performing offline media and reallocate spend toward higher-response digital channels

A 5% reallocation away from lower-performing offline media was estimated to improve overall marketing efficiency while having minimal negative impact on bookings. :contentReference[oaicite:3]{index=3}

The project estimated that improved budget allocation could generate approximately **€4 million in annual savings**. :contentReference[oaicite:4]{index=4}

## Technologies

Python, Pandas, NumPy, Statsmodels, scikit-learn, Matplotlib, Marketing Mix Modeling, Regression Analysis, Adstock Modeling

## Files

- `globestay_marketing_mix_model.ipynb` – data preparation, feature engineering, modelling, elasticity analysis, and scenario testing
- `data_mmm_2020_post.xlsx` – original weekly marketing and booking dataset
- `processed_marketing_data_withEngineeredFeatures.csv` – cleaned and model-ready dataset containing engineered marketing, seasonality, and adstock features
- `globestay_mmm_presentation.pdf` – project presentation containing methodology, results, business interpretation, and recommendations

## Data Pipeline

The project follows the general workflow:

`Raw marketing data → Data cleaning → Feature engineering → Adstock transformations → Marketing mix model → Elasticity analysis → Scenario testing → Budget recommendations`

## Project Context

This was completed as an academic team project within the Master of Management Analytics program at Smith School of Business, Queen's University.
