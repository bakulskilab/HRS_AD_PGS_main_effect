# Cumulative genetic risk and APOE-ε4 are independently associated with dementia status in a multi-ethnic, population-based cohort.

## Citation Information
Bakulski KM, Vadari HS, Faul JD, Heeringa SG, Kardia SLR, Langa KM, Smith JA, Manly JJ, Mitchell CM, Benke KS, Ware EB. 2021. Cumulative genetic risk and APOE-ε4 are independently associated with dementia status in a multi-ethnic, population-based cohort. Neurology Genetics. PMID: 33688582, PMCID: PMC7938646
DOI: 10.1212/NXG.0000000000000576

This Github repository contains the data management and analytic scripts to produce the following manuscript:[Cumulative genetic risk and APOE-ε4 are independently associated with dementia status in a multi-ethnic, population-based cohort](https://pubmed.ncbi.nlm.nih.gov/33688582/)

## Abstract
**Objective**: Alzheimer disease (AD) is a common and costly neurodegenerative disorder. A large proportion of AD risk is heritable, and many genetic risk factors have been identified. The objective of this study was to test the hypothesis that cumulative genetic risk of known AD markers contributed to odds of dementia in a population-based sample.
**Methods**: In the US population-based Health and Retirement Study (waves 1995-2014), we evaluated the role of cumulative genetic risk of AD, with and without the APOE ε4 alleles, on dementia status (dementia, cognitive impairment without dementia, borderline cognitive impairment without dementia, and cognitively normal). We used logistic regression, accounting for demographic covariates and genetic principal components, and analyses were stratified by European and African genetic ancestry.
**Results**: In the European ancestry sample (n = 8,399), both AD polygenic score excluding the APOE genetic region (odds ratio [OR] = 1.10; 95% confidence interval [CI]: 1.00-1.20) and the presence of any APOE ε4 alleles (OR = 2.42; 95% CI: 1.99-2.95) were associated with the odds of dementia relative to normal cognition in a mutually adjusted model. In the African ancestry sample (n = 1,605), the presence of any APOE ε4 alleles was associated with 1.77 (95% CI: 1.20-2.61) times higher odds of dementia, whereas the AD polygenic score excluding the APOE genetic region was not significantly associated with the odds of dementia relative to normal cognition 1.06 (95% CI: 0.97-1.30).
**Conclusions**: Cumulative genetic risk of AD and APOE ε4 are both independent predictors of dementia in European ancestry. This study provides important insight into the polygenic nature of dementia and demonstrates the utility of polygenic scores in dementia research.

## Funding
This study was funded by the NIH (grant numbers R01 AG055406, R01 AG055654, R25 AG053227, R01 AG053972, R03 AG048806, and P30 AG053760). The Health and Retirement Study is sponsored by the National Institute on Aging (U01AG009740) and is conducted at the Institute for Social Research, University of Michigan.

## Script Files
This is a [workflowr](https://github.com/jdblischak/workflowr) project

*analysis* folder contains code files to produce this project

HRS_PGS_AD_Cog_01_DataQC_kmb_20191029.Rmd: Data QC and Variable Development

HRS_PGS_AD_Cog_02_Inclusion_Flow_Table_kmb_20191029.Rmd: Producing reproducible inclusion/exclusion descriptive statistics tables, flowcharts

HRS_PGS_AD_Cog_03_Bivariate_Tables_kmb_20191029.Rmd: Producing reproducible bivariate descriptive statistics tables

HRS_PGS_AD_Cog_04_Logistic_Regression_Primary_kmb_20191029.Rmd: Primary logistic regression models in primary analysis

HRS_PGS_AD_Cog_05_Logistic_Regression_Sensitivity_kmb_20191029.Rmd: Sensitivity regression models

HRS_PGS_AD_Cog_06_ROC_PAF_kmb_20191029.Rmd: Complete PAF and ROC curve analysis for primary analysis

*docs* folder contains the html file of the code producing this project
