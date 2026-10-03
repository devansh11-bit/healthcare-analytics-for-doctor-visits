# Healthcare Analytics for Doctor Visits

A data analytics project that explores patterns associated with doctor visits using healthcare-related demographic, health, financial, healthcare-support, and chronic-condition variables.

## Project Overview

The project uses a healthcare dataset containing **5,190 records and 13 columns**. The analysis focuses on understanding why some individuals visit doctors more often than others.

The project covers:
- Data loading and understanding
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Bivariate and multivariate analysis
- Correlation analysis
- Data visualization
- Key findings and conclusion

## Problem Statement

People may visit doctors at different frequencies depending on their health conditions, illness, age, income, activity limitations, and chronic health conditions.

The objective of this project is to analyze the healthcare dataset and identify patterns associated with the number of doctor visits. The analysis examines health condition, illness, socioeconomic background, healthcare support, and chronic conditions to understand their relationship with healthcare utilization.

## Dataset

The dataset contains 5,190 records and 13 columns.

Important variables include:

| Column | Description |
|---|---|
| `visits` | Number of doctor visits during the covered period |
| `gender` | Gender of the person |
| `age` | Age value |
| `income` | Income level |
| `illness` | Number of illnesses or reported health problems |
| `reduced` | Days normal activities were reduced due to health problems |
| `health` | General health indicator |
| `private` | Private healthcare/insurance support |
| `freepoor` | Free healthcare support based on financial need |
| `freerepat` | Repatriation-related healthcare support |
| `nchronic` | Chronic health condition indicator |
| `lchronic` | Long-term chronic health condition indicator |

`Unnamed: 0` is a record identifier and is removed during analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

The notebook includes:

1. Dataset inspection using `head()`, `tail()`, `shape`, `info()`, and `describe()`
2. Missing-value and duplicate checks
3. Removal of the record identifier column
4. Gender distribution analysis
5. Age distribution analysis
6. Doctor-visit distribution
7. Gender vs doctor visits
8. Illness vs doctor visits
9. Age vs doctor visits
10. Health vs doctor visits
11. Reduced activity vs doctor visits
12. Income vs doctor visits
13. Chronic-condition analysis
14. Healthcare-support analysis
15. Correlation analysis
16. Multivariate visualizations
17. Summary of key findings

## Key Findings

- Most individuals in the dataset reported zero doctor visits.
- Average doctor visits increase across higher illness levels.
- Reduced activity has a noticeable positive relationship with doctor visits.
- Individuals with long-term chronic conditions show higher average doctor visits.
- Female participants have a higher average number of doctor visits than male participants in this dataset.
- Illness, reduced activity, health, and age show positive relationships with doctor visits.
- Income has a relatively weak negative relationship with doctor visits.

> These findings describe associations observed in the dataset and should not be interpreted as causal relationships.

## Repository Structure

```text
Healthcare-Analytics-for-Doctor-Visits/
│
├── data/
│   └── healthcare_doctor_visits.csv
│
├── notebooks/
│   └── Healthcare_Analytics_for_Doctor_Visits.ipynb
│
├── presentation/
│   └── Healthcare_Analytics_Project_Presentation.pptx
│
├── docs/
│   └── Dataset_Explanation.docx
│
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/healthcare-analytics-for-doctor-visits.git
cd healthcare-analytics-for-doctor-visits
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/Healthcare_Analytics_for_Doctor_Visits.ipynb
```

## Project Objective

The overall objective is to use data analysis and visualization to understand healthcare utilization patterns and identify factors associated with doctor visits.

## Author

**Devansh Soni**

B.Tech CSE Student
