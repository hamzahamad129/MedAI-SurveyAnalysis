# Medical Students' AI Usage Perception Study

## Overview
This repository contains the complete research workflow for studying **AI Usage Patterns and Perceptions Among Undergraduate Medical Students** as part of MHPE (Masters in Health Professions Education) coursework.

## Research Objective
To investigate and analyze medical students' attitudes, usage patterns, and perceptions regarding Artificial Intelligence tools in medical education and practice.

## Methodology

### 1. Data Collection
- **Tool**: Google Forms questionnaire
- **Target Population**: Undergraduate medical students
- **Data Format**: CSV export from Google Forms

### 2. Data Processing & Cleaning
- **Language**: Python
- **Libraries Used**:
  - `pandas` for data manipulation
  - `openpyxl` for Excel file handling
  - Additional cleaning operations for:
    - Age column standardization (removed "years", "yr" variations)
    - City name formatting (title case)
    - Likert scale conversion (text responses to 1-5 numeric scale)

### 3. Statistical Analysis
- **Software**: JASP (Jeffreys's Amazing Statistics Program)
- **Analysis Type**: Descriptive/Inferential




## Key Data Transformations

### Age Column Cleaning
- Removed text variations: "years", "yr", "y.o", "year old"
- Converted to numeric format for statistical analysis

### Geographic Data Standardization
- Standardized city names to title case format
- Ensured consistent geographical coding

### Likert Scale Conversion
- Converted 36 Likert scale questions from text to numeric:
  - **Strongly Agree** → 5
  - **Agree** → 4
  - **Neutral** → 3
  - **Disagree** → 2
  - **Strongly Disagree** → 1

## Prerequisites
- Python 3.7+
- Required Python packages:
  ```bash
  pip install pandas openpyxl numpy
  ```
- JASP software for statistical analysis

## How to Reproduce This Study

### Step 1: Data Collection 
1. Deploy via Google Forms
2. Export responses as CSV

### Step 2: Data Cleaning
```bash
data_cleaning.py
```

### Step 3: Statistical Analysis
1. Open JASP software
2. Import the cleaned dataset 
3. Run the analysis 


---
*This project was conducted as part of the MHPE program requirements at RIPHA International University, 2025.*
