# nsclc-rwe-seer
## Real-World Treatment Patterns & Overall Survival in Early-Stage NSCLC
#### A SEER-Based Observational Study:

An end-to-end real-world evidence (RWE) study evaluating the association between adjuvant radiation and overall survival in Stage I–II non-small cell lung cancer, using SEER registry data. Designed to reflect methods used in pharma R&D and regulatory-grade observational research.

## Background
For Stage I–II non-small cell lung cancer (NSCLC), the role of adjuvant radiation therapy following surgery remains contested outside specific clinical scenarios. While randomized trials offer limited guidance in this space, real-world data can characterize treatment patterns and survival outcomes across the broader population of patients treated in routine clinical practice.
This study applies an epidemiologically rigorous RWE framework including a pre-specified study protocol, survival analysis, and inverse probability of treatment weighting (IPTW) to evaluate whether adjuvant radiation following surgical resection is associated with differential overall survival in early-stage NSCLC patients.

## Study Design
| Parameter          | Specification                                      |
|--------------------|---------------------------------------------------|
| Data source        | SEER 17 registry (seer.cancer.gov)                |
| Study population   | Stage I–II NSCLC, diagnosed 2010–2018             |
| Exposure           | Surgery alone vs. surgery + adjuvant radiation    |
| Primary outcome    | Overall survival (OS); time zero = diagnosis date |
| Minimum follow-up  | 5 years (index through 2023)                      |
| Analytic cohort    | ~45,000 patients (post-exclusion estimate)        |

**Inclusion criteria**

- Primary NSCLC diagnosis (ICD-O-3 histology codes)
- Stage I or II (AJCC 7th/8th edition)
- Received surgical resection as first-line treatment
- Diagnosed 2010–2018

**Exclusion criteria**

- Second or subsequent primary cancer
- Unknown or missing stage
- Follow-up < 1 month from diagnosis
- Unknown vital status


#### Author:
Jisoo Han
MS Applied Data Science, University of Chicago | Senior Scientist II, Novartis Biomedical Research
Transitioning into RWE / advanced analytics at the intersection of pharma R&D and immuno-oncology.
[LinkedIn:](https://www.linkedin.com/in/jisoo-han/) 
