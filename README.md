# Hypothesis-Testing-with-python


# Hypothesis Testing Project: Sleep Duration & Sleep Disorders
## Project Overview
This project investigates whether there is a statistically significant difference in sleep duration between individuals with and without sleep disorders using Python. The analysis is grounded in inferential statistics, specifically hypothesis testing, and supported with exploratory data analysis (EDA) and data visualization.

## Research Question
Is there a significant difference in sleep duration between individuals with and without sleep disorders?

#### Hypotheses
* Null Hypothesis (H₀): There is no significant difference in sleep duration between people with and without sleep disorders.

* Alternative Hypothesis (H₁): There is a significant difference in sleep duration between people with and without sleep disorders.

### Objectives
Calculate average sleep durations for both groups.

Test the assumption of normality for both groups.

Perform the appropriate statistical test (t-test or Mann-Whitney U test).

Interpret and draw conclusions based on the p-value.

Visualize the distributions of sleep duration.

#### Tools & Technologies
Language: Python

Libraries: pandas, seaborn, matplotlib, scipy.stats,Jupyter Notebook, dash/plotly

Data Source: kaggle

### Data Description
The dataset contains individual-level data with the following relevant columns:

Sleep Duration (in hours)

Sleep Disorder (categorical: Insomnia, Sleep Apnea, None)

Other variables: Age, Gender, Stress Level, Physical Activity, etc.

### Methodology
Descriptive Statistics: Mean sleep durations were computed.

##### Normality Test:
Shapiro-Wilk test was used to check for normality.

###### Statistical Test:

Since the data was not normally distributed, the Mann-Whitney U test was applied.

##### Visualization:

Box plots and histograms were used to compare distributions between groups.

##### Key Findings
Mean Sleep Duration (With Disorder): ~6.81 hours

Mean Sleep Duration (Without Disorder): ~7.36 hours

Mann-Whitney U Test result:

U-statistic: 10906.0

p-value: < 0.001

###### Conclusion: 
There is a statistically significant difference in sleep duration between individuals with and without sleep disorders. Individuals without sleep disorders tend to sleep longer.

#### Visuals
Boxplot comparing sleep durations by disorder status

![image](https://github.com/user-attachments/assets/229de84c-49ca-4370-865d-bdf0240e8ded)


Histogram showing distribution of sleep duration in both groups

![image](https://github.com/user-attachments/assets/ababfcd0-7b49-4331-ac6d-43a12e5e4f72)


##### Future Work
Extend analysis to assess impact of stress or physical activity on sleep quality.

Apply similar hypothesis testing methods to financial or marketing data.

Integrate interactive dashboard using Dash or Streamlit.
