# Car Price Prediction: A Data Science Approach

This repository contains the implementation and results of a car price prediction project, which achieved a **Top 3 Ranking on Kaggle**. The project focuses on predicting the prices of luxury and non-luxury cars using advanced machine learning techniques and feature engineering.

---

## **Project Overview**

Predicting car prices accurately is a challenging task due to the diverse factors that influence vehicle pricing. This project addresses this challenge by leveraging real-world datasets and applying machine learning to develop highly accurate models for luxury and non-luxury car segments.

### **Key Features**
- Separate modeling for luxury and non-luxury cars using **LightGBM** and **Random Forest**.
- Utilization of **VIN overlap** between training and test datasets to directly improve prediction accuracy.
- Comprehensive feature engineering to identify key predictors.
- Submission of final predictions to Kaggle, achieving a **MAPE score of 0.08729**.

---

## **Repository Structure**


---

## **Project Objectives**

1. **Data Processing and Cleaning**:
   - Handle missing values and irrelevant features.
   - Ensure consistent formatting for machine learning pipelines.

2. **Predictive Modeling**:
   - Train separate models for luxury and non-luxury cars.
   - Optimize model parameters using Grid Search and feature selection.

3. **Feature Engineering**:
   - Identify and utilize VIN overlap between datasets for direct price assignment.

4. **Kaggle Submission**:
   - Evaluate the model's performance through the Kaggle competition.

---

## **Tools and Techniques**

- **Languages**: Python
- **Libraries**: pandas, NumPy, scikit-learn, LightGBM, matplotlib
- **Data Visualization**: Matplotlib, Seaborn
- **Machine Learning Models**:
  - LightGBM: For both luxury and non-luxury car predictions.
  - Random Forest: As an alternative model for luxury car predictions.

---

## **Results**

- Achieved a **Top 3 Ranking** in the Kaggle competition.
- MAPE score of **0.08729** with precise predictions for both luxury and non-luxury cars.
- Enhanced accuracy using VIN overlap for known price assignment.

---

## **Usage Instructions**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/car-price-prediction.git
   cd car-price-prediction
