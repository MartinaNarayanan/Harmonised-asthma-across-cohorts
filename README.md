# Harmonised asthma variables across four CLS cohorts

[Centre for Longitudinal Studies](https://cls.ucl.ac.uk/)

---

## Overview
- This repository provides Stata syntax files that harmonise asthma variables in the [**NCDS**]([https://cls.ucl.ac.uk/cls-studies/1958-national-child-development-study/]),  [**BCS**]([https://cls.ucl.ac.uk/cls-studies/1970-british-cohort-study/]),  [**Next Steps**]([https://cls.ucl.ac.uk/cls-studies/1958-national-child-development-study/]) and [**MCS**]([https://cls.ucl.ac.uk/cls-studies/millennium-cohort-study/]) in a consistent way to enable cross-cohort comparison. 
- We also provide an overview of all variables related to asthma in these four cohort studies (note that only a few of them were used in the derivation of the harmonised asthma variables)

---

## Syntax and data availability

- *Source data:* Download raw data files from the **UK Data Service** and place them in `data/raw/`.
- *Syntax:* `01_build_dataset.R` reads those files and produces `data/derived/next_steps.parquet` *(note: keep the code well-commented and use **relative** file paths—e.g., `here::here("data", "raw", ...)` in R, or `$raw` / `$derived` globals in Stata).*
- *Derived dataset:* Available to download from the [**UK Data Service**](https://beta.ukdataservice.ac.uk).

---

## User feedback and future plans

We welcome user feedback. Please open an issue on GitHub or email **clsdata@ucl.ac.uk**.

## Authors
- X author
 
## Contributors [optional e.g., for code checkers]

- X contributor

## Licence  
Code: MIT Licence (see `LICENSE`).

---

© 2025 UCL Centre for Longitudinal Studies
