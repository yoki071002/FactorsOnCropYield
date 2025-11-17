# Factors Influencing Crop Yield: Statistical Study

**Authors:** Chenjie Xu, Simiao Wu, Yutong Qin  
**Date:** 2025-11-09  

## Overview
This repository contains an R-based statistical analysis investigating how crop type, year-to-year variation, and adaptation strategies influence crop yield. The analysis uses the [Climate Change Impact on Agriculture 2024 dataset](https://www.kaggle.com/datasets/waqi786/climate-change-impact-on-agriculture).

## Methods
Three main statistical approaches were applied:  
1. One-Way ANOVA – to test yield differences across crop types.  
2. Repeated-Measures ANOVA – to examine yield changes across years within countries.  
3. Kruskal–Wallis Test – a non-parametric method to compare yields across adaptation strategies.  

Preliminary checks included:  
- Normality test (Lilliefors KS test)  
- Outlier detection (Tietjen-Moore test)  
- Variance homogeneity (Bartlett’s test)  

## Key Findings
- No significant effect of crop type on yield (ANOVA p = 0.150).  
- No significant year-to-year changes in yield (RM-ANOVA p = 0.140 after correction).  
- No significant differences among adaptation strategies (Kruskal–Wallis p = 0.146).  

**Conclusion:** Crop yield remained relatively stable across biological, temporal, and management factors in this dataset.

## Files
- `MA416_GroupProjFinal.Rmd` – R Markdown script for data cleaning, analysis, and visualization.  
- `climate_change_impact_on_agriculture_2024.csv` – dataset used for analysis.  

