# PNAD 2015 Data Analysis

This repository contains a descriptive analysis of the 2015 National Household Sample Survey (PNAD) data from the Brazilian Institute of Geography and Statistics (IBGE). The analysis focuses on income, education, age, height, and other demographic variables.

## Project Overview

The goal of this project is to perform a basic descriptive analysis of the PNAD 2015 dataset. The analysis includes:

- **Histograms** for quantitative variables.
- **Measures of central tendency** (mean, median, mode).
- **Measures of dispersion** (variance, standard deviation).
- **Frequency tables** and **cross-tabulations** for categorical variables.
- **Box plots** to visualize income distribution across different demographic groups.

## Dataset

The dataset used in this project is from the 2015 PNAD survey, which includes information on income, age, education, height, and other demographic variables. The dataset has been preprocessed to remove invalid and missing income records and to include only the household reference persons.

### Variables

- **Renda**: Monthly income from the main job for people aged 10 or older.
- **Idade**: Age of the resident in years.
- **Altura**: Height of the resident in meters.
- **UF**: State of residence (coded).
- **Sexo**: Gender (0: Male, 1: Female).
- **Anos de Estudo**: Years of study.
- **Cor**: Race/Color (coded).

## Analysis

The analysis is divided into several steps:

1. **Data Import and Exploration**: The dataset is imported and explored to understand its structure and content.
2. **Frequency Tables**: Frequency tables are constructed for income classes, and histograms are plotted to visualize income distribution.
3. **Measures of Central Tendency and Dispersion**: Mean, median, mode, variance, and standard deviation are calculated for income and other quantitative variables.
4. **Cross-Tabulations**: Cross-tabulations are performed to analyze income distribution by gender and race.
5. **Box Plots**: Box plots are used to visualize income distribution across different demographic groups.

## Key Findings

- **Income Distribution**: The majority of the population earns up to 2 minimum wages (64.75%), while only a small percentage earns above 25 minimum wages (0.55%).
- **Gender and Race**: There are significant differences in income distribution between genders and racial groups. For example, men generally earn more than women, and individuals of Asian descent tend to have higher incomes compared to other racial groups.
- **Education**: Higher levels of education are associated with higher incomes, although the relationship is not linear.

## Repository Structure

- **notebooks/**: Contains Jupyter notebooks with the analysis.
  - `PNAD_2015_Analysis.ipynb`: Main notebook with the descriptive analysis.
- **data/**: Contains the dataset used in the analysis.
  - `dados.csv`: The preprocessed PNAD 2015 dataset.
- **README.md**: This file, providing an overview of the project.

## Requirements

To run the analysis, you need the following Python libraries:

- pandas
- numpy
- seaborn
- matplotlib
- scipy

You can install these libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib scipy
