---
layout: publication
title: Should We Fine-Tune or RAG Evaluating Different Techniques to Adapt alms for Dialogue
authors: Alghisi Simone, Rizzoli Massimo, Roccabruna Gabriel, Mousavi Seyed Mahed, Riccardi Giuseppe
conference: "Arxiv"
year: 2024
bibkey: alghisi2024should
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06399"}
tags: ['Applications', 'Fine Tuning', 'In Context Learning', 'Interpretability And Explainability', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
We study the limitations of Large Language Models (LLMs) for the task of response generation in human-machine dialogue. Several techniques have been proposed in the literature for different dialogue types (e.g. Open-Domain). However the evaluations of these techniques have been limited in terms of base LLMs dialogue types and evaluation metrics. In this work we extensively analyze different LLM adaptation techniques when applied to different dialogue types. We have selected two base LLMs Llama-2 and Mistral and four dialogue types Open-Domain Knowledge-Grounded Task-Oriented and Question Answering. We evaluate the performance of in-context learning and fine-tuning techniques across datasets selected for each dialogue type. We assess the impact of incorporating external knowledge to ground the generation in both scenarios of Retrieval-Augmented Generation (RAG) and gold knowledge. We adopt consistent evaluation and explainability criteria for automatic metrics and human evaluation protocols. Our analysis shows that there is no universal best-technique for adapting large language models as the efficacy of each technique depends on both the base LLM and the specific type of dialogue. Last but not least the assessment of the best adaptation technique should include human evaluation to avoid false expectations and outcomes derived from automatic metrics.
