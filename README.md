# 🧪 Drug–Indication Association Analysis (FAERS-derived data)

## Context
Understanding drug–indication associations is an important component of healthcare and pharmaceutical data analysis.  
This project explores drug–indication data extracted from the FDA Adverse Event Reporting System (FAERS) and standardized using clinical ontologies such as RxNorm, UMLS, and MONDO.

## Objective
To perform a descriptive and exploratory analysis of drug–indication associations, focusing on data structure, coverage, and indication diversity across drugs.

This analysis does not aim to assess clinical effectiveness, safety, or causality.

## Data
The dataset contains drug–indication associations derived from FAERS reports, including:
- Drug labels and synonyms
- RxNorm Clinical Unique Identifiers (RxCUI)
- Clinical indications mapped to UMLS and MONDO ontologies

## Methodology
- Data cleaning and parsing of multi-label drug and indication fields
- Explicit handling of missing indication data
- Exploratory data analysis (EDA)
- Analysis of indication distribution and drug indication profiles
- Visualization of key patterns

## Key findings
- A substantial proportion of drugs lack recorded indication information, reflecting dataset coverage limitations
- Most drugs with available data are associated with a small number of indications
- A limited subset of drugs shows broader indication profiles
- Drug labels required standardization to improve interpretability and visualization clarity

## Limitations
- Indications are derived from FAERS reports and do not represent treatment effectiveness or clinical outcomes
- Missing indication values reflect incomplete coverage rather than absence of clinical use
- Results are descriptive and should not be used for clinical or regulatory decision-making

## Tools
Python, Pandas, Matplotlib

## Disclaimer
This project uses publicly available data and is intended for educational and portfolio purposes only.
