# <Center> ![Alt text](images.jpg)

# <Center> Utilizing Macine Learning for Optimal Student Loan Tactics

## <Center>KUBootcamp Data Analytics

## <Center>Project 4 - Group 3 - Yi-Hsiang Chou, Janice Powers, Agustin Zapata

### Project Description

#### The focus of this project is to utilize machine learning to analyze key indicators relevant to pursuing higher education and the associated costs. We worked together to identify 3 key outcomes to analyze using machine learning models to determine predictive outcomes.

#### The 3 key Outcomes:

- Income Prediction
- Repayment Capability
- Employment by Degree

### Machine Learning Methodologies

1. KMeans
2. Tensorflow
3. Keras Tuner
4. Random Forest Regressor

### Prerequisites

1. Python
2. Pyspark
3. Findspark
4. Pyspark.sql
5. Pandas
6. Numpy
7. Matplotlib
8. Sklearn

## Models

#### The dataset we used was the College Scorecard from the U.S. Department of Education. https://collegescorecard.ed.gov/data. The datasets were stored in CSV files. Of the files available we downloaded 2:

- Most Recent Institutional-Level Data
- Most Recent Data by Field of Study

## Income Prediction Model

#### The Field of Study dataset from the College Scorecard were downloaded and cleaned to use for the income prediction model. The cleaned data is stored at https://drive.google.com/file/d/1t0crmMdDN0AJxopDj7E6UhOs2MMm-okB/view?usp=sharing

#### The following steps describe the process:

1. Download the raw datasets to the local computer into the project folder.
2. Use Jupyter Notebook to review and clean the data.
3. Upload cleaned dataset to a google drive.
4. Create a new notebook using Google Colaboratory and link to the dataset.
5. Install necessary packages and initialize a Spark session.
6. Extract dataset from the Google drive and load it into pyspark.sql database.
7. Run exploratory analysis of the dataset.
8. Plot distribution and scatterplot for insights.
9. Transform categorical data with StringIndexer and OneHotEncoder.
10. Assembled the feature data columns into a vector column.
11. Train, test and split the data.
12. Run the linear Regression Model using PySpark’s MLLib returning the mean squared error and the r2 coefficient.
13. Plot the actual vs predicted values.
14. Run Random Forest Regressor model and evaluate the model with the regression evaluator.
15. Plot the actual vs predicted values.
16. Optimized the Random Forest Regressor model.
17. Cross validate to determine the best model.
18. Use the optimized model to make predictions on the test data.
19. Plot the actual vs predicted values of the optimized model.

## Repayment Model

#### The original raw dataset (Most Recent Institution-Level Data) was obtained from https://collegescorecard.ed.gov/data and stored at https://drive.google.com/file/d/1u2_ACLlHvdObvOFXWi567xp6KYVUWG8s/view?usp=drive_link.collegescorecard.ed.govcollegescorecard.ed.gov

1. On the local computer, create a "repayrate_modeling" folder.
2. Inside the "repayrate_modeling" folder, create a folder named "Data" and store the original raw dataset there.
3. Run the "1_PCA_clustering_Ian.ipynb" notebook, which should be located in the same directory as the "Data" folder.
4. At the end of the code, export a CSV file named "cleaned_data.csv" to the "repayrate_modeling" folder.
5. Run the "2_prediction_Ian.ipynb" notebook in the "repayrate_modeling" folder to obtain the modeling results.
6. Run the "3_optimization_colab_Ian.ipynb" notebook in the Google Colab environment for model optimization.

## Employment by Degree Model
1. Download the files or clone the git hub.
2. Run the code using Jupyter Notebook for the results to be reproduced.
3. The CSV file named "cleaned_data.csv" are the results.
4. Run the model and the visualiztions to see more results.

