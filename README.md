# Student Result Analysis

This project aims to analyze the student scores dataset and extract meaningful insights using data visualization and statistical analysis. The analysis includes handling missing values, performing exploratory data analysis (EDA), and applying a linear regression model to predict Math Scores.


## Dataset
The dataset contains the following columns:

- `Gender`: Gender of the student.
- `EthnicGroup`: Ethnic group of the student.
- `ParentEduc`: Education level of the parent.
- `LunchType`: Type of lunch the student receives.
- `TestPrep`: Whether the student completed test preparation.
- `ParentMaritalStatus`: Marital status of the parent.
- `PracticeSport`: Frequency of sports practice.
- `IsFirstChild`: Whether the student is the first child.
- `NrSiblings`: Number of siblings.
- `TransportMeans`: Mode of transport to school.
- `WklyStudyHours`: Weekly study hours.
- `MathScore`: Score in Mathematics.
- `ReadingScore`: Score in Reading.
- `WritingScore`: Score in Writing.

## Analysis Overview


### 1. Data Cleaning

- Handled missing values for categorical and numerical columns.
- Dropped unnecessary columns.

### 2. Exploratory Data Analysis (EDA)

- Gender distribution using count plots.
- Impact of parent education on student scores using group by and heatmap.
- Impact of parent marital status on student scores using group by and heatmap.
- Distribution of Math, Reading, and Writing scores using boxplots.
- Distribution of ethnic groups using pie chart.
- Comparison of parent education and lunch type using count plots.
- Distribution of Math, Reading, and Writing scores using histograms.
- Violin plots for scores across different ethnic groups.
- Pair plot for visualizing relationships between Math, Reading, and Writing scores.

### 3. Linear Regression Model

- Selected relevant features for predicting Math Scores.
- Split the data into training and testing sets.
- Trained a linear regression model.
- Evaluated the model using Mean Squared Error (MSE) and R-squared (R²) metrics.
- Analyzed model coefficients to understand the impact of different features on Math Scores.

## Results

- The linear regression model explains approximately 67.63% of the variance in Math Scores.
- Significant predictors of Math Scores include Reading Scores, Writing Scores, and weekly study hours.
- Parental education levels have varying impacts on Math Scores.

## Conclusion

This project demonstrates the application of data analysis and machine learning techniques to understand and predict student performance. It highlights the importance of parental education, study habits, and other factors in student success.
