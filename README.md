# CARDIOVASCULAR-DISEASE-PROTECTION

## Project Overview
The **Cardiovascular Disease Prediction** project aims to predict the occurrence of cardiovascular disease in patients based on their medical records and history. By analyzing various factors, the project calculates the probability of cardiovascular disease developing in a patient. This predictive model is a valuable tool in identifying individuals who are at higher risk and enabling early intervention.

## Table Of Content 
- [Tools Used](#tools-used-while-performing-the-analysis)
- [Data Cleaning](#data-cleaning-step-used-in-python)
- [EDA](#performed-the-eda-task-in-python)
- [Features](##DataDictionary)
- [Dashboard in Tableau](#using-the-cleaned-dataset-performed-interactive-dashboard-in-tableau)
- [Result](##Impact)
- [Conclusion](Inconclusion)

## Tools Used While performing the Analysis
- Excel - [Download Dataset Here](https://drive.google.com/file/d/1tCgnQWVrW0e4ilhfqvEtdRSqjIsVIcGY/view?usp=drive_link)
- Python
  - Jupyter notebook - Cleaning the dataset and showing the graphical visualizations.

- Tableau - Created an interactive dashboard for analysising all the outcome.


## Data Cleaning Step Used In Python 
- imported the necessary libraries.
- loaded the csv file from the system.
- performed the cleaning analysis:
  - Removing duplcates.
  - Replacing/Droping the Null/NA values.
  - adjusted the dtypes of date and time columns.
  - droped the unnecessary columns to remove confuctions

## Data Dictionary
The project utilizes a comprehensive dataset with the following features:

| Feature                    | Description                                       |
|---------------------------|---------------------------------------------------|
| General Health            | General health condition of the patient.          |
| Checkup                   | Date of the patient's last medical checkup.       |
| Exercise                  | Whether the patient engages in regular exercise.  |
| Heart Disease             | Presence of existing heart disease in the patient.|
| Skin Cancer               | Presence of skin cancer in the patient.           |
| Other Cancer              | Presence of other types of cancer in the patient. |
| Depression               | Presence of depression in the patient.           |
| Diabetes                  | Presence of diabetes in the patient.              |
| Arthritis                 | Presence of arthritis in the patient.             |
| Sex                       | Gender of the patient.                           |
| Age-Category              | Age category of the patient.                     |
| BMI                       | Body Mass Index of the patient.                  |
| Smoking History           | Patient's history of smoking.                    |
| Alcohol Consumption       | Patient's alcohol consumption habits.            |
| Fruit Consumption         | Patient's consumption of fruits.                 |
| Green Vegetable Consumption | Patient's consumption of green vegetables.    |
| Fried Potato Consumption | Patient's consumption of fried potatoes.         |

## Performed the EDA Task In Python:
1.Patient Demographics :-
Gender Distribution,
Age Distribution,
BMI Distribution.

2.General Health and Last Checkup :-
General Health and Last Checkup Correlation.

3.Exercise and General Health :-
Impact of Exercise on General Health.

4.Food Consumption Analysis :-
Alcohol Consumption,
Fruit Consumption,
Green Vegetables Consumption,
Fried Potato Consumption.

5.Medical History :-
Heart Disease Prevalence,
Skin Cancer Cases,
Other Cancer Incidence,
Depression Rate,
Diabetes Cases,
Arthritis Incidence,
Patient's Smoking History.

Smoking Habits Analysis
## Using the cleaned dataset performed Interactive Dashboard in Tableau
- [Tableau Dashboard](https://public.tableau.com/views/FinalYearProject_17188948702440/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Impact
Through thorough exploratory data analysis, significant insights were revealed about the factors contributing to cardiovascular disease:

- Age plays a crucial role, with individuals above the age of 55 being more prone to cardiovascular disease. The risk escalates with age, reaching a peak in patients aged 80 and above.
- Higher BMI is correlated with an increased likelihood of cardiovascular disease.
- Surprisingly, exercise can have varying effects based on age. While exercise generally reduces risk, older patients who exercise extensively might face elevated risks due to increased heart strain.
- Dietary habits significantly influence the disease. Patients consuming more fruits and green vegetables exhibit lower susceptibility to cardiovascular disease, while those consuming fried potatoes are more prone.
- Smoking history is a notable risk factor.
- Intriguingly, medical history concerning cancer, arthritis, diabetes, and depression showed no significant impact on cardiovascular disease risk.

This project's predictions and insights empower healthcare professionals to identify high-risk patients and implement preventive measures, ultimately reducing the prevalence of cardiovascular disease.

In conclusion, the Cardiovascular Disease Prediction project underscores the importance of data-driven approaches in healthcare, aiding in the proactive management of patients' cardiovascular health.
