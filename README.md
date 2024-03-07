# UW Madison Admissions Analysis

## Objective
The main objective of this project is to analyze the admissions data for the University of Wisconsin Madison from 2010 to 2022, focusing on factors such as race, gender, and generation status. The aim is to investigate the trends in the admission rates and to determine if the admissions process is influenced by these factors or if the outcomes are purely by chance.

## Data Sources
The data were collected from student applications to the University of Wisconsin Madison, supplemented with reports to state and federal governments. The datasets include information on general enrollment, admitted students by sex, applicant and admitted students by residence, race, and generation status.

## Methodology
- **Data Analysis Tools**: The project employs R for data analysis, utilizing libraries such as `tidyverse`, `lubridate`, and `dplyr`. Custom scripts `viridis.R` and `ggprob.R` were sourced for enhanced visualization and probability functions, respectively.
- **Data Processing**: The analysis begins with the processing of various CSV files containing data on applicants and admitted students, segmented by different demographics and over the years.
- **Statistical Testing**: To examine the randomness of admissions concerning race, gender, and generation, hypothesis testing was performed, especially focusing on the binomial distribution of admitted students against expected admissions based on overall rates.

## Findings and Interpretations
The project presents a detailed analysis, including graphical representations of applicant trends over years, admissions rates by race, and hypothesis testing results for different demographic groups. Key findings indicate significant deviations from expected admissions rates for most groups, suggesting that the admissions process might not be entirely random and could be influenced by the factors under study.

## Conclusions
- Admissions rates based on sex, race, and generation status show statistically significant deviations from randomness, suggesting a potential influence of these factors on the admissions process.
- While some groups like African Americans did not show a strong deviation, suggesting randomness, other groups, notably by race and sex, showed significant differences from expected rates.
- The findings point towards a need for further investigation into the admissions policies and criteria at the University of Wisconsin Madison, especially to understand the underlying causes of these disparities.

## Future Directions
The project outlines several avenues for future research, including a deeper dive into the most influential factors in admissions, exploration of residence-based admissions trends, correlation analysis between different applicant characteristics, and the use of regression models for more nuanced analysis.

## Shortcomings and Limitations
- The analysis is confined to a single academic year (2022), limiting the ability to discern longer-term trends.
- The statistical significance found in the study might be influenced by the large sample sizes, and further qualitative research could help in understanding the practical significance of the findings.
