---
layout: publication
title: Diff-explainer Differentiable Convex Optimization For Explainable Multi-hop Inference
authors: Thayaparan Mokanarangan, Valentino Marco, Ferreira Deborah, Rozanova Julia, Freitas André
conference: "Arxiv"
year: 2021
bibkey: thayaparan2021diff
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.03417"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
This paper presents Diff-Explainer the first hybrid framework for explainable multi-hop inference that integrates explicit constraints with neural architectures through differentiable convex optimization. Specifically Diff-Explainer allows for the fine-tuning of neural representations within a constrained optimization framework to answer and explain multi-hop questions in natural language. To demonstrate the efficacy of the hybrid framework we combine existing ILP-based solvers for multi-hop Question Answering (QA) with Transformer-based representations. An extensive empirical evaluation on scientific and commonsense QA tasks demonstrates that the integration of explicit constraints in an end-to-end differentiable framework can significantly improve the performance of non-differentiable ILP solvers (8.9137; - 13.337;). Moreover additional analysis reveals that Diff-Explainer is able to achieve strong performance when compared to standalone Transformers and previous multi-hop approaches while still providing structured explanations in support of its predictions.
