# FIN_NL_cohort_collaboration
Comparison of iron status in Finnish and Dutch blood donor and general populations

This repository contains R code to reproduce the analyses for the manuscript "IRON STATUS IN DUTCH AND FINNISH BLOOD DONOR AND GENERAL POPULATIONS: A CROSS-COHORT COMPARISON STUDY" 

The code is included in three separate .Rmd files. The first part (Cohort Comparison - Cohort Preparation) allows the user to describe the cohorts, filter participants based on eligibility, preprocess data, produce tables for the manuscript and build a summary table to be used in further regression analysis. The second part (Prevalence of iron deficiency) contains code to produce the prevalence plots and ferritin histograms. The third (Low ferritin logistic model) part allows the user to run Bayesian logistic regression analyses on iron deficiency to produce the forest plots. There are two versions of code used, one for the Finnish cohorts and one for the Dutch cohorts. A fourth code (Cohort Comparison - Tables & Plots) can be used to combine the figures produced for both countries. 

Information on packages needed to run the code is included in the .Rmd:s.

For questions regarding the code or manuscript, please contact S Ekroos (sofie (dot) ekroos (at) helsinki (dot) fi) or J Karregat (j (dot) karregat (at) sanquin (dot) nl).

Old version control available in https://github.com/FRCBS/iron_measurement_comparisons
