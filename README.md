# academic-sat-gpa-prediction-linear-regression
A university admissions analytics model designed to evaluate and predict student cumulative GPA performance based on standardized SAT scores.

# Academic SAT Score vs. GPA Prediction Model

## 1. Business Problem
### 1.1. What is the business objective?
To understand and quantify the empirical relationship between students' SAT scores and their academic performance (GPA), assisting admissions and academic counseling departments.
### 1.2. Are there any constraints?
* GPA can be influenced by external academic support, study habits, and coursework difficulty not reflected in standardized test scores.

## 2. Data Dictionary
| Feature Name | Data Type | Relevance | Description / Reason if Not Relevant |
| :--- | :--- | :--- | :--- |
| `SAT Score` | Continuous (Integer) | High (Predictor) | Standardized entrance test score of the student. |
| `GPA` | Continuous (Float) | High (Target Variable) | Cumulative Grade Point Average achieved by the student. |

## 3. Data Pre-processing
* **3.1. Data Cleaning & Feature Engineering:** Checked for missing values, invalid score bounds, and format consistency.
* **3.2. Outlier Treatment:** Inspected scores and GPAs for anomalies to maintain clean linear trends.

## 4. Exploratory Data Analysis (EDA)
* **4.1. Summary:** Summarized score ranges, means, and standard deviations for admissions metrics.
* **4.2. Univariate Analysis:** Evaluated score distributions using histograms and density plots.
* **4.3. Bivariate Analysis:** Visualized scatter plots highlighting the correlation between entrance exam benchmarks and collegiate GPA.

## 5. Model Building
* **5.1. Simple Linear Regression:** Built baseline Ordinary Least Squares regression using SAT scores to forecast GPA.
* **5.2. Transformations:** Tested log, exponential, and polynomial transformations, recording RMSE, R-Squared, and correlation coefficients.
* **5.3. Model Selection:** Determined the optimal model fit balancing goodness-of-fit and prediction error.
* **5.4. Documentation:** Summarized regression slope, intercept, and error metrics.

## 6. Business Impact / Benefits
Aids university admission committees in setting objective screening thresholds and helps academic advisors identify students who may require early academic support based on entrance metrics.
