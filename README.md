# WOF_transitions_cps
Code to create job-to-job transitions using IPUMS CPS, either at the occupation or industry level. It could be expanded to different definitions of transitions.    
Specifically, the repository contains code to replicate the transition matrix at the SOCXX-SOCXX and NAICSXX-NAICSXX level used in Moving up: Promoting workers’ upward mobility using network analysis (Escobari, Seyal and Daboin, 2021). 
It includes:
- Script to clean CPS_IPUMS data and create the month-to-month dataset.
- Script to clean month-to-month into a transition’s dataset at the SOCXX and NAICSXX level.
- Scripts to develop and test functions to crunch the transition datasets (work in progresss).
