---
layout: publication
title: 'Policy Induction: Predicting Startup Success Via Explainable Memory-augmented In-context Learning'
authors: Xianling Mu, Joseph Ternasky, Fuat Alican, Yigit Ihlamur
conference: "Arxiv"
year: 2025
bibkey: mu2025policy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21427"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Early-stage startup investment is a high-risk endeavor characterized by scarce data and uncertain outcomes. Traditional machine learning approaches often require large, labeled datasets and extensive fine-tuning, yet remain opaque and difficult for domain experts to interpret or improve. In this paper, we propose a transparent and data-efficient investment decision framework powered by memory-augmented large language models (LLMs) using in-context learning (ICL). Central to our method is a natural language policy embedded directly into the LLM prompt, enabling the model to apply explicit reasoning patterns and allowing human experts to easily interpret, audit, and iteratively refine the logic. We introduce a lightweight training process that combines few-shot learning with an in-context learning loop, enabling the LLM to update its decision policy iteratively based on structured feedback. With only minimal supervision and no gradient-based optimization, our system predicts startup success far more accurately than existing benchmarks. It is over 20x more precise than random chance, which succeeds 1.9% of the time. It is also 7.1x more precise than the typical 5.6% success rate of top-tier venture capital (VC) firms.
