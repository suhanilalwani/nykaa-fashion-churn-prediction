# Nykaa Fashion Customer Churn Prediction
Customer churn prediction model for Nykaa Fashion with RFM segmentation and 3-tier retention campaign framework

## Business Problem
Which Nykaa Fashion customers are most at risk of churning —
and what should the CRM and retention marketing team do
differently for each risk segment to bring them back?

## Key Findings
- Overall churn rate: 16.8% across 5630 customers
- Lost Customer segment churns at 8.5% vs Champions at 15%
- Top churn predictor: tenure — customers with high
  tenure scores are more likely to leave
- 425 customers flagged as High Risk requiring immediate action

## Model Performance
| Model | Accuracy | Recall (Churned) |
|---|---|---|
| Logistic Regression | 87.1% | 43% |
| Decision Tree | 89.3% | 51% |

Selected model: Decision Tree (max_depth=5) — higher recall
on churned class means fewer at-risk customers are missed.

## Retention Campaign Framework
- High Risk (≥70%): "We Miss You" — 20% discount email →
  WhatsApp → personal call escalation
- Medium Risk (40-70%): "Stay With Us" — early access +
  loyalty points
- Low Risk (<40%): "Champion Program" — VIP invite +
  referral bonus

## Tools
Python (pandas, scikit-learn, matplotlib, seaborn),
Jupyter Notebook, Power BI Desktop

## Data Source
E-Commerce Customer Churn Dataset — Kaggle
