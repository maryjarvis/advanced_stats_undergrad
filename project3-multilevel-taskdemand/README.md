# Multilevel Regression – Task Demand and Job Categories

## 📘 Overview
This project uses linear mixed-effects modelling to examine how perceived task demand varies across job categories, incorporating random effects and interaction terms.

## 🎯 Objectives
- Assess how job roles influence perceived task load
- Account for within-group variability with random intercepts
- Explore whether age effects vary across job types

## 🛠 Tools & Techniques
- R (lme4, tidyverse)
- Mixed models with random intercepts and slopes
- ICC (Intra-class correlation) to estimate group effects

## 📁 Files
- `multilevel_model.Rmd` - full model code
- `workplace_stress.csv` - data 
- `multilevel_model.pdf`

## 📊 Data Source
This dataset is based on anonymised survey data from published studies.

Menghini, L., Pastore, M., and Balducci, C. (2022). Workplace stress in real time: Three parsimonious
scales for the experience sampling measurement of stressors and strain at work. European Journal of
Psychological Assessment. https://doi.org/10.1027/1015-5759/a000725

The data is used here for educational and non-commercial purposes only.

## 📌 Outcome
The multilevel model showed that job category explained 66% of the variance in task demand. Age interacted with job category, suggesting different perceptions of workload across roles.

