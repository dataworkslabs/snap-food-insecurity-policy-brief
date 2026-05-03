# Hunger in America: A Policy Design Problem

An R Markdown data visualization project analyzing food insecurity 
across the United States and the structural failures of the SNAP 
nutrition assistance program.

## Overview

This project was built as a policy brief for a political audience. 
The goal is to demonstrate that food insecurity in America is not a 
scarcity problem. It is a policy design problem. Working families are 
falling through a gap that the current system created.

## Story Arc

The visualizations follow a deliberate narrative sequence:

1. Geographic scale — food insecurity by state
2. Who it affects — breakdown by age, sex, and household type
3. The child to adult pipeline — long term consequences of childhood hunger
4. Structural cause — poverty drives food insecurity
5. SNAP inadequacy — benefits do not cover minimum nutrition costs
6. The cliff effect — earning more can leave families with less
7. A policy fix — what a gradual phase-out would look like
8. The closing case — what reform would mean at the national level

## Data Sources

- Feeding America, Map the Meal Gap 2025 (2019-2023 data)
- USDA Food and Nutrition Service, SNAP Participation and Spending
- USDA Center for Nutrition Policy and Promotion, Thrifty Food Plan November 2024
- USDA Economic Research Service, Household Food Security Report 2023
- U.S. Department of Health and Human Services, 2025 Federal Poverty Guidelines
- U.S. Census Bureau, American Community Survey 2023

## Requirements

R version 4.0 or higher. The following packages are required:

- ggplot2
- usmap
- dplyr
- scales
- patchwork
- ggrepel

Install all packages by running:

install.packages(c("ggplot2", "usmap", "dplyr", "scales", "patchwork", "ggrepel"))

## Usage

Open food_insecurity_brief.Rmd in RStudio and knit to PDF. All data 
is embedded directly in the code. No external file loading is required 
except for the raw data files listed in the data sources section above.

## Key Findings

- 47 million Americans faced food insecurity in 2023
- No state falls below 9% food insecurity
- The South has the highest concentration of food insecure households
- Poverty rate and food insecurity rate are strongly correlated across states
- Average SNAP benefits fall short of minimum nutrition costs by 124 to 252 dollars per month depending on household size
- A 1,000 dollar annual raise can reduce a household's total monthly resources when it crosses the SNAP eligibility threshold
- Children facing food insecurity are more likely to fall behind academically, earn less, and face food insecurity as adults
