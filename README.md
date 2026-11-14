# Longitudinal Cellular-Sheaf Framework for ICU Physiological Data Analysis

## Overview
This repository contains the analysis code for a methodological study applying a cellular-sheaf framework to ICU physiological data. The framework uses a reference-derived transition operator to quantify deviations in physiological dynamics through edge-level residuals and patient-level energy trajectories.

## Data Availability
The study uses the publicly available **PhysioNet 2019 Challenge dataset** (DOI: https://doi.org/10.13026/v64v-d857) under CC BY 4.0.

Processed datasets and preprocessing procedures are available through Zenodo under the **CC BY 4.0 license**:

**Zenodo DOI:** https://doi.org/10.5281/zenodo.24211811

## Cohorts
The processed data comprise three patient cohorts:

- **Reference_Normal:** Non-septic ICU patients used to estimate the reference transition operator.
- **Analysis_Normal:** Independent non-septic ICU patients used for downstream analysis.
- **Septic:** Sepsis-positive ICU patients.

The reference cohort does not represent healthy individuals and may include patients with other acute or chronic illnesses. Also, the three patient cohort partitions, are publicly available through Zenodo under the CC BY 4.0 license [https://doi.org/10.5281/zenodo.24211811].

## Methodology
The pipeline includes data preprocessing, missingness assessment, reference transition estimation using patient-grouped cross-validation, cellular-sheaf residual computation, and patient-level energy aggregation with temporal alignment.

## Reproducibility
The analysis code and implementation are available in this repository. Data preprocessing and analytical procedures are described in the associated manuscript.

## License
- **Code:** MIT License.
- **Processed data:** Creative Commons Attribution 4.0 International (CC BY 4.0).
- **Original data:** Subject to the PhysioNet 2019 Challenge terms of use.
