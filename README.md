# Heart Attack Risk Analysis

## Author
- Kirsten Perez (@kirstenperez)

## Project Description
This project explores the Heart Attack Risk Prediction Dataset to identify potential relationships between demographic, health, and lifestyle factors that may influence the risk of having a heart attack. Python in Jupyter Notebook will be used to clean and audit the data, identify inconsistencies, and summarize key findings through descriptive statistics. At least one statistical test will be conducted to investigate potential relationships between selected variables. Findings will be presented through static visualizations and an interactive dashboard designed to be clear, accessible, and easy to understand. Data-cleaning decisions and dataset limitations will also be documented to make sure the interpretation of the results are unbiased and more reliable.

### Dataset Information:
- **Name:** Heart Attack Risk Prediction Dataset
- **Source:** https://www.kaggle.com/datasets/iamsouravbanerjee/heart-attack-prediction-dataset
- **Size:** 8,763 rows, 26 columns
- **Type:** Synthetic

| Column | Description |
|---|---|
| Patient ID | Unique identifier for each patient |
| Age | Age of the patient in years |
| Sex | Male or Female |
| Cholesterol | Cholesterol level (mg/dL) |
| Blood Pressure | Blood pressure as text in systolic/diastolic form (for example 158/88) |
| Heart Rate | Heart rate in beats per minute |
| Diabetes | Whether the patient has diabetes (1 = Yes, 0 = No) |
| Family History | Family history of heart problems (1 = Yes, 0 = No) |
| Smoking | Whether the patient smokes (1 = Yes, 0 = No) |
| Obesity | Whether the patient is obese (1 = Yes, 0 = No) |
| Alcohol Consumption | Whether the patient drinks alcohol (1 = Yes, 0 = No) |
| Exercise Hours Per Week | Hours of exercise per week |
| Diet | Dietary habits (Healthy, Average, Unhealthy) |
| Previous Heart Problems | Previous heart problems (1 = Yes, 0 = No) |
| Medication Use | Whether the patient takes medication (1 = Yes, 0 = No) |
| Stress Level | Self-reported stress level from 1 to 10 |
| Sedentary Hours Per Day | Hours of sedentary activity per day |
| Income | Income level of the patient |
| BMI | Body Mass Index |
| Triglycerides | Triglyceride level (mg/dL) |
| Physical Activity Days Per Week | Days of physical activity per week |
| Sleep Hours Per Day | Hours of sleep per day |
| Country | Country of the patient |
| Continent | Continent where the patient lives |
| Hemisphere | Hemisphere where the patient lives |
| Heart Attack Risk | Target variable (1 = at risk, 0 = not at risk) |

## Project Plan

### Interface Plan

- Interactive dashboard: Build a Plotly dashboard and save it as an HTML file that opens in a web browser.
- Interactions: Include hover details, filters for sex, continent, diet, and age group, and zoom and pan features.
- Accessibility: Use clear labels and readable charts. Note to make it accessible for color blindness and sight impairments.
- Feedback: Collect peer feedback on the dashboard and make improvements based on their suggestions.

### Data Collection and Storage Plan
- Source: Download the Heart Attack Risk Prediction Dataset from Kaggle as a CSV file.
- Data audit: Check data types, missing values, duplicate rows, outliers, and dataset dimensions.
- Data cleaning: Use Python and pandas to split blood pressure into systolic and diastolic values, remove the patient ID from analysis, standardize column names, and create age groups.
- Storage: Keep the original file unchanged in the data/ folder and save the cleaned data separately as data/heart_cleaned.csv.
- Documentation: Record cleaning decisions and explain why each change was made.

### Data Analysis and Visualization Plan
- Descriptive statistics: Use pandas to summarize the data and compare groups with and without heart attack risk.
- Statistical testing: Conduct a t-test comparing cholesterol levels or a chi-square test examining smoking and heart attack risk.
- Static visualizations: Create at least five charts using Matplotlib and Seaborn, including:
  1. Heart attack risk by sex
  2. Age distribution by risk group
  3. Cholesterol levels by risk group
  4. Risk rates by diet and smoking status
  5. Correlation heatmap of numeric variables
- Chart design: Explain the choice of chart types and use clear labels, accessible colors, and readable layouts.
- Interactive dashboard: Present key findings in Plotly and explain how interactive features help users explore the data.
- Limitations and bias: Discuss potential sources of bias and explain that synthetic data may not reflect real-world patients.

