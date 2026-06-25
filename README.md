# tassk-11# CoreTech Client Data Analysis Dashboard

## Project Overview

This project analyzes CoreTech client data and builds machine learning models to understand client behavior, predict project outcomes, and generate business insights.

---

# Dataset

Datasets used:

1. coretech_clients.csv
2. coretech_clients_cleaned.csv
3. coretech_feedback.csv


---

# Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-Learn

SQLite

NLTK / NLP

Google Colab


---

# Data Cleaning

Performed:

- Checked missing values
- Removed duplicate records
- Cleaned column names
- Fixed data types
- Saved cleaned dataset


Output:

coretech_clients_cleaned.csv


---

# Data Visualization

Created charts:

## Bar Chart
Shows client distribution by service.

## Pie Chart
Shows lead source percentage.

## Line Chart
Shows project budget trend.

## Histogram
Shows client rating distribution.

## Scatter Plot
Shows budget relationship with project duration.


---

# Exploratory Data Analysis

Analyzed:

- Highest demand service
- Top client city
- Best lead source
- Average project budget
- Highest budget service
- Project status count
- Average rating


---

# Machine Learning Models


## 1. Project Budget Prediction

Algorithm:

Linear Regression


Features:

- Service
- Project Duration
- Client City
- Lead Source
- Rating


Evaluation:

- MAE
- MSE
- RMSE
- R2 Score


Purpose:

Predict expected project cost.


---

## 2. Client Status Prediction

Algorithm:

Random Forest Classifier


Target:

Project Status


Classes:

- Pending
- In Progress
- Completed
- Cancelled


Evaluation:

- Accuracy Score
- Confusion Matrix
- Classification Report


Purpose:

Predict project completion status.


---

# Sentiment Analysis

Dataset:

Customer Feedback


Model:

Naive Bayes + CountVectorizer


Tasks:

- Clean feedback text
- Analyze sentiment
- Find common words
- Classify feedback


---

# Business Insights

1. High-value services generate more revenue.

2. Client satisfaction is generally positive.

3. Project duration affects budget.

4. Referrals provide valuable clients.

5. Completed projects represent strong delivery performance.


---

# Business Recommendations

1. Promote high-budget services like AI and Cloud Computing.

2. Improve marketing channels with better client acquisition.

3. Use feedback analysis to improve customer experience.

4. Focus on completing projects on time.

5. Expand services in cities with fewer clients.


---

# Conclusion

CoreTech data analysis helps understand customers,
improve services, predict project outcomes,
and support business decisions.
## Dashboard Charts

![Bar Chart](charts/bar_chart.png)

![Pie Chart](charts/pie_chart.png)

![Sentiment](charts/sentiment_chart.png)
