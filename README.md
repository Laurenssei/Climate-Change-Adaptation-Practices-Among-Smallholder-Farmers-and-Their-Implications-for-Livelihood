# Climate-Change-Adaptation-Practices-Among-Smallholder-Farmers-and-Their-Implications-for-Livelihood

# Climate Change Adaptation Practices Among Smallholder Farmers and Their Implications for Livelihood Sustainability: Evidence from the Bono East Region

📄 Full Report: [View Analysis](Climate Change Adaptation Practices Among Smallholder Farmers and Their Implications for Livelihood.pdf) and (Additional analysis  - Climate Change Adaptation Practices Among Smallholder Farmers and Their Implications for Livelihood.pdf)

## Overview
This project examines climate change adaptation among 368 smallholder crop farmers in Ghana's Bono East Region, assessing awareness, strategies, adoption factors, livelihood impacts, and barriers to effective implementation. Findings reveal high awareness (94%) of effects like rising temperatures (72%) and irregular rainfall (71.1%), driving 79.9% adoption of indigenous strategies such as organic manure (77.6%) and changing planting dates (74.1%). Adaptation boosts yields (61.6% increase, p<0.0001) and mitigates income declines (-58% vs. -73.2%), but increases food insecurity (72.1%, p<0.0001) due to costs. Barriers include environmental (plant diversity loss, mean=3.76) and technological (training lack, mean=3.68) factors, with gender (males OR=2.81, p=0.002) and cultural beliefs (OR=2.82, p=0.023) influencing adoption. Insights advocate for cost-effective, education-enhanced interventions to bolster resilience and sustainable livelihoods.

## Objectives
- Assess the awareness and effects of climate change on smallholder crop farmers.
- Examine the climate change adaptation strategies among crop farmers.
- Determine the factors that affect the adoption of climate change adaptation strategies.
- Assess the effects of climate change adaptation strategies on livelihoods.
- Explore barriers to implementing effective climate change adaptation measures.

## Dataset Summary
- **Source**: Primary survey data from smallholder crop farmers in Bono East Region, Ghana (2025).
- **Sample Size**: 368 respondents.
- **Key Variables**: Demographics (age, gender, education, household size, farming experience); awareness/effects (noticed climate change, temperature/rainfall changes, impacts like crop destruction); adaptation (adopted strategies, effectiveness, factors like loss experience); livelihoods (income/yield changes, food security indicators); barriers (cultural, environmental, technological, market, supply chain).

## Methods
- Descriptive statistics (means, frequencies, percentages) and visualizations (bar plots, violin plots, scatterplots) for profiling demographics, adoption, and outcomes.
- Inferential tests including chi-square/Fisher's exact for associations (e.g., gender vs. adoption), t-tests/Wilcoxon for differences (e.g., income by adoption), logistic/ordinal/linear regression for predictors (e.g., factors on adoption, strategies on income/yield).
- Correlations (tetrachoric/Spearman) and MANCOVA for multivariate relationships; factor analysis for barrier clustering.

## Key Findings
- High climate awareness (94%), with rising temperatures (72%) and irregular rainfall (71.1%) as top effects; education (p=0.018) and land size (OR=1.15, p=0.017) drive awareness.
- 79.9% adopt strategies, favoring indigenous methods like organic manure (77.6%) and changing planting dates (74.1%); intercropping (mean=3.77) rated most effective; gender (males OR=2.81, p=0.002) and cultural beliefs (OR=2.82, p=0.023) key adoption factors.
- Adaptation improves yields (61.6% increase, p<0.0001) and reduces income declines (-58% vs. -73.2%), but raises food insecurity (72.1%, p<0.0001); changing planting dates boosts income (OR=2.97, p=0.0005), while organic manure/intercropping hinder it.
- Barriers dominated by environmental (plant diversity loss, mean=3.76) and technological (training/tools, mean=3.66–3.68); uneducated farmers face highest barriers (p<0.001); market/supply chain issues (mean=3.61–3.63) significant.
- Flooding analysis: 35.7% experience it (never 64.3%), linked to lower yields/income; adopters in high-frequency areas use diversification (31.1%); correlates with soil degradation (25.9% cause) and food insecurity.



## How to Reproduce the Analysis
### Requirements
- R (version 4.0 or higher)
- RStudio
- R packages: tidyverse, ggplot2, dplyr, psych (for correlations/factor analysis), MASS (for regression), car (for MANCOVA)

### Steps
1. Clone this repository.
2. Open `analysis.Rmd` in RStudio.
3. Install required packages if not already installed (e.g., `install.packages(c("tidyverse", "psych", "MASS"))`).
4. Knit the R Markdown file to generate the HTML report.
Data not included due to confidentiality. Please contact me for collaboration requests.

## Repository Structure
├── analysis.Rmd         # R Markdown source file  
├── analysis.html        # Knitted HTML report  
├── figures/             # Plots and visualizations  
├── README.md            # Project description  

## License / Citation
This project is for academic and research purposes. Please cite appropriately if referenced, e.g., Sei, Lawrence. (2025). Climate Change Adaptation Practices Among Smallholder Farmers and Their Implications for Livelihood Sustainability: Evidence from the Bono East Region.
