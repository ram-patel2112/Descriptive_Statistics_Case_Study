# Descriptive Statistics Case Study: Employee Dataset Analysis

## Overview
Jupyter notebook performing exploratory data analysis on employee data to uncover patterns in age, lifestyle habits, and salary across groups (A, O, AB, B).

## Dataset
- **Source**: Employee-Dataset-2.csv (50 records)
- **Columns**:
  - id: Unique identifier
  - groups: Categorical (A, O, AB, B)
  - age: Employee age
  - healthy_eating: Score (1-10)
  - active_lifestyle: Score (1-10)
  - salary: Annual salary

## Key Analysis
- Data overview: shape, info, head
- Visualizations: scatterplots (age-salary, healthy_eating-active_lifestyle), salary histogram, group counts
- Subsets: High healthy_eating (≥8), high salary (≥1000)

## Requirements
- Python 3
- pandas, numpy, matplotlib, seaborn

## Usage
1. Clone repo
2. Open `Descriptive_Statistics_Case_Study.ipynb`
3. Run all cells

## Files
- `Descriptive_Statistics_Case_Study.ipynb`: Main analysis
- `Employee-Dataset-2.csv`: Dataset
