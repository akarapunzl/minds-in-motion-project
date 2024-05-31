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
