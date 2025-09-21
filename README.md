# Customer-Retention-Analytics

This is a business analytics case study that applies logistic regression and machine learning to improve subscription retention.  

## Problem Statement
Ted & Poppy, a subscription-based pet food company, faced a **15.8% churn rate in Q4 2024**.  
The challenge was to identify key churn drivers and design data-driven retention strategies.  

Key questions addressed:  
- What are the main factors influencing customer churn?  
- Which customers are at higher risk of leaving?  
- How can predictive models support proactive retention campaigns?  
- What strategies can improve customer loyalty and lifetime value?  

## Tech Stack
- **Data & Storage:** Synthetic subscription dataset (200,000 customers, Oct–Dec 2024)  
- **Analysis/Modeling:** R (Logistic Regression, Random Forest, LightGBM)  
- **Visualization:** Poster PDF  
- **Validation:** 10-fold cross-validation, ROC analysis  

## Workflow
- **Data Preparation:** Cleaning, standardization, variable selection (28 features)  
- **Exploratory Analysis:** Churn distribution, customer purchase patterns, discount usage, support tickets  
- **Modeling:**  
  - Logistic Regression (best model, interpretable)  
  - Random Forest  
  - LightGBM  
- **Model Comparison:** Accuracy, Sensitivity, Specificity, ROC (up to 0.92)  
- **Interpretation:** Feature importance & churn factor insights  

## Key Insights
- Customers with **longer gaps since last purchase** are more likely to churn.  
- Those who **raised support tickets in the past 6 months** had higher churn risk.  
- **Browser type matters**: Chrome/Firefox users showed lower churn.  
- **Discounts help retention**: Customers without offers churned more.  

## Recommendations
- Strengthen customer support (faster response, chatbots, proactive outreach).  
- Optimize digital experience (browser compatibility, smoother UX).  
- Targeted promotions (loyalty rewards, referral discounts, renewal offers).  
- AI-driven product recommendations & replenishment reminders.  

## Code  
The full analysis is implemented in Quarto:
- [`Code/Retention-modeling.qmd`](Code/Retention-modeling.qmd)  
  Contains data preparation and model training, evaluation.
  
## Results Poster
See the full poster summarizing the findings:  
[View Poster (PDF)](Customer-Retention-Poster.pdf)

