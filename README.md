# Heart Disease Risk Factors: Statistical Analysis in Python

## Objective
Explore whether various patient variables are associated with heart disease diagnosis.

## Tools
Python, Pandas, NumPy, Matplotlib/Seaborn, SciPy, statsmodels

## Methods
* Data visualisation
    * Box plots
* Hypothesis testing
    * Two-sample t-tests
    * One-way ANOVA and Tukey tests
    * Chi-square test

## Key Findings
* Maximum heart rate differed significantly between patients with and without heart disease, the two diagnosis groups in this dataset.
* Cholesterol levels, however, were not statistically significant between these two groups.
* Maximum heart rate varied significantly between patients with asymptomatic chest pains and patients with other chest-pain types.
* Chest-pain type was significantly associated with heart disease diagnosis.

## Limitations
Statistical associations do not guarantee causal relationships -- this means, for example, that despite the lack of statistical significance between cholesterol and heart disease diagnoses, medical studies have confirmed that high cholesterol causes heart disease. This can be explained by the fact that the provided dataset was limited to a specific patient sample; as such, these results may not generalise to all populations.
