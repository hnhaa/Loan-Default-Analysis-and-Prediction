# Loan Default Analysis and Prediction  💰 

This project is dedicated to leveraging comprehensive historical data analysis to formulate predictive models assessing the probability of default in future loan portfolios.

## ⚙️ Build Steps

- Conducted data cleaning process and EDA using Pandas, Seaborn, and Matplotlib for a data set of 72 attributes and 42,452 instances.
- Engineered features for enhanced model performance, creating new variables and transforming existing ones.
- Implemented machine learning algorithms (Decision Trees, Random Forest, KNN, SVM and MLP).
- Implemented hyperparameter tuning and cross-validation to optimise model performance and generalise to new data.
- Evaluated model performance using key metrics (accuracy, precision, recall, F1 score & AUC-ROC analysis).
- Achieved the **highest accuracy of 80% from the Random Forest machine learning algorithm**.

## 🎞️ Demo & Snippets

### 1. Data Cleaning & Transformation
Some of the most noteworthy steps to clean and transform the large dataset of loan default include:
- Detecting and Handling Missing Values with KNN Imputer
![alt text](image-12.png)
![alt text](image-1.png)
![alt text](image.png)
- Feature Engineering
    - Binary and Categorical Feature Creation
    ![alt text](image-13.png)
    ![alt text](image-14.png)
    ![alt text](image-10.png)
    - Reduce Dimensionality
    ![alt text](image-15.png)![alt text](image-16.png)![alt text](image-17.png)
    - Attribute Aggregation
    ![alt text](image-18.png)
    ![alt text](image-11.png)
- Handling Outliers
![alt text](image-19.png)
![alt text](image-20.png)
![alt text](image-21.png)
![alt text](image-9.png)
- Label Encoder: I applied a custom mapping to categorical columns. Categorical columns contain nonnumeric data, and to utilise machine learning algorithms effectively, these values need to be transformed into numerical representations.
![alt text](image-22.png)
![alt text](image-23.png)

- Feature Importance and Selection
![alt text](image-24.png)
![alt text](image-8.png)
- Balance Dataset using Upsampling
![alt text](image-25.png)
![alt text](image-7.png)
- Normalisation
![alt text](image-26.png)
![alt text](image-27.png)

### 2. Prediction Model Development
- **Decision Tree Classifier**
![alt text](image-28.png)
![alt text](image-6.png)
- **K-Nearest Neighbour Classifier**
![alt text](image-29.png)
![alt text](image-5.png)
- **Multilayer Perceptron Classifier**
![alt text](image-30.png)
![alt text](image-4.png)
- **Random Forest Classifier**
![alt text](image-31.png)
![alt text](image-3.png)
- **Support Vector Machine Classifier**
![alt text](image-32.png)
![alt text](image-2.png)
x
## 🌟 Future Goals

If given more time, I will implement  statistics analytics to leverage more insights from the current loan applicants in terms of demographics and loan default behaviours.

I also would have tried downsampling instead of upsampling if I had  a chance to rework on the project.




