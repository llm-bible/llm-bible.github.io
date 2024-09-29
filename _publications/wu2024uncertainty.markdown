---
layout: publication
title: 'Uncertainty Estimation Of Large Language Models In Medical Question Answering'
authors: Wu Jiaxin, Yu Yizhou, Zhou Hong-yu
conference: "Arxiv"
year: 2024
bibkey: wu2024uncertainty
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08662"}
tags: ['Applications', 'Interpretability And Explainability', 'Reinforcement Learning']
---
Large Language Models (LLMs) show promise for natural language generation in healthcare but risk hallucinating factually incorrect information. Deploying LLMs for medical question answering necessitates reliable uncertainty estimation (UE) methods to detect hallucinations. In this work we benchmark popular UE methods with different model sizes on medical question-answering datasets. Our results show that current approaches generally perform poorly in this domain highlighting the challenge of UE for medical applications. We also observe that larger models tend to yield better results suggesting a correlation between model size and the reliability of UE. To address these challenges we propose Two-phase Verification a probability-free Uncertainty Estimation approach. First an LLM generates a step-by-step explanation alongside its initial answer followed by formulating verification questions to check the factual claims in the explanation. The model then answers these questions twice first independently and then referencing the explanation. Inconsistencies between the two sets of answers measure the uncertainty in the original response. We evaluate our approach on three biomedical question-answering datasets using Llama 2 Chat models and compare it against the benchmarked baseline methods. The results show that our Two-phase Verification method achieves the best overall accuracy and stability across various datasets and model sizes and its performance scales as the model size increases.
