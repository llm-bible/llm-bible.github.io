---
layout: publication
title: 'Evaluating The Effectiveness Of XAI Techniques For Encoder-based Language Models'
authors: Melkamu Abay Mersha, Mesay Gemeda Yigezu, Jugal Kalita
conference: "310(2025)113042"
year: 2025
bibkey: mersha2025evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.15374'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'Security', 'Model Architecture', 'Tools', 'BERT', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability']
---
The black-box nature of large language models (LLMs) necessitates the
development of eXplainable AI (XAI) techniques for transparency and
trustworthiness. However, evaluating these techniques remains a challenge. This
study presents a general evaluation framework using four key metrics:
Human-reasoning Agreement (HA), Robustness, Consistency, and Contrastivity. We
assess the effectiveness of six explainability techniques from five different
XAI categories model simplification (LIME), perturbation-based methods (SHAP),
gradient-based approaches (InputXGradient, Grad-CAM), Layer-wise Relevance
Propagation (LRP), and attention mechanisms-based explainability methods
(Attention Mechanism Visualization, AMV) across five encoder-based language
models: TinyBERT, BERTbase, BERTlarge, XLM-R large, and DeBERTa-xlarge, using
the IMDB Movie Reviews and Tweet Sentiment Extraction (TSE) datasets. Our
findings show that the model simplification-based XAI method (LIME)
consistently outperforms across multiple metrics and models, significantly
excelling in HA with a score of 0.9685 on DeBERTa-xlarge, robustness, and
consistency as the complexity of large language models increases. AMV
demonstrates the best Robustness, with scores as low as 0.0020. It also excels
in Consistency, achieving near-perfect scores of 0.9999 across all models.
Regarding Contrastivity, LRP performs the best, particularly on more complex
models, with scores up to 0.9371.
