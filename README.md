# UDCA-PD

README: Analytical Code for "Ursodeoxycholic acid and Parkinson’s disease risk: an emulated target trial in UK electronic health records"

Overview This repository contains SAS code used to conduct the primary, secondary, and sensitivity analyses for the study titled:

"Ursodeoxycholic acid and Parkinson’s disease risk: an emulated target trial in UK electronic health records"

The study emulates a target trial using real-world data to assess the effect of UDCA treatment and subsequent risk of Parkinson’s disease (PD).

Contents The repository includes the following SAS scripts: Analysis_combined.sas and Analysis_boot.sas

Required Data The analyses were conducted using data from CPRD Aurum and GOLD To replicate the results, access to this dataset is required.

Data inputs expected: Patient-level data with demographics, UDCA prescription records, covariates, and outcome events from CPRD Gold and Aurum within each individual emulated trials

Please note: Due to data governance restrictions, the dataset itself is not shared.

Software Requirements SAS version: SAS 9.4 or later

How to Run Update the library name in each script to match your local environment. Ensure all macros in the macros/ folder are compiled before running the analysis scripts. Run the scripts in the order specified above (starting from primary analysis).
