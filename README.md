# Breast Cancer Survival Analysis

This README provides an overview of a breast cancer survival analysis using a dataset that includes various demographic and clinical factors. The analysis includes data visualizations to explore correlations between patient characteristics and survival outcomes.

## Problem Statement

Breast cancer remains one of the most common cancers affecting individuals worldwide, making it a critical area of research in healthcare. Understanding the factors that influence patient survival can significantly impact treatment decisions, patient counseling, and public health strategies. 

This analysis aims to investigate the relationship between various demographic and clinical factors—such as age, tumor size, lymph node involvement, and hormonal status—and patient survival outcomes. By examining these correlations, we can gain insights into how these variables affect prognosis, potentially leading to improved patient management and targeted interventions.

The dataset, which includes a diverse range of patients and clinical details, allows us to explore important trends and disparities in breast cancer outcomes. This information is not only relevant for healthcare professionals but also for researchers and policymakers looking to enhance cancer care and allocate resources effectively. 

Ultimately, the goal of this analysis is to contribute to a deeper understanding of breast cancer survival, enabling stakeholders to make informed decisions that can improve patient outcomes and quality of life.

## Data Dictionary

The dataset contains the following columns:

- **Age**: Age at diagnosis.
- **Race**: Racial background of the patient.
- **Marital Status**: Marital status of the patient.
- **T Stage**: Tumor stage classification.
- **N Stage**: Lymph node stage classification.
- **6th Stage**: Additional stage classification.
- **differentiate**: Tumor differentiation.
- **Grade**: Tumor grade.
- **A Stage**: Additional tumor stage classification.
- **Tumor Size**: Size of the tumor.
- **Estrogen Status**: Estrogen receptor status.
- **Progesterone Status**: Progesterone receptor status.
- **Regional Node Examined**: Number of regional nodes examined.
- **Regional Node Positive**: Number of positive regional nodes.
- **Survival Months**: Number of months survived after diagnosis.
- **Status**: Patient status (Alive/Deceased).

## Data Cleaning Steps

This dataset of breast cancer patients was obtained from the 2017 November update of the SEER Program of the NCI, which provides information on population-based cancer statistics. The dataset involved female patients with infiltrating duct and lobular carcinoma breast cancer (SEER primary cites recode NOS histology codes 8522/3) diagnosed in 2006-2010. Patients with unknown tumour size, examined regional LNs, positive regional LNs, and patients whose survival months were less than 1 month were excluded; thus, 4024 patients were ultimately included.

## Visualizations

### 1. Correlation of Age and Survival Months

The scatterplot depicts the correlation between age at diagnosis and survival months. The data shows that most people are diagnosed after the age of 35 and most survive anywhere from 40 to 100 months after.

### 2. Distribution of Survival Months by N Stage

The boxplot displays the distribution of survival months by N Stage. The average number of survival months decreases as the number of nodes infected and spread increases.

### 3. Distribution of Tumor Grade vs Survival Months by Type of Cell

The boxplot shows little to no difference between tumor grade in survival months between different types of cells.

### 4. Distribution of Survival Months by Hormonal Status

The boxplot shows the distribution of survival months organized by hormonal status; negative estrogen and progesterone readings indicate an overall lower average in survival months.

### 5. Correlation of the Regional Nodes Examined and Regional Nodes Positive

The scatterplot depicts a positive correlation between the amount of regional nodes examined and the amount of regional nodes found positive.

### 6. Distribution of Survival Months by Marital Status

Although the boxplot shows similar averages for the different categories of marital status, being seperated is associated with the lowest average in months of survival.

### 7. Distribution of Survival Months by Race

The figure shows side-by-side boxplots of the distribution of survival months by race. The "other" category has the highest average of survival months over "white" and "black."

### 8. Correlation of Age and Tumor Size

Most cases of breast cancer are found after the age of 35 and range from tumor sizes of 5 to 55.

### 9. Correlation of Tumor Size and Survival Months

The scatterplot shows a strong correlation between how small the tumor is, the higher amount of survival months a patient will have.

### 10. Distribution of Regional Nodes Examined by Type of Cell

The side-by-side boxplots show the distribution of regional nodes examined by type of cell. The amount of regional nodes examined decreases as the ability to differentiate between cells increases.

## Analysis Insights

- Patients diagnosed at an older age tend to have varying survival outcomes, with younger patients generally showing better survival rates.
- Increased involvement of lymph nodes is correlated with lower survival months.
- Hormonal status appears to significantly influence survival, with negative readings associated with poorer outcomes.
- The data indicates that smaller tumor sizes correlate with longer survival durations.
- Marital status may have an impact on survival, highlighting the importance of social support systems.
- Most breast cancer cases are diagnosed after the age of 35, with tumor sizes ranging from 5 to 55.