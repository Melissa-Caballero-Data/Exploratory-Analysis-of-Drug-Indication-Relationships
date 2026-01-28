# 🧪 Drug–Indication Relationship Analysis

## Context
Understanding the relationship between drugs and their approved or reported clinical indications is essential in healthcare and pharmaceutical analytics.  
Standardized vocabularies such as RxNorm, MONDO, and UMLS enable consistent integration and analysis of medical data across systems.

## Objective
To perform an exploratory analysis of drug–indication relationships using standardized clinical vocabularies, focusing on the structure, frequency, and diversity of indications associated with different drugs.

This project is descriptive and does not aim to assess efficacy or safety.

## Data
Publicly available drug–indication data including:
- Drug names and synonyms
- RxNorm identifiers (RxCUI)
- Clinical indications mapped to MONDO and UMLS ontologies

Key variables include:
- Drug labels
- Indication labels
- Ontology identifiers

## Methodology
- Data cleaning and normalization of drug and indication labels
- Exploratory data analysis (EDA)
- Frequency analysis of indications per drug
- Identification of drugs with broad vs. narrow indication profiles

## Key findings
- Some drugs are associated with a wide range of clinical indications
- Indications are unevenly distributed across drugs
- Ontology-based identifiers enable structured analysis of medical concepts

## Limitations
- The dataset does not include treatment outcomes or adverse events
- Relationships are descriptive and may not reflect clinical practice or approval status
- No causal or effectiveness conclusions can be drawn

## Tools
Python, Pandas, Matplotlib

## Disclaimer
This project uses publicly available data and is intended for educational purposes only.
