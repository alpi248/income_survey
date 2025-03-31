# income_survey
# Summary 
## 1 Data Inspection and Cleaning
* First, we loaded the Income Survey Dataset.csv file and cleaned the
## 2 Histograms Showing the Distribution of Numerical Variables
These graphs are used to visualize the distribution of continuous (numerical) variables in the dataset. The goal is to check if the data follows a normal distribution or is skewed to the left or right.

* Age_gap (Age Difference) Histogram
    * Shows how age difference is distributed.
    * Typically, it is used to see if there is a concentration of data within a specific age range.

* Work_yearly (Annual Working Years) Histogram
    * Examines the distribution of working years.
    * It is important for identifying the general trends of how many years people work.

* Emp_week_ref (Worked Weeks) Histogram
    * Shows how many weeks a person worked in a year.
    * It helps to observe if there are any periods of intensive work.

* Total_hour_ref (Total Working Hours) Histogram
    * Shows how many total hours people have worked.
    * It is used to identify groups that work excessively long or very few hours.

* Salary_wages (Salary) Histogram
    * Analyzes the distribution of salaries.
    * It is crucial for identifying income disparities.

* Total_income (Total Income) Histogram
    * Shows the distribution of total income.
    * It is used to identify groups with very low or very high incomes.

* Income_after_tax (Income After Tax) Histogram
    * Shows the distribution of net income after taxes.
    * It helps to understand how individuals derive their net income.

## 3 Scatter Plots Showing the Relationship Between Numerical Variables
These graphs are used to visualize the relationship between two numerical variables.

* Age_gap (Age Difference) - Total_income (Total Income)
    * Shows how income changes with increasing age difference.

* Work_yearly (Annual Working) - Total_income (Total Income)
    * Examines the impact of more years of work experience on income.

* Emp_week_ref (Worked Weeks) - Total_income (Total Income)
    * Shows whether people who work more weeks in a year earn more.

* Total_hour_ref (Total Working Hours) - Total_income (Total Income)
    * Analyzes how income changes for people working more hours.

* alary_wages (Salary) - Total_income (Total Income)
    * Shows how salary contributes to total income.

* Income_after_tax (Income After Tax) - Total_income (Total Income)
    * Shows the direct relationship between net income after tax and total income.

## 4 Box Plots Showing the Effect of Categorical Variables on Income
These plots are used to examine the effect of categorical variables on income.

* Gender (Gender) - Total_income (Total Income) Boxplot
    * Compares the income differences between male and female workers.
    * Analyzes whether there is a gender pay gap.

* Marital_status (Marital Status) - Total_income (Total Income) Boxplot
    * Shows income differences between married, single, divorced, etc. individuals.

* Highest_edu (Highest Education Level) - Total_income (Total Income) Boxplot
    * Examines the effect of different education levels on income.
    * It helps to see if people with higher education tend to earn more.

* Province (Province) - Total_income (Total Income) Boxplot
    * Shows income differences based on the region or province individuals live in.
    * It compares economically developed areas with underdeveloped regions.

## 5 Correlation Heatmap
* Finally, a heatmap is created to visualize the relationships between all numerical variables.
    * Positive correlation: Shows whether two variables increase together.
    * Negative correlation: Indicates if one variable decreases as the other increases.

## 6 Feature Selection
* We selected the best feature (income_after_tax) and the target variable (Gender).

## 7 Splitting the Dataset
* We split the dataset into training and testing sets (80% training, 20% testing).

## 8 Standardizing the Features
* We standardized the features using StandardScaler.

## 9 Applying Machine Learning (ML) and Deep Learning (DL) Algorithms:
* Logistic Regression: We trained and evaluated the model by setting the max_iter parameter to 500.
* Random Forest: We trained and evaluated the model.
* Support Vector Machines (SVM): We trained and evaluated the model.
* Multi-Layer Perceptron (MLP): We trained and evaluated the model.

## 10 Applying K-means Clustering Algorithm: 
* We applied the K-means clustering algorithm and divided the dataset into 3 clusters.

## 11 Visualizing the Results:
* K-means Clustering Results: We visualized the clusters using the Age_gap and income_after_tax features.
* Accuracy of ML and DL Algorithms: We visualized the accuracies of different algorithms using a bar plot.

