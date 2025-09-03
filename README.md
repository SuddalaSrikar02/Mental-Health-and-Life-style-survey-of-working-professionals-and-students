Mental Health Conditions Analysis
This repository contains a Jupyter Notebook that analyzes a dataset on mental health conditions. The project aims to explore the various factors that may contribute to or be associated with mental health issues, providing insights into the relationships between professional life, personal habits, and well-being.

About the Dataset
The dataset used in this analysis contains 93,800 records and 16 columns. It includes information on individuals' mental health conditions, with data points such as:

Demographics: Gender, Age, City

Professional/Academic Status: Whether an individual is a working professional or a student, their profession, and work/study hours.

Lifestyle Factors: Sleep duration and dietary habits.

Work-related Factors: Work pressure and job satisfaction.

Mental Health Indicators: Suicidal thoughts and family history of mental illness.

Key Findings
The notebook provides several observations from the initial data exploration:

The dataset is comprised of 93,800 rows and 16 columns, representing a large sample of individuals.

The analysis found a weak negative correlation (approximately -0.04) between work pressure and job satisfaction, suggesting a slight tendency for job satisfaction to decrease as work pressure increases.

Some data points, such as Profession, Work Pressure, and Job Satisfaction, have missing values, which were addressed in the data cleaning process.

Project Structure
Mental Health conditions.ipynb: The main Jupyter Notebook containing the data loading, cleaning, and analysis code.

project1.csv: The dataset used in this project. (Note: The notebook references this file path directly, so you may need to adjust it for your environment).

How to Run the Notebook
Clone this repository to your local machine.

Ensure you have a Python environment with Jupyter Notebook and the necessary libraries installed (e.g., pandas, numpy).

Place your project1.csv file in the same directory as the notebook, or update the file path in the code.

Open the Mental Health conditions.ipynb file in Jupyter Notebook and run the cells sequentially to reproduce the analysis.

Conclusion
This project serves as a foundational analysis of mental health conditions, highlighting the importance of factors like work pressure and job satisfaction. The cleaned and structured dataset is ready for further, more in-depth analysis, visualization, and predictive modeling.
