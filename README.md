# Hackathon - Math & Stats Brief

## Introduction:
Dr. Igor Panchevski has gathered data to determine whether a specific medication provided to patients at "The Hospital" has been effective in reducing high blood pressure (only systolic pressure is considered). The dataset includes information for 100 patients, recorded in "Prva_zadaca.csv". The column 'Merenje 1' represents the measured pressure on the first day of the study, while 'Merenje 2' represents the pressure after 6 months. The column 'Primil lek ili ne' is a categorical variable (0 or 1), indicating whether a patient received (or not) the medication for lowering blood pressure.

## Tasks:

#### Exploratory Data Analysis (EDA):
a) Choose appropriate visualization methods and provide comments on them (brief textual descriptions and comments for plots).
b) Categorize the data and perform Descriptive Statistics for the obtained variables.
c) Conduct group tests:

#### Determine if there is a difference in measured blood pressure between patients on the first and last days.
Establish whether there is a decrease (or increase) in pressure for patients who received the medication on the first day compared to the end of 6 months.
Determine if there is a decrease (or increase) in pressure for patients who did not receive the medication on the first day compared to the end of 6 months.
Identify if there is a difference between patients who received the medication and those who did not.

#### Classification Algorithm:
a) Using the data from 'Prva_zadaca.csv', construct (train) a classification algorithm to categorize patients into 2 groups - 0 (did not receive medication) and 1 (received medication). Then, for the data from 'Vtora_zadaca.csv':
Categorize patients only based on the first measurement.
Categorize patients only based on the second measurement.
Categorize patients based on both the first and second measurements.
Compare the accuracy of the models for categorizations under a-1), a-2), and a-3), provide comments (brief textual descriptions), and visualize the data (2D / 3D - accordingly in Python, and provide comments for plots).

b) Bonus: Investigate whether data can be categorized using linear regression. Determine which columns should be used to train the model in this case (from the data in 'Prva_zadaca.csv'). Construct linear regression for the same patient categorization as in 'Vtora_zadaca.csv'. What is the R2? Can this score be improved? What does our score depend on in this scenario?

#### Conclusion:
This hackathon focuses on applying mathematical and statistical techniques to analyze medical data related to the effectiveness of a medication in reducing high blood pressure. By exploring various visualization methods, conducting statistical tests, and training classification algorithms, the goal is to derive insights and make informed decisions regarding patient treatment and medication efficacy. Additionally, the bonus task explores the potential of linear regression in categorizing patient data and improving model accuracy.
