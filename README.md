# ARSA
In this project we studied role of rare ARSA variants in Parkinson's disease

##Role of rare ARSA variants##
#Cohorts sequenced at McGill#
For cohorts sequenced at McGill ARSA gene was captured using molecular inversion probs. All MIPs that were used to sequence ARSA are provided (Supplementary Table 2) and the full protocol is available at https://github.com/gan-orlab/MIP_protocol.
We performed standart filtering procedures using MIPVar pipeline (https://github.com/gan-orlab/MIPVar).

#We also used AMP-PD and UKBB data#
Alignment for these data was performed using the human reference genome (hg38) and coordinates for the ARSA gene extraction were chr22:50,622,754-50,628,152
For AMP-PD we utilized Terra platform

#Analysis of UKBB cohort was performed localy using Neurohub#
Filtration detailed in the UKBB script

#Analysis of AMP-PD data was performed using Terra platform#
Filtration detailed in the AMP-PD script

#burden analysis and meta-analysis between cohort was performed using SKAT-0 and meta-SKAT packages#
detailed in the meta-analysis script
