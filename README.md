# 🧪 Pharmacovigilance: Adverse Drug Events Analysis

## Context
Pharmacovigilance focuses on monitoring the safety of medications after they are approved and used in real-world settings.  
Adverse event reporting systems help identify potential safety signals and patterns that may require further investigation.

## Objective
To perform an exploratory analysis of adverse drug event reports in order to describe reporting patterns by drug, patient demographics, and type of adverse event.

This project is descriptive and does not aim to establish causality.

## Data
Public adverse event reports from the FDA Adverse Event Reporting System (FAERS).  
The dataset contains spontaneous reports submitted by healthcare professionals and consumers.

Key variables include:
- Drug name
- Adverse event
- Patient age and sex
- Report year

## Methodology
- Data cleaning and standardization
- Exploratory data analysis (EDA)
- Frequency analysis by drug and adverse event
- Stratification by demographic variables

## Key findings
- Certain adverse events are more frequently reported for specific drugs
- Reporting frequency varies across age groups and sex
- Most reports are concentrated in a small number of event categories

## Limitations
- FAERS data is subject to reporting bias and underreporting
- The presence of a report does not imply causality
- Results should not be interpreted as estimates of risk

## Tools
Python, Pandas, Matplotlib

## Disclaimer
This project uses publicly available data and is intended for educational purposes only.
