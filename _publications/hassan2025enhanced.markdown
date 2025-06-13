---
layout: publication
title: 'Enhanced Urdu Intent Detection With Large Language Models And Prototype-informed Predictive Pipelines'
authors: Faiza Hassan, Summra Saleem, Kashif Javed, Muhammad Nabeel Asim, Abdur Rehman, Andreas Dengel
conference: "Arxiv"
year: 2025
bibkey: hassan2025enhanced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.07857"}
tags: ['Training Techniques', 'Model Architecture', 'Few-Shot', 'Tools', 'RAG', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Multifarious intent detection predictors are developed for different languages, including English, Chinese and French, however, the field remains underdeveloped for Urdu, the 10th most spoken language. In the realm of well-known languages, intent detection predictors utilize the strategy of few-shot learning and prediction of unseen classes based on the model training on seen classes. However, Urdu language lacks few-shot strategy based intent detection predictors and traditional predictors are focused on prediction of the same classes which models have seen in the train set. To empower Urdu language specific intent detection, this introduces a unique contrastive learning approach that leverages unlabeled Urdu data to re-train pre-trained language models. This re-training empowers LLMs representation learning for the downstream intent detection task. Finally, it reaps the combined potential of pre-trained LLMs and the prototype-informed attention mechanism to create a comprehensive end-to-end LLMPIA intent detection pipeline. Under the paradigm of proposed predictive pipeline, it explores the potential of 6 distinct language models and 13 distinct similarity computation methods. The proposed framework is evaluated on 2 public benchmark datasets, namely ATIS encompassing 5836 samples and Web Queries having 8519 samples. Across ATIS dataset under 4-way 1 shot and 4-way 5 shot experimental settings LLMPIA achieved 83.28% and 98.25% F1-Score and on Web Queries dataset produced 76.23% and 84.42% F1-Score, respectively. In an additional case study on the Web Queries dataset under same classes train and test set settings, LLMPIA outperformed state-of-the-art predictor by 53.55% F1-Score.
