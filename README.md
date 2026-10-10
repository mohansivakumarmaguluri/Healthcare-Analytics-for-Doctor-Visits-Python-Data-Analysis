# -Healthcare-Analytics-for-Doctor-Visits-Python-Data-Analysis

## Project Overview
This project focuses on analyzing healthcare data related to doctor visits using Python. It uses exploratory data analysis (EDA) and data visualization to understand doctor visit patterns and explore relationships between healthcare utilization, demographic characteristics, and health-related factors.

## Objectives
- Analyze doctor visit patterns across different age groups and genders.
- Explore the relationship between illness and the number of doctor visits.
- Understand how demographic and health-related factors relate to healthcare utilization.
- Visualize data distributions and relationships to identify meaningful patterns.

## Technologies Used
- **Python** – Data analysis and processing
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Interactive analysis

## Dataset Description
The dataset contains **5,190 rows and 13 columns** related to doctor visits, demographic characteristics, income, illness, health status, and other health-related indicators.

The analysis explores variables such as:
- Number of doctor visits
- Gender and age
- Income
- Illness
- Reduced activity
- Health status
- Insurance indicators
- Chronic-condition indicators

## Project Workflow
1. Load the healthcare dataset using Pandas.
2. Inspect the dataset structure, dimensions, and data types.
3. Generate descriptive statistics and check for missing values.
4. Perform exploratory data analysis on demographic and health-related variables.
5. Analyze doctor visits by gender and other relevant factors.
6. Create visualizations to explore patterns and relationships.
7. Interpret the findings to better understand healthcare utilization.

## Key Analysis
- Distribution of doctor visits.
- Gender distribution and comparison of doctor visits by gender.
- Age distribution and its relationship with doctor visits.
- Relationship between illness scores and doctor visits.
- Comparison of age and doctor visits across genders.

## Repository Structure
```text
Healthcare-Analytics-for-Doctor-Visits/
├── data/
│   └── healthcare_doctor_visits.csv
├── notebooks/
│   └── healthcare_analysis.ipynb
├── README.md
└── .gitignore
```

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Navigate to the `notebooks` folder.
4. Open the notebook:

   ```bash
   jupyter notebook healthcare_analysis.ipynb
   ```

5. Run the notebook cells sequentially to reproduce the analysis.

**Note:** Keep the `data` and `notebooks` folders in their original locations because the notebook uses a relative path to load the CSV file.

## Expected Outcomes
- Better understanding of doctor visit patterns.
- Identification of relationships between demographic characteristics, illness, and healthcare utilization.
- Clear visual representation of healthcare data using Python.
- Practical experience in data cleaning, exploratory data analysis, and visualization.

## Conclusion
This project demonstrates the use of Python-based data analytics to explore healthcare data and understand patterns in doctor visits. It provides practical experience in data analysis and visualization and can serve as a foundation for further healthcare analytics projects.

## Disclaimer
This project is intended for educational and exploratory data analysis purposes only. It is not intended for clinical diagnosis or medical decision-making.
