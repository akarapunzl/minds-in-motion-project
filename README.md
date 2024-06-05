# minds-in-motion-project

Project Proposal Document
https://docs.google.com/document/d/1oPRr9OlwbEjcbe5TWQCvG9sY_givHJHgWird6HvFv_w/edit

Dataset link
 https://www.kaggle.com/datasets/rohit265/loan-approval-dataset

Dataset citation
@misc{rohit_sharma_2024,
	title={Loan Approval Dataset},
	url={https://www.kaggle.com/dsv/8173310},
	DOI={10.34740/KAGGLE/DSV/8173310},
	publisher={Kaggle},
	author={Rohit Sharma},
	year={2024}


Let's start by loading the dataset and inspecting its contents. Then we'll preprocess the data, split it into training and testing sets, and fit a logistic regression model for loan approval prediction.

Step-by-Step Process
Load the dataset: Load the dataset to understand its structure and contents.
Inspect the data: Look at the first few rows and summary statistics.
Preprocess the data: Handle missing values, encode categorical variables, and scale the features if necessary.
Split the data: Divide the data into training and testing sets.
Train the model: Fit a logistic regression model.
Evaluate the model: Assess the model's performance using appropriate metrics.

The dataset consists of 252,000 entries with 12 columns. The columns include both numerical and categorical data. Here is a brief overview:

Numerical columns: Income, Age, Experience, CURRENT_JOB_YRS, CURRENT_HOUSE_YRS, Risk_Flag
Categorical columns: Married/Single, House_Ownership, Car_Ownership, Profession, CITY, STATE




Tableau Storytelling for Loan Applicants' Data
Here’s a detailed storytelling approach for your loan applicants' dataset using Tableau. The aim is to create a comprehensive narrative that can guide stakeholders through the insights derived from the data.

Story Points Overview

Introduction and Dataset Overview
Demographic Insights
Financial Status Analysis
Employment and Experience Analysis
Risk Assessment by Demographics
Geographical Insights
Housing and Car Ownership Analysis
Profession and Risk Analysis
Loan Risk Prediction and Key Insights
Conclusion and Recommendations
Detailed Story Points

1. Introduction and Dataset Overview
Visualization: Text box and a basic bar chart

Content: Introduce the dataset, explain its key features, and the purpose of the analysis.
Visual: A bar chart showing the distribution of Risk_Flag (risky vs. non-risky applicants) to provide an initial overview of the dataset.
2. Demographic Insights
Visualization: Bar charts and pie charts

Visual 1: Bar chart showing the distribution of applicants by Age group.
Visual 2: Pie chart showing the marital status (Married/Single) distribution.
Insight: Understand the age and marital status distribution among applicants.
3. Financial Status Analysis
Visualization: Box plots and bar charts

Visual 1: Box plot showing the distribution of Income across different Age groups.
Visual 2: Bar chart comparing the average Income of risky vs. non-risky applicants.
Insight: Determine the financial status of applicants and how income levels correlate with loan risk.
4. Employment and Experience Analysis
Visualization: Line charts and scatter plots

Visual 1: Line chart showing the relationship between Age and Experience.
Visual 2: Scatter plot showing Income vs. Experience colored by Risk_Flag.
Insight: Analyze how professional experience influences income and risk assessment.
5. Risk Assessment by Demographics
Visualization: Stacked bar charts and heatmaps

Visual 1: Stacked bar chart showing the Risk_Flag distribution across different Age groups.
Visual 2: Heatmap showing Risk_Flag distribution by Married/Single and House_Ownership.
Insight: Identify demographic factors contributing to loan risk.
6. Geographical Insights
Visualization: Maps

Visual 1: Map of India showing the count of loan applicants by STATE.
Visual 2: Heatmap on the map showing the distribution of risky vs. non-risky applicants across states.
Insight: Geographical analysis of loan applications and risk distribution.
7. Housing and Car Ownership Analysis
Visualization: Bar charts and pie charts

Visual 1: Bar chart showing the distribution of House_Ownership status.
Visual 2: Pie chart showing the distribution of Car_Ownership status.
Visual 3: Bar chart showing the Risk_Flag distribution for applicants with and without car/house ownership.
Insight: Understand how ownership status of house and car affects loan risk.
8. Profession and Risk Analysis
Visualization: Bar charts and bubble charts

Visual 1: Bar chart showing the count of applicants by Profession.
Visual 2: Bubble chart showing Income vs. Profession colored by Risk_Flag.
Insight: Identify which professions are more associated with risky applicants.
9. Loan Risk Prediction and Key Insights
Visualization: Dashboards and summary text

Visual 1: Dashboard combining key insights from previous analyses.
Visual 2: Summary text highlighting important findings such as demographic factors affecting risk, geographical hotspots, and risk distribution by profession.
Insight: Provide a comprehensive view of risk factors and predictors for loan applications.
10. Conclusion and Recommendations
Visualization: Text box and strategic visuals

Content: Summarize key findings and provide actionable recommendations for stakeholders.
Visual: Strategic visualizations (e.g., top 3 recommendations highlighted with supporting visuals).
Implementation in Tableau
Data Preparation:

Clean and preprocess the dataset.
Ensure all categorical variables are appropriately encoded.
Create Individual Visualizations:

Use Tableau to create each visualization as described in the storytelling points.
Build Dashboards:

Combine related visualizations into dashboards for each story point.
Create Story Points:

Use Tableau’s story feature to link dashboards and visualizations into a cohesive narrative.
Add Descriptions and Annotations:

Add text boxes and annotations to explain each visualization and its insights.
Review and Iterate:

Review the story with stakeholders and make adjustments based on feedback.
By following this structured approach, you can create a compelling and informative story in Tableau that provides valuable insights into loan applicants' characteristics and their risk assessments.










ChatGPT can make mistakes. Check important info.
