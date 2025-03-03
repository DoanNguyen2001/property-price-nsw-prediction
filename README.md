# **Property Price Prediction Analysis**  

This project aims to predict property prices across **Australia** using machine learning models. The dataset includes **for sale, for rent, and sold property listings** from **1986 to 2019**, with attributes like **location, property type, size, and historical prices**.

## **Project Workflow**  

### **1. Data Collection & Preprocessing**  
- Collected **1.1M+ property records** with **65 features**.  
- Handled missing values, removed redundant columns, and updated geospatial data.  
- Performed feature engineering to improve model performance.  

### **2. Exploratory Data Analysis (EDA)**  
- Analyzed trends in **property prices**, **location impact**, and **market variations**.  
- Used **correlation analysis** to identify key predictors of property prices.  
- Detected and handled **outliers** in pricing and property size.  

### **3. Machine Learning Model Development**  
- Built and compared multiple models:  
  - **Linear Regression** (Baseline Model)  
  - **Random Forest** (Best-performing Model)  
  - **Gradient Boosting** (Alternative Ensemble Method)  
- Performed **hyperparameter tuning** for model optimization.  

### **4. Model Evaluation & Results**  
The models were evaluated based on **R² Score** and **Mean Squared Error (MSE)**:  

| Model              | R² Score | MSE |
|-------------------|------------|-------------------|
| **Linear Regression** | 0.1665 | 570,214,410,271.16 |
| **Random Forest** | **0.7778** | **152,015,391,207.92** |
| **Gradient Boosting** | 0.5954 | 276,781,411,055.34 |

- **Random Forest** outperformed other models, achieving the highest accuracy and lowest error.  
- **Linear Regression** had the weakest performance due to the complexity of real estate pricing.  
- **Gradient Boosting** performed better than Linear Regression but was less effective than Random Forest.  

### **5. Conclusion**  
The project successfully developed a robust property price prediction model, with **Random Forest** providing the best performance. By leveraging historical sales data and geospatial features, the model offers valuable insights for **real estate professionals, buyers, and investors**. The results confirm that **location, property size, and historical pricing trends** significantly impact property values.  

### **6. Future Enhancements**  
- Integrate **external economic factors** (e.g., interest rates, inflation) for better predictions.  
- Experiment with **deep learning models** like LSTMs or CNNs for spatial analysis.  
- Deploy the model as an API for real-time property valuation.  
