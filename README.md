# WOF_transitions_cps
Code to create job-to-job transitions using IPUMS CPS, either at the occupation or industry level. Could be expanded to different definitions of transitions
Repository contains code to replicate the transition matrix at the SOCXX-SOCXX and NAICSXX-NAICSXX level used in Moving up: Promoting workers’ upward mobility using network analysis (Escobari, Seyal and Daboin, 2021). 
Includes:
- Script to clean CPS_IPUMS data and create the month-to-month dataset (202104_build_transitions_cps_demo.R).
- Script to clean month-to-month into a transition’s dataset at the SOCXX and NAICSXX level (clean_transitions_cps.R).
- Scripts to develop and test functions to crunch the transition datasets (work in progresss).

Important: Raw data must be downloaded from [IPUMS CPS website](https://cps.ipums.org/cps-action/data_requests/download), we only provide the code we used to clean it. 