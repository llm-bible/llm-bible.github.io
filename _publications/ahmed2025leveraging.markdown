---
layout: publication
title: 'Leveraging Large Language Models To Enhance Machine Learning Interpretability And Predictive Performance: A Case Study On Emergency Department Returns For Mental Health Patients'
authors: Abdulaziz Ahmed, Mohammad Saleem, Mohammed Alzeen, Badari Birur, Rachel E Fargason, Bradley G Burk, Hannah Rose Harkins, Ahmed Alhassan, Mohammed Ali Al-garadi
conference: "Arxiv"
year: 2025
bibkey: ahmed2025leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.00025"}
tags: ['Interpretability', 'RAG', 'Tools', 'Interpretability and Explainability']
---
Importance: Emergency department (ED) returns for mental health conditions
pose a major healthcare burden, with 24-27% of patients returning within 30
days. Traditional machine learning models for predicting these returns often
lack interpretability for clinical use.
  Objective: To assess whether integrating large language models (LLMs) with
machine learning improves predictive accuracy and clinical interpretability of
ED mental health return risk models.
  Methods: This retrospective cohort study analyzed 42,464 ED visits for 27,904
unique mental health patients at an academic medical center in the Deep South
from January 2018 to December 2022.
  Main Outcomes and Measures: Two primary outcomes were evaluated: (1) 30-day
ED return prediction accuracy and (2) model interpretability using a novel
LLM-enhanced framework integrating SHAP (SHapley Additive exPlanations) values
with clinical knowledge.
  Results: For chief complaint classification, LLaMA 3 (8B) with 10-shot
learning outperformed traditional models (accuracy: 0.882, F1-score: 0.86). In
SDoH classification, LLM-based models achieved 0.95 accuracy and 0.96 F1-score,
with Alcohol, Tobacco, and Substance Abuse performing best (F1: 0.96-0.89),
while Exercise and Home Environment showed lower performance (F1: 0.70-0.67).
The LLM-based interpretability framework achieved 99% accuracy in translating
model predictions into clinically relevant explanations. LLM-extracted features
improved XGBoost AUC from 0.74 to 0.76 and AUC-PR from 0.58 to 0.61.
  Conclusions and Relevance: Integrating LLMs with machine learning models
yielded modest but consistent accuracy gains while significantly enhancing
interpretability through automated, clinically relevant explanations. This
approach provides a framework for translating predictive analytics into
actionable clinical insights.
