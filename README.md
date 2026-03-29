# Zomato Restaurant Data Analysis & Rating Prediction

## Author
Shrinithi  
MSc Data Science, CIT  

---

## Project Overview
This project focuses on cleaning and analyzing a real-world Zomato restaurant dataset.  
The dataset contains messy and inconsistent data such as missing values, text-based fields, and mixed formats.

The goal of this project is to:
- Perform data cleaning and preprocessing  
- Extract meaningful insights through visualization  
- Build machine learning models to predict restaurant ratings  

---

## Why This Dataset?
The Zomato dataset was chosen because it closely represents real-world data.  
It contains:
- Missing values  
- Text-based columns (cuisines, location)  
- Mixed formats (ratings like "4.2/5", cost with symbols)  

This makes it ideal for demonstrating:
- Data cleaning techniques  
- Feature engineering  
- Practical data analysis

## 📊 Dataset

The dataset used in this project is not included in the repository due to its large size.  

You can download it from Kaggle:  
https://www.kaggle.com/datasets/rajeshrampure/zomato-dataset  

The dataset contains information about restaurants such as:
- Name and location  
- Cuisines offered  
- Ratings and votes  
- Approximate cost for two people  

It includes real-world inconsistencies such as missing values, text-based fields, and mixed formats, making it suitable for data cleaning and preprocessing tasks.

---

## Data Cleaning
The dataset was cleaned by:
- Handling missing values  
- Converting ratings and cost into numeric format  
- Standardizing text columns  
- Removing duplicates and inconsistencies  

---

## Feature Engineering
New features were created to improve analysis:
- **cost_per_person** → derived from cost for two  
- **cuisine_count** → number of cuisines offered  

---

## Exploratory Data Analysis
Key observations:
- Most restaurants have ratings between 3.5 and 4.2  
- Higher vote counts lead to more stable ratings  
- Cost does not strongly influence ratings  

---

## Machine Learning
Two models were used:
- Random Forest Regressor  
- Linear Regression  

### Model Comparison

| Model | MAE | RMSE | R² Score |
|------|------|------|---------|
| Random Forest | 0.125 | 0.221 | 0.745 |
| Linear Regression | 0.292 | 0.378 | 0.254 |

**Best Model: Random Forest**

---

## Conclusion
Random Forest performed better as it captured non-linear relationships in the data.  
The project shows how proper data cleaning and simple modeling can provide useful insights from real-world datasets.

---

## Limitations
- Ratings are subjective and may vary  
- Dataset is limited to specific locations  
- Some missing data may affect accuracy  

---

## Future Improvements
- Include more features like location encoding  
- Use advanced models for better accuracy  
- Expand dataset to include more regions  

---
