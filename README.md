The goal of this small project was to expand a medical dataset by adding a new column named Depression based on predefined medical and exam score conditions. The expanded dataset was then saved as a new CSV file for further analysis.

Key Steps:
Dataset Import:
The dataset was successfully imported from an external source using the requests library to fetch the raw CSV file from a GitHub repository. The dataset was read into a pandas DataFrame for further processing.

Depression Column Addition:
A new column Depression was added to the dataset, and values were assigned based on the following rules:

25% of individuals with Heart Disease were assigned depression.
25% of individuals with Diabetes were assigned depression.
25% of individuals with Cancer were assigned depression.
40% of individuals with Stroke were assigned depression.
30% of individuals with Exam Score 47 or below were assigned depression.
5% of the remaining population (those not fitting the above categories) were randomly assigned depression.
CSV Export:
The modified dataset, now containing the Depression column, was saved as a new CSV file (depression_dataset.csv) for further use or analysis.

Report:
The first 3 rows of the modified dataset were displayed to verify the changes, and the total percentage of individuals with depression in the dataset was calculated and reported.

Insights:
This project expands the dataset by incorporating mental health (depression) as a key factor based on co-occurrence with other medical conditions and performance indicators (e.g., exam scores).
The added Depression column can now be used for further exploratory data analysis (EDA) or machine learning models to understand its impact on health outcomes.

Conclusion:
The project successfully enhanced the dataset with a new feature, making it more comprehensive for future analysis. 
