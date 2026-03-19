# Publication Checklist

**Machine Learning vs. Statistical Models for Dengue Forecasting in Brazil**
*A Benchmarking Study Across Eight State Capitals (2010–2024)*

---

## Title Page

- [ ] Fill in author names, affiliations, and ORCID IDs
- [ ] Fill in corresponding author email
- [ ] Fill in abstract word count
- [ ] Fill in main text word count

---

## Abstract

- [ ] Fill in final word count (target ≤ 300 words)
- [ ] Update Results paragraph with final values for all 8 cities (currently placeholder)
- [ ] Write abstract topics (Introduction, Methods, Results, Conclusion)

---

## Introduction

- [ ] Write Introduction (3 paragraphs)

### 1. Global and Latin American burden of dengue

### 2. Importance of prediction models: gap and rationale

### 3. Objective

---

## Methods

- [ ] Write Methods section

### 1. Adherence to reporting guidelines, ethics, and registration

- [ ] Add citation: STROBE guidelines
- [ ] Add citation: Brazilian Resolution CNS 510/2016
- [ ] Confirm GitHub repository URL is publicly accessible
- [ ] Add conflict of interest statement (currently: none declared)
- [ ] Add funding statement (currently: no external funding)

### 2. Study setting

### 3. Data source

- [ ] Add citation: 2018 — InfoDengue system description
- [ ] Add citation: IBGE intercensal population estimates (2010–2022) and projections (2023–2024)
- [ ] Confirm fetch_infodengue.py is in the public repository and functional
- [ ] Confirm 780 weekly observations per city (Week 1/2010 – Week 52/2024)

### 4. Variables

### 5. Statistical methods

#### 5.1 Forecasting models

#### 5.2 Evaluation framework

#### 5.3 Spatiotemporal cluster analysis

---

## Results

### Descriptive summary and crude time series

- [ ] Descriptive statistics
- [ ] Insert **Figure 1** — crude monthly time series for all 8 capitals with SaTScan cluster windows

### SaTScan spatiotemporal cluster analysis

- [ ] Run SaTScan and fill in all [XX,XXX] values in **Table 1** (observed cases, expected cases, RR, LLR)
- [ ] Confirm p-values for all 16 cluster rows in Table 1
- [ ] Fill in number of significant space-time clusters [X]
- [ ] Fill in number of cities encompassed by largest space-time cluster [X]
- [ ] Fill in date span of largest space-time cluster [period]
- [ ] Insert **Figure 1** — SaTScan high/low cluster, time series

### Forecasting model performance

- [ ] Run benchmark for all 7 remaining capitals and fill in all [to be filled] cells in **Table 2** (6 models × 8 cities × MAE, RMSE, sMAPE)
- [ ] Fill in [X] of 8 cities where CatBoost had lowest/second-lowest MAE
- [ ] Fill in [X] of 8 cities where CatBoost had lowest sMAPE
- [ ] Fill in [X]–[X]% MAE advantage of CatBoost over SARIMAX
- [ ] Insert **Figure 2** — CatBoost forecast vs. observed per capital, 2×4 panel, SaTScan high-cluster periods shaded

---

## Discussion

- [ ] Add citation: ML vs. linear models for epidemic time series (non-linear dynamics)
- [ ] Add citation: benchmarking studies from Southeast Asia
- [ ] Add citation: ML methods for other arboviruses in Brazil
- [ ] Add citation: COVID-19 pandemic effect on dengue surveillance
- [ ] Add citation: climate covariates for future work

---

## References

- [ ] Write References

---

## Supplementary Material

- [ ] **Table S1** — full SaTScan output for all cities (all significant clusters, high and low)
- [ ] **Table S2** — IBGE population denominators and city geocoordinates used in SaTScan
- [ ] **Table S3** — full model hyperparameter configurations (including post-tuning parameters)
- [ ] **Figure S1** — STL seasonal decomposition plots for all 8 cities
- [ ] **Figure S2** — forecast vs. observed plots for all 6 models in São Paulo

---

## Submission

- [ ] Define target journal and confirm scope fit
- [ ] Apply journal author guidelines (word limit, reference style, figure format, file types)
- [ ] Prepare title page per journal requirements
- [ ] Write cover letter
- [ ] Run plagiarism check
- [ ] Final proofread
- [ ] Confirm all figures are 300 dpi, ≥ 85 mm wide, in required format (TIFF or EPS)
- [ ] Upload all files to submission system

---

*Repository: https://github.com/fabianofilho/dengue-timeseries-skforecast*
*Data: InfoDengue (https://info.dengue.mat.br/) · Population: IBGE (https://www.ibge.gov.br/)*
