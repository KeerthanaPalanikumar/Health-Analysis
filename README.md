# HEALTH MONITORING AND ANALYZING USING PYTHON


This project involves analyzing a health monitoring dataset to understand various health metrics and their relationships. The dataset includes patient information such as age, gender, heart rate, blood pressure, respiratory rate, body temperature, activity level, oxygen saturation, sleep quality, stress level, and timestamps.

# Steps and Analysis:

## Data Preprocessing:

  * Importing necessary libraries (pandas, matplotlib, seaborn).
  * Loading the dataset and displaying the first few records.
  * Checking for and handling missing values using median imputation.

## Summary Statistics and Distribution:

  * Calculating summary statistics for numerical columns.
  * Visualizing the distributions of age, heart rate, respiratory rate, body temperature, and oxygen saturation using histograms and KDE plots.

## Gender Distribution and Correlation Analysis:

  * Visualizing gender distribution with a pie chart.
  * Creating a correlation matrix to explore relationships between numerical health metrics.

## Activity Level Analysis:

  * Examining heart rate variations across different activity levels with a boxplot.

## Blood Pressure and Health Metrics by Gender:

  * Extracting systolic and diastolic blood pressure for detailed analysis.
  * Visualizing the distribution of blood pressure values.
  * Analyzing heart rate and oxygen saturation by gender using boxplots.

## Sleep Quality and Stress Level Analysis:

  * Exploring the impact of sleep quality and stress levels on heart rate and oxygen saturation with boxplots.

## Respiratory Rate and Body Temperature by Activity Level:

  * Investigating respiratory rate and body temperature changes across different activity levels.

## Patient Grouping:

  * Categorizing patients by age group (Young, Middle-aged, Senior), blood pressure category (Normal, Elevated, Hypertension Stage 1, Hypertension Stage 2), heart rate category (Low, Normal, High), and oxygen saturation category (Normal, Low).
  * Applying these categorizations to the dataset.

## Visualizing Group Distributions:

  * Creating count plots to visualize the distribution of age groups, blood pressure categories, heart rate categories, and oxygen saturation categories.

## Key Observations:

  * The dataset shows a higher count of seniors compared to young and middle-aged individuals.
  * Most individuals have normal blood pressure, heart rate, and oxygen saturation levels.
  * Activity levels influence heart rate and respiratory rate as expected, with higher rates during physical activities.
  * There is no strong correlation between the health metrics, indicating varied individual responses.

This analysis provides insights into the health status and metrics of the individuals in the dataset, helping to identify patterns and potential areas for further investigation.
