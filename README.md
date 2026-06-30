# Restaurant Rating Prediction using Machine Learning

## Project Overview

This project builds a Machine Learning model to predict restaurant ratings based on key restaurant attributes such as cuisine type, location, cost, customer engagement, and service features.

It demonstrates an end-to-end Data Science pipeline, from raw data handling to model evaluation and business insights.

### End-to-End Workflow:
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Data Visualization  
- Model Building  
- Model Evaluation & Comparison  
- Business Insights & Recommendations  

---

## Business Problem

Restaurant ratings strongly influence:
- Customer decision-making  
- Restaurant visibility on platforms  
- Revenue and customer trust  

However, ratings are often subjective and influenced by multiple factors.

### Objective:
To build a predictive model that estimates restaurant ratings using historical data, enabling data-driven decision-making for stakeholders.

---

## Who Benefits From This Model?

- Restaurant Owners → Improve service and strategy  
- Food Delivery Platforms → Better recommendations and ranking systems  
- Customers → Smarter restaurant choices  
- Investors → Identify high-performing restaurant segments  

---

## Dataset Overview

The dataset contains restaurant-related attributes such as:

- Restaurant Name  
- Location  
- Restaurant Type  
- Cuisines  
- Online Ordering Availability  
- Table Booking Option  
- Customer Votes  
- Approximate Cost for Two People  
- Restaurant Rating  

Note: The dataset is not included in this repository due to GitHub file size limitations (91MB). Please download it from the original source and place it inside the `dataset/` folder before running the notebook.

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Machine Learning Pipeline

1. Data Cleaning and Handling Missing Values  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Data Preprocessing (Encoding and Scaling)  
5. Model Training  
6. Model Evaluation  
7. Model Comparison  

---

## Machine Learning Models

The following regression models were trained and evaluated:

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

---

## Model Performance

| Model | R² Score |
|------|----------|
| Linear Regression | 27.25% |
| Decision Tree Regressor | 87.17% |
| Random Forest Regressor | 91.25% |

### Best Model:
Random Forest Regressor achieved the highest performance, capturing complex non-linear relationships effectively.

---

## Key Insights

- Online ordering is significantly more common than table booking.  
- Certain locations contain a high concentration of restaurants.  
- Quick Bites is the most dominant restaurant type.  
- North Indian cuisine is the most frequently offered cuisine.  
- Customer votes show a strong relationship with restaurant ratings.  
- Ensemble models perform better than simple linear models.  

---

## Business Recommendations

- Improve online ordering systems to increase customer engagement  
- Encourage customer reviews and feedback collection  
- Focus expansion strategies on high-density restaurant zones  
- Use predictive models for rating-based ranking systems  
- Optimize restaurant offerings based on cuisine demand trends  

---

## Future Improvements

- Hyperparameter tuning for model optimization  
- Advanced models: XGBoost, LightGBM, CatBoost  
- Deployment using Streamlit or Flask  
- API integration for real-time predictions  
- Feature importance analysis for better interpretability  

---

## Project Structure

```text
zomato-rating-prediction/
│── zomato_rating_prediction.ipynb
│── README.md
│── requirements.txt
