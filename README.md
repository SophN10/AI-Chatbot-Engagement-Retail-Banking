# Customer Perceptions of AI-Powered Chatbots and Their Influence on Engagement in Retail Banking

## Overview
This repository contains my MSc dissertation project analysing how customers perceive AI-powered chatbots in retail banking and how those perceptions influence customer engagement.

The project adopts a **triangulated quantitative approach**, combining survey-based perceptual data with large-scale behavioural sentiment data, supported by applied machine learning and NLP techniques. The aim is to generate practical, evidence-based insights to inform responsible AI adoption in financial services.

---

## Business Context
Retail banks increasingly deploy AI chatbots to improve customer service efficiency and accessibility. However, customer engagement and trust in these systems remain inconsistent.

This project explores:
- Which customer perceptions most strongly influence engagement with AI chatbots
- Whether functional performance or relational attributes (e.g. empathy, personalisation) matter more
- How real-world behavioural sentiment aligns with self-reported customer perceptions

The findings support **customer-centric and trustworthy AI deployment**, rather than AI adoption for novelty alone.

---

## Data
### 1. Survey Data (Perceptual Evidence)
- Online customer survey measuring:
  - Engagement
  - Trust
  - Satisfaction
  - Empathy
  - Personalisation
  - Functional service quality attributes
- Likert-scale constructs with composite scoring
- Used for statistical and regression analysis

### 2. Behavioural Text Data
- ~19,000 real-world retail banking customer reviews
- Public dataset sourced from Hugging Face
- Used for sentiment analysis to capture naturally occurring customer behaviour and opinions

> ⚠️ Raw survey data is not included due to confidentiality and ethical considerations.

---

## How to Run
The notebooks in this repository are fully executed and include all outputs and visualisations.

To explore the analysis:
1. Clone the repository
2. Open the `.ipynb` files in Jupyter Notebook or VS Code
3. Review the code, outputs, and figures directly within the notebooks

No re-execution is required to view results.

---
   
## Methodology
This project uses a **triangulated quantitative methodology**, combining perceptual and behavioural evidence to strengthen validity.

Key methods include:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Correlation analysis and multiple linear regression
- NLP-based sentiment analysis
- Machine learning classification models:
  - Logistic Regression (interpretability baseline)
  - XGBoost
  - BERT (benchmark transformer model)
- Model evaluation using appropriate performance metrics
- Emphasis on explainability and responsible AI use

---

## Key Findings
- **Trust** emerged as the strongest driver of customer engagement with AI-powered chatbots
- Functional reliability is a baseline requirement rather than a competitive differentiator
- Negative sentiment in real-world reviews is driven primarily by:
  - Inaccurate responses
  - Poor escalation to human agents
  - Reliability and consistency issues
- Relational attributes such as empathy and personalisation play a secondary role compared to trust and functional performance
![Logistic Regression Feature Importance](Sentiment%20Plot%20.png)

Findings were consistent across both survey and behavioural datasets, reinforcing insight robustness.

---

## Practical Implications
- AI chatbots should prioritise:
  - Accuracy
  - Transparency
  - Trustworthiness
  - Clear escalation to human support
- Over-reliance on conversational features cannot compensate for poor functional performance
- Engagement with AI systems is driven by confidence and reliability, not novelty

---

## Repository Contents
- Analysis scripts and notebooks
- Key visualisations and outputs
- Dissertation presentation (PDF)
- Selected figures supporting insights

📄 **Full Dissertation (PDF):**  
[View Dissertation](AI%20Chatbot%20Engagement%20Dissertation.pdf)

📄 **Dissertation Summary (PDF):**  
[View Summary](AI%20Chatbot%20Engagement%20Summary.pdf)

---

## Tools & Technologies
- Python / Excel
- NLP and machine learning libraries
- Statistical analysis
- Data visualisation
- Explainability-focused modelling

---

## Author
**Sophia Nelson**  
MSc Business Analytics  
Interests: Applied AI, NLP, Explainable AI, Customer Analytics, AI in Financial Services
