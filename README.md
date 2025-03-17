# Analysing-Students-Mental-Health-SQL-Project-
[Visit DataCamp Project](https://www.datacamp.com/datalab/w/98fa2c4b-a245-4213-a649-6c2a5fd8ebbf/print-notebook/notebook.ipynb)

Description
This project analyzes the mental health challenges faced by international students at a Japanese university, based on survey data collected in 2018 and published in 2019. The study found that international students are at a higher risk of mental health difficulties, with social connectedness and acculturative stress being significant predictors of depression.

Objective
The primary objective of this project is to explore the survey data using PostgreSQL to determine if the findings of the original study hold true. Additionally, the project seeks to investigate whether the length of stay in the host country contributes to mental health outcomes among international students.

Data Description
The dataset includes the following columns:

inter_dom: Types of students (international or domestic)
japanese_cate: Japanese language proficiency
english_cate: English language proficiency
academic: Current academic level (undergraduate or graduate)
age: Current age of student
stay: Current length of stay in years
todep: Total score of depression (PHQ-9 test)
tosc: Total score of social connectedness (SCS test)
toas: Total score of acculturative stress (ASISS test)


Methodology

Data Exploration: Use SQL queries to explore the dataset and understand the distribution of key variables.
Analysis: Perform statistical analysis to compare mental health scores (depression, social connectedness, acculturative stress) between international and domestic students.
Length of Stay Impact: Investigate the relationship between the length of stay and mental health outcomes for international students.
Visualization: Create visualizations to illustrate the findings and make the data more accessible.

Expected Outcomes
Confirmation of higher mental health risks among international students.
Insights into how social connectedness and acculturative stress predict depression.
Understanding of the impact of the length of stay on mental health outcomes.
Tools Used
PostgreSQL: For data querying and analysis.
//Python: For additional data manipulation and visualization.//


How to Run the Project
Clone the repository to your local machine.
Set up a PostgreSQL database and import the dataset.
Run the provided SQL queries to explore and analyze the data.
Use Python scripts to visualize the results.
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.
