# Amazon Delivery Time Prediction

## Overview
A **Machine Learning project** that utilizes **advanced regression algorithms** to predict the **estimated delivery time** of Amazon orders using **historical order and shipment data**.  
The goal is to enhance **logistics efficiency** and **customer satisfaction** by providing accurate delivery time estimates.

---

## Objectives
- Predict expected delivery time based on historical order and shipment data.  
- Identify the factors that affect delivery time.  
- Compare multiple regression models to select the best-performing one.

---

## Tech Stack
- **Language:** Python  
- **Libraries:** pandas, scikit-learn, matplotlib, seaborn  
- **Tools:** Jupyter Notebook  

---

## Dataset
- **Source:** Amazon delivery dataset *(Confidential – provided by company during internship)*  
- **Description:** Contains historical shipment records with features such as:

| Variable | Description |
|-----------|-------------|
| Order_Date/Order_Time | Date and time when the order was placed. |
| Pickup_Time | Time when the delivery agent picked up the order. |
| Weather | Weather conditions during delivery. |
| Traffic | Traffic conditions during delivery. |
| Vehicle | Mode of transportation used for delivery. |
| Area | Type of delivery area (Urban/Metropolitan). |
| Delivery_Time | Target variable representing the actual time taken for delivery (in hours). |
| Category | Category of the product being delivered. |

- **Target Variable:** Delivery time (in hours)

---

## Methodology

### Data Preprocessing
- Handled missing values, outliers, and duplicates.  
- Scaled numerical variables and encoded categorical features.

### Exploratory Data Analysis (EDA)
- Visualized data distributions and correlations.  
- Identified key factors influencing delivery time.

### Model Building
- Implemented **Linear Regression**, **Random Forest**, and **Gradient Boosting** models.  
- Tuned hyperparameters using **GridSearchCV**.

### Evaluation
- Compared models using **MAE** and **R² Score**.  
- Selected the best-performing model based on results.

---

## Results

| Model | MAE | R² Score |
|--------|------|----------|
| Linear Regression | 31.93 | 0.34 |
| Random Forest | 17.92 | 0.79 |
| Random Forest (Tuned) | 17.70 | 0.80 |
| Gradient Boosting | 18.47 | 0.79 |

**Best Model:** Tuned Random Forest Regressor (R² = 0.80)

---

## Author
**Nilesh Bahirgaonkar**  
*Data Scientist*  
gmail : nileshbahirgaonkar1494@gmail.com 
🔗 [LinkedIn Profile](https://www.linkedin.com/in/nilesh-bahirgaonkar/)
