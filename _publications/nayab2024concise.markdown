---
layout: publication
title: 'Concise Thoughts: Impact Of Output Length On LLM Reasoning And Cost'
authors: Nayab Sania, Rossolini Giulio, Buttazzo Giorgio, Manes Nicolamaria, Giacomelli Fabrizio
conference: "Arxiv"
year: 2024
bibkey: nayab2024concise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.19825"}
tags: ['Attention Mechanism', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
"Today's large language models (LLMs) can solve challenging question-answering tasks, and prompt engineering techniques, such as chain-of-thought (CoT), have gained attention for enhancing the explanation and correctness of outputs. Nevertheless, models require significant time to generate answers augmented with lengthy reasoning details. To address this issue, this paper analyzes the impact of output lengths on LLM inference pipelines and proposes novel metrics to evaluate them in terms of \textit\{correct conciseness\}. It also examines the impact of controlling output length through a refined prompt engineering strategy, Constrained-CoT (CCoT), which encourages the model to limit output length. Experiments on pre-trained LLMs demonstrated the benefit of the proposed metrics and the effectiveness of CCoT across different models. For instance, constraining the reasoning of LLaMA2-70b to 100 words improves the accuracy from 36.01\&#37; (CoT) to 41.07\&#37; (CCoT) on the GSM8K dataset, while reducing the average output length by 28 words."
