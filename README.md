# covid-vaccination-us-efficacy

COVID-19 Vaccination and Infection Rate Analysis
Overview
This project explores the relationship between COVID-19 vaccination rates and infection rates across different periods of the pandemic, focusing on the impact of variants such as Delta and Omicron. The analysis examines whether higher vaccination rates correlate with lower infection rates, and provides insights into the observed trends through statistical and contextual evaluation.

Key Objectives
Test the hypothesis:

Null Hypothesis (H₀): Vaccination rates (first dose and fully vaccinated) do not correlate with lower infection rates.
Alternative Hypothesis (H₁): Higher vaccination rates correlate with lower infection rates.
Investigate infection trends during key pandemic periods:

Pre-Omicron Period (early 2021 to November 2021).
Omicron Wave (December 2021 to February 2022).
Provide a contextual interpretation of the findings to understand the broader dynamics influencing infection rates.

Dataset
Source: Publicly available COVID-19 vaccination and infection data.
Columns:
Date Administered: Date of vaccination data collection.
AgeGroupVacc: Age groups analyzed for vaccination and infection rates.
7-day_avg_group_cases_per_100k: Average infection rate (per 100k population) over a 7-day period.
Administered_Dose1_pct_agegroup: Percentage of the age group receiving at least one vaccine dose.
Series_Complete_Pop_pct_agegroup: Percentage of the age group fully vaccinated.
Findings
Statistical Results:

Correlation between vaccination rates (first dose or full dose) and infection rates was very low (~0.06).
Regression analysis showed minimal explanatory power for vaccination rates predicting infection rates.
Trends During Key Periods:

Pre-Omicron: Infection rates were relatively low and stable.
Omicron Wave: Infection rates spiked significantly, despite high vaccination rates, driven by Omicron's high transmissibility and immune escape.
Contextual Insights:

Vaccines remained effective in reducing severe illness, but their efficacy in preventing infection declined with variants like Delta and Omicron.
Behavioral changes (e.g., resumption of normal activities by vaccinated populations) and timing of data likely contributed to the observed lack of correlation.
Visualizations
Time Trends:
Infection rates over time during pre-Omicron and Omicron periods.
Scatterplots:
Infection rates vs. vaccination rates across age groups.
Box Plots:
Infection rates by age group to highlight variability.
Conclusion
The analysis confirmed the null hypothesis: Vaccination rates do not strongly correlate with lower infection rates. However, the findings must be interpreted in the context of:

Variants with immune escape properties (e.g., Omicron).
Changes in public behavior during vaccination campaigns.
Evolving public health messaging around vaccine efficacy.
Vaccines remain critical in reducing severe outcomes, but their role in preventing infection is limited under certain pandemic conditions.

Files
Notebook: Contains the complete analysis, code, and visualizations.
Dataset: The cleaned dataset used for the analysis.
Visuals: Plots and charts summarizing key findings.
Next Steps
Explore regional or policy-based differences in vaccination and infection trends.
Analyze booster dose efficacy during Omicron.
Study additional variables like mask mandates, population density, or testing rates.
Feel free to suggest edits or let me know if you'd like a different focus for the README!
