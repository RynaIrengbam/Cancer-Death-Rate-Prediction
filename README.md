# Abstract
Cancer remains one of the leading causes of death worldwide, placing a significant burden on society. There are notable
disparities in the impact of cancer across different regions in the US. The study investigates the relationship between
cancer death rates and various socioeconomic and healthcare-related factors across different regions. Using a compre-
hensive dataset, analysis of the impact of median income, age demographics, health insurance coverage (both private
and public), employment rates, and the presence of clinical trials on cancer mortality. Through descriptive analysis,
it was found that strong correlation, particularly median age showing a significant positive correlation and median
income (correlated with healthcare access) demonstrating a moderate negative correlation with death rate. GAM was
the best model of choice for predicting mortality with the smallest test MSE and highest test R2. Additionally, it can
handle multicollinearity and outliers present in the data effectively. These findings indicate the relationship between
socioeconomic factors and mortality rate and the need for targeted resource allocation and policy changes.

# Introduction
Cancer has consistently been a prominent contributor to mortality, which is a major challenge to public health. The
economic burden is also expected to increase in the coming decades, affecting individuals and the US healthcare
system. But the mortality rate varying significantly across different regions is another matter of concern. For example,
an increase in cancer mortality rate is associated with increasing age. The project aims to understand the
socioeconomic factors and healthcare-related variables that affect the cancer death rate, potentially
addressing the gap in our collective knowledge about the complex interplay between these factors.
By analyzing the relationship between cancer death rates and factors including age, income, employment rate, health
insurance coverage and the presence of clinical trials, the project seeks to uncover patterns that might not be imme-
diately apparent. The study is particularly interesting given the ongoing debate on healthcare access and its impact
on healthcare outcomes. With a greater understanding of the effect of these factors on cancer death
rate, there can be targeted resource allocation for high-risk areas and assist policymakers in making
equitable healthcare policy decisions.

# Dataset
The dataset has been collected from Kaggle. Based on the goal of the project, the following variables have been
selected and created:
• medianage: Median age in the region (Quantitative)
• pctemployed16 over: Employment Rate (Quantitative)
• medincome: Median income in the region (Quantitative)
• pctprivatecoverage: Percentage of population covered by private health insurance (Quantitative)
• pctpubliccoverage: Percentage of population covered by public health insurance (Quantitative)
• clinical trails: Whether cancer-related clinical trials conducted (Categorical)
• deathrate per 1000: Death Rate per 1,000 people (quantitative)

# Conclusion
The analysis of cancer death rates across regions reveals complex relationships between socioeconomic factors and
mortality outcomes. The comparison of various regression techniques shows that GAM provides the most accurate
predictions, with an R² of 0.643 and the lowest MSE of 0.130399. Median Age was identified as the strongest predictor
of cancer death rates with age explaining approximately 50% of the variation in death rate. Additionally, variables
like median income has an inverse relationship with death rates, and the presence of clinical trials is associated with
lower mortality rates.
The analysis also revealed important patterns in healthcare coverage, with regions having higher private insurance
coverage generally showing lower death rates. The presence of significant multicollinearity between predictors, particu-
larly between income, employment, and insurance coverage types, suggests complex interactions between socioeconomic
factors affecting cancer mortality. These findings have important implications for healthcare policy and resource allo-
cation. They suggest that targeted interventions considering age demographics, income levels, and healthcare access
could be effective in reducing cancer mortality rates. The results also highlight the potential benefit of expanding
clinical trials to more regions, given their association with lower death rates.
