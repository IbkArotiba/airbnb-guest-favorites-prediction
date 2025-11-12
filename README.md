# Airbnb Guest Favorites Prediction

Comparative analysis of machine learning models (Logistic Regression vs Random Forest) 
for predicting guest favorite status in Airbnb listings.

## Project Overview
- **Dataset:** 25,269 Airbnb listings across 5 cities
- **Goal:** Predict which listings become "Guest Favorites"
- **Challenge:** Handling imbalanced classification (75-25 split)

## Key Findings
- Random Forest outperformed Logistic Regression despite lower overall accuracy
- Successfully identified 458/1,564 guest favorites (29% recall)
- Demonstrated that accuracy can be misleading with imbalanced data

## Technologies Used
- Python 3.13
- pandas, NumPy
- scikit-learn
- matplotlib, seaborn

## Results
| Model | Accuracy | Recall (Favorites) |
|-------|----------|-------------------|
| Logistic Regression | 75% | 0% |
| Random Forest | 71% | 29% |

## Skills Demonstrated
- Data cleaning and preprocessing
- Exploratory data analysis
- Feature engineering (city encoding)
- Model training and evaluation
- Handling imbalanced datasets
- Model comparison and selection

## Dataset
Data sourced from Kaggle Airbnb dataset 
```
https://www.kaggle.com/datasets/willianoliveiragibin/airbnb-site-hotel

