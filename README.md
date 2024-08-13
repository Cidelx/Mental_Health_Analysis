# Analysis of Factors Influencing Mental Health

**Author**: Cidel Tetteh  
**Date**: 08/09/2024

---

## Executive Summary

This report presents a comprehensive analysis of factors influencing mental health, using a dataset that includes variables such as age, marital status, education level, smoking status, physical activity, employment status, alcohol consumption, dietary habits, sleep patterns, history of mental illness, and family history of mental illness. The analysis aims to identify key correlations and trends that may provide insights into how these factors relate to mental health.

## Introduction

### Background
Mental health is a complex and multifaceted issue influenced by various personal, social, and environmental factors. Understanding the relationship between these factors can help in identifying at-risk populations and developing targeted interventions. This study analyzes a dataset with multiple variables to explore their impact on mental health.

### Objective
The objective of this analysis is to investigate the relationships between different lifestyle and demographic factors and the prevalence of mental illness. By analyzing these variables, the report aims to provide actionable insights into how these factors contribute to mental health outcomes.

### Scope
This report focuses on ten key variables: age, marital status, education level, smoking status, physical activity, employment status, alcohol consumption, dietary habits, sleep patterns, history of mental illness, and family history of mental illness. The analysis includes a comparison of these factors and their potential correlation with mental health.

## Data Description

The dataset used in this analysis contains the following columns:
- **Age**: The age of the individual.
- **Marital Status**: The individual's marital status.
- **Education Level**: The highest level of education attained by the individual.
- **Smoking Status**: Whether the individual is a current smoker, former smoker, or non-smoker.
- **Physical Activity**: The individual's level of physical activity (e.g., active, moderate, sedentary).
- **Employment Status**: Whether the individual is employed or unemployed.
- **Alcohol Consumption**: The individual's level of alcohol consumption.
- **Dietary Habits**: The individual's dietary habits (e.g., healthy, moderate, unhealthy).
- **Sleep Patterns**: The quality of sleep (e.g., good, fair, poor).
- **History of Mental Illness**: Whether the individual has a history of mental illness.
- **Family History of Mental Illness**: Whether there is a family history of mental illness.

## Methodology

The analysis involved cleaning and preprocessing the data to ensure accuracy. Various analytical techniques, including correlation analysis and visual comparisons, were used to examine the relationships between the variables. The analysis was supported by visual representations such as bar charts to illustrate key findings.

## Analysis and Findings

### 1. Marital Status
- Married individuals show the highest incidence of mental illness history, possibly due to the larger sample size or stressors associated with marriage. Single and widowed individuals also display significant counts, highlighting the potential impact of loneliness or loss on mental health.

![Marital Status Analysis](https://github.com/Cidelx/Mental_Health_Analysis/blob/main/Images/Marital%20Status%20Analysis.png?raw=true)

### 2. Employment Status and Physical Activity
- Sedentary lifestyles are strongly associated with a higher incidence of mental illness, regardless of employment status. This underscores the importance of physical activity in maintaining mental health.

![Employment and Physical Activity Analysis](https://github.com/Cidelx/Mental_Health_Analysis/blob/main/Images/Employment%20Status%20and%20Physical%20Activity.png?raw=true)

### 3. Sleep Patterns and Dietary Habits
- Poor sleep quality correlates with unhealthy dietary habits and a higher prevalence of mental illness. Even those with fair or good sleep patterns are more likely to have moderate or unhealthy diets, indicating a broader issue with sleep affecting overall health.

![Sleep Patterns and Dietary Habits Analysis](https://github.com/Cidelx/Mental_Health_Analysis/blob/main/Images/Sleep%20Patterns%20and%20Dietary%20Habits.png?raw=true)

### 4. Smoking Status
- Non-smokers have the highest incidence of mental illness, followed by former smokers. This may suggest that quitting smoking is associated with increased awareness of mental health issues, or that former smokers seek support after quitting.

![Smoking Status Analysis](https://github.com/Cidelx/Mental_Health_Analysis/blob/main/Images/Smoking%20Status%20pie%20chart.png?raw=true)

### 5. Family History of Mental Illness
- A family history of depression is a significant factor in the likelihood of developing mental health issues, although it is not determinative. Many individuals without a family history still experience mental health challenges, highlighting the multifactorial nature of mental health.

![Family History of Depression Analysis](https://github.com/Cidelx/Mental_Health_Analysis/blob/main/Images/Family%20History%20of%20Mental%20Illness.png?raw=true)

## Conclusions

- **Marital Status**: There is a notable association between marital status and mental health, with married and single individuals showing higher incidences of mental illness.
- **Physical Activity**: Physical activity appears to be a crucial factor in mental well-being, with sedentary lifestyles strongly linked to mental illness.
- **Sleep Patterns**: Poor sleep is a significant predictor of mental health issues, particularly when combined with unhealthy dietary habits.
- **Smoking Status**: The relationship between smoking and mental health is complex, with non-smokers and former smokers showing higher incidences of mental illness.
- **Family History**: Family history of depression increases the likelihood of mental illness, but it is not the sole determining factor.

## Recommendations

1. **Promote Physical Activity**: Encourage regular physical activity as a key preventive measure against mental health issues.
2. **Improve Sleep Quality**: Focus on improving sleep hygiene through public health initiatives and workplace programs.
3. **Support Smoking Cessation**: Integrate mental health support into smoking cessation programs to address the psychological challenges of quitting.
4. **Targeted Mental Health Interventions**: Provide tailored support to individuals with a family history of depression and those facing marital challenges.

## Appendices

For those interested in exploring further, additional resources are available:

- **Data**: The complete dataset and any processed versions can be found in the [`Mental Health Analysis/`](https://github.com/Cidelx/Mental_Health_Analysis/blob/main/DepressionData.xlsx) directory.
- **Figures**: All charts and visualizations used in this analysis, along with supplementary figures, are stored in the [`Mental Health Factors Analysis/`](https://github.com/Cidelx/Mental_Health_Analysis/blob/main/Mental_Health_Factors_Analysis.xlsx) directory.

## References

1. Mental Health Foundation. "Factors that affect mental health." *Mental Health Foundation*. (n.d.). [https://www.mentalhealth.org.uk/explore-mental-health/factors-affect-mental-health](https://www.mentalhealth.org.uk/explore-mental-health/factors-affect-mental-health#:~:text=Biological%20factors%2C%20e.g.%20physical%20health,culture%2C%20work%2C%20money%2C%20housing).
2. Therrien, Anthony. "Depression Dataset." *Kaggle*. [https://www.kaggle.com/datasets/anthonytherrien/depression-dataset](https://www.kaggle.com/datasets/anthonytherrien/depression-dataset)


