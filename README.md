# TFM-Rancho-Bernardo-Aging
R code for longitudinal analysis of healthy aging biomarkers - Master's Thesis 2025 Bioinformatics and Biostatistics Master's UOC

# Longitudinal Insights into Healthy Aging

R code for the Master's Thesis: *"Longitudinal insights into healthy aging: 
a multi-disciplinary analysis of the Rancho Bernardo cohort"*

**Author:** Adriana Ibáñez Gómez  
**Program:** Bioinformatics and Biostatistics Master's (UOC/UB)  
**Date:** January 2026

## Description
This repository contains the R scripts used for analyzing longitudinal 
biomarker trajectories in the Rancho Bernardo Study cohort.

## Contents
- `01_Kruskal_Venn.Rmd` - Kruskal-Wallis tests
- `02_Slopes_and_Interactions.Rmd` - Linear regression
- `03_Timeseries.Rmd` - Timeseries graphs and symmetry tests
- `04_Individual_Clustering.Rmd` - Individual Clustering
- `05a_Variable_clusters_female.Rmd`- Variable-level Clustering por women
- `05b_Variable_clusters_male.Rmd`- Variable-level Clustering por men
- `06_PCAs_by_different_vars.Rmd`- Principal Component Analysis

## Data
The original data from the Rancho Bernardo Study is not included due to 
confidentiality. Access can be requested through UC San Diego.

## Requirements
- R >= 4.0
- General packages (specified in each .Rmd): tidyverse, VIM, cluster, FactoMineR, factoextra, ggplot2
