# 📊 Healthcare Analytics Project
![image](https://github.com/user-attachments/assets/3feaaf19-d74d-4fbb-8cc3-f688143a210e)


## 📁 Project Overview

This project is part of the Capstone requirement for the Data Analytics course. The objective is to perform exploratory and visual analysis on a healthcare dataset using **Tableau**. The dataset contains information about patients’ blood pressure, BMI, glucose, insulin, and diabetes status, for individuals aged 20 and above.

## 📂 Dataset Used

- **File Name**: `Healthcare.csv`

## 🧰 Tools & Technologies

- Tableau Public / Tableau Desktop
- Extract Connection (not Live)
- Data Visualization, Dashboards, Story

## 🎯 Project Objectives

1. Create two dashboards:
   - One with a healthcare image and descriptive title.
   - One with multiple interactive visualizations.
2. Build a Story combining both dashboards and additional views.
3. Provide visual insights on diabetes, blood pressure, BMI, and other health factors.

## 📊 Dashboards

### 🩺 Dashboard 1: Introduction

- Embedded a relevant healthcare image.
- Added a meaningful **Text Object** title based on data analysis.

### 📈 Dashboard 2: Patient Analytics

#### ✅ View 1: Diabetic vs Non-Diabetic (Shape View)
- Created a calculated field from `Outcome` (1 = Diabetic, 0 = Non-diabetic).
- Used shapes and colors to display percentage distribution.
- Tooltip shows patient count.
- Enabled Action filters.

#### ✅ View 2: Patient summary by Blood Pressure category
- Displayed patient count by blood pressure category.
- Used shapes and labels.
- Differentiated diabetic status using color.
- Enabled Action filters.

#### ✅ View 3: BMI by Age Group (Histogram)
- Created `Age` bins with size = 5 (e.g., 20-24, 25-29).
- Edited aliases for clarity.
- Displayed average BMI values (rounded to 2 decimals).
- Colored using shades of red based on average BMI.

#### ✅ View 4: BMI Type Distribution (Single Bar)
- Classified BMI into:
  - Underweight (<18.5)
  - Healthy Weight (18.5–24.9)
  - Overweight (25–29.9)
  - Obese (30+)
- Showed percentage distribution in a single bar.
- Enabled Action filters.

#### ✅ View 5: Diabetic Patients by Blood Pressure
- Calculated field to highlight diabetic patients with High/Low BP.
- Displayed with bar chart.

#### ✅ View 6: Heat Map - Health Factors by Age Group
- Created a heat map to display health factors (e.g., BMI, glucose, insulin) by age group.

## 📖 Story

- **Story Name**: `Healthcare`
- **Story Title**: `Healthcare Summary Report`
- **Story Layout**: Navigator (Numbers)
- **Story Size**: Custom Size

### 📌 Story Points:

1. Dashboard 1 – Healthcare Overview
2. Dashboard 2 – Patient Analysis
3. Heat Map Worksheet – Health Factors by Age

## 📬 Contact

For questions or feedback related to the project, please contact:

- **Name**: Komal Sahu
- **Email**: komal.sahu2511@gmail.com
