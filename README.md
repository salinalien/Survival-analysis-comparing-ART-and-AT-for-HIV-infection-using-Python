# Survival-analysis-comparing-ART-and-AT-for-HIV-infection-using-Python
This project conducts survival analysis to compare the effectiveness of Antiretroviral therapy (ART) versus Ayurvedic therapy (AT) for HIV infection. The analysis explores the survival outcomes of patients under each treatment and investigates if there's a significant difference in survival rates between the two groups.


# Data
- Dataset: Antiretroviral therapy vs Ayurvedic therapy for HIV Infection.csv
- File containing analysis: Antiretroviral therapy vs Ayurvedic therapy for HIV Infection.ipynb


The dataset used for this analysis contains the following variables:
- Time of Event: Time in days representing the duration until an event (e.g., death) occurs.
- Total no. of patients died in both groups: Total number of patients that have died in both ART and AT groups.
- No. of patients died - ART group: Number of patients that died in the ART group.
- No. of patients died - AT group: Number of patients that died in the AT group.
- Live at start of day: Number of patients alive at the start of each day.


# Tools and Libraries
- Python: Used for data manipulation, preprocessing, and analysis.
Libraries:
- pandas: Data manipulation and analysis.
- numpy: Mathematical operations.
- matplotlib: Data visualization.
- lifelines: Survival analysis.

# Conclusion
Through Kaplan-Meier curves, survival probabilities over time for patients under each treatment were observed. The log-rank test revealed a significant difference in survival between the ART and AT groups.
