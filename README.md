# Netflix TV Show Success Prediction

## Project Overview

This project focuses on predicting whether a Netflix TV show will be successful using machine learning techniques. 

The objective is to analyze engagement metrics and genre information to understand what factors influence content performance. By building classification models, we aim to identify patterns that contribute to a show's success.

---

## Dataset Description

The dataset contains over 16,000 Netflix TV shows.

Features used in modeling:
- Vote count (audience engagement)
- Popularity score
- Release year
- Main genre (extracted and encoded)

Target variable:
- Success (1 if rating ≥ 7, otherwise 0)

Only TV shows were considered for this analysis.

---

## Methodology

1. Data cleaning and preprocessing  
2. Feature engineering (genre extraction and encoding)  
3. Exploratory data analysis (EDA)  
4. Model building:
   - Logistic Regression
   - Random Forest  
5. Model evaluation using Accuracy, Precision, Recall, and F1-score  

---

## Model Performance

| Model                | Accuracy |
|----------------------|----------|
| Logistic Regression  | ~64%     |
| Random Forest        | ~69%     |

The Random Forest model achieved better overall performance and provided improved class balance compared to Logistic Regression.

---

## Key Insights

- Audience engagement (vote count) is the strongest predictor of success.
- Certain genres consistently show higher success rates.
- Success rates have generally improved over time.
- Popularity alone does not strongly determine content quality.

---

## How to Run the Project

1. Clone this repository  
2. Install required libraries:
   pip install pandas numpy scikit-learn matplotlib seaborn  
3. Open the Jupyter Notebook  
4. Run all cells  

---

## Future Improvements

- Hyperparameter tuning  
- Cross-validation  
- Advanced ensemble models  
- Model deployment using Streamlit  

