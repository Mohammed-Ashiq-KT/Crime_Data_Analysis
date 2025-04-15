📊 Predicting Crime Trends & Identifying High-Risk Areas Using Machine Learning

1. 🎯 Project Goal
   
The goal of this project is to leverage machine learning and exploratory data analysis (EDA) to understand crime patterns, predict future crime occurrences, and identify high-risk areas. These insights are crucial for optimizing law enforcement efforts and implementing preventive measures effectively.

2. 📚 Data Source & Description
   
Source: Crime Data from 2020 to Present
Type: Public Open Government Dataset
Format: CSV
Size: 1,005,104 rows × 28 columns
Data Types:

float64: 8 columns

int64: 7 columns

object: 13 columns

3. 🧰 Tools & Libraries Used
   
Data Manipulation: pandas, numpy

Visualization: matplotlib.pyplot, seaborn

Machine Learning:

train_test_split (for data splitting)

LabelEncoder (for categorical encoding)

LogisticRegression

RandomForestClassifier

Evaluation Metrics:

accuracy_score

confusion_matrix

classification_report

4. 🔍 Data Understanding & Cleaning
   
Inspected data shape, types, and null values.

Dropped irrelevant columns such as Report_Type, MO Codes, Crime Code 1/2/3/4, etc.

Checked for and handled missing values.

Converted DATE OCC column to datetime format and extracted Year, Month, Day.

Encoded categorical variables using LabelEncoder.

5. 📊 Exploratory Data Analysis (EDA)
   
Several visualizations were performed to uncover insights:

Top Crimes Reported:

Visualized using bar plots to show the most frequent crime types.

Crime Trends Over Time:

Plotted trends by month and year to detect seasonal or temporal patterns.

Crime by Location:

Analyzed frequency by AREA NAME to identify hotspots.

Relationship Analysis:

Heatmap of correlation matrix to detect relationships between numerical variables.

6. 🤖 Machine Learning Models
   
a. Logistic Regression

Applied after feature engineering and train-test split.

Accuracy Score: reported based on output in the notebook.

Evaluated using confusion matrix and classification report.

b. Random Forest Classifier

Implemented as a more robust, ensemble-based alternative.

Compared accuracy with logistic regression.

Results showed higher accuracy and better generalization.

7. 📈 Results & Insight
   
The Random Forest model outperformed Logistic Regression.

High-crime areas were identified for strategic planning.

Temporal patterns helped identify peak months/days for crime.

Model predictions can be used for resource allocation and early alerts.

8. ✅ Conclusion
   
This project effectively demonstrates how machine learning and EDA can be applied to public crime datasets to:

Understand urban crime patterns

Build predictive models for future occurrences

Assist authorities in focusing preventive efforts in high-risk zones

Future work could include incorporating geospatial modeling, real-time data, and deep learning for enhanced predictions.

Data Set : https://drive.google.com/drive/folders/1X93xJjPmyi0rohlzyfb_Kxzmid3JZPjE

PowerBi Dashboard : https://drive.google.com/drive/folders/1uX-jDWd8xxW3nBa6SouwEc5qYiM42Miv
