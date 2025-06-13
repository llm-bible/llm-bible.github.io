---
layout: publication
title: 'Agentic Predictor: Performance Prediction For Agentic Workflows Via Multi-view Encoding'
authors: Patara Trirat, Wonyong Jeong, Sung Ju Hwang
conference: "Arxiv"
year: 2025
bibkey: trirat2025agentic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19764"}
tags: ['Agentic', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) have demonstrated remarkable capabilities across diverse tasks, but optimizing LLM-based agentic systems remains challenging due to the vast search space of agent configurations, prompting strategies, and communication patterns. Existing approaches often rely on heuristic-based tuning or exhaustive evaluation, which can be computationally expensive and suboptimal. This paper proposes Agentic Predictor, a lightweight predictor for efficient agentic workflow evaluation. Agentic Predictor is equipped with a multi-view workflow encoding technique that leverages multi-view representation learning of agentic systems by incorporating code architecture, textual prompts, and interaction graph features. To achieve high predictive accuracy while significantly reducing the number of required workflow evaluations for training a predictor, Agentic Predictor employs cross-domain unsupervised pretraining. By learning to approximate task success rates, Agentic Predictor enables fast and accurate selection of optimal agentic workflow configurations for a given task, significantly reducing the need for expensive trial-and-error evaluations. Experiments on a carefully curated benchmark spanning three domains show that our predictor outperforms state-of-the-art methods in both predictive accuracy and workflow utility, highlighting the potential of performance predictors in streamlining the design of LLM-based agentic workflows.
