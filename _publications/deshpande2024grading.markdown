---
layout: publication
title: 'GLIDER: Grading LLM Interactions And Decisions Using Explainable Ranking'
authors: Darshan Deshpande, Selvan Sunitha Ravi, Sky Ch-wang, Bartosz Mielczarek, Anand Kannappan, Rebecca Qian
conference: "Arxiv"
year: 2024
bibkey: deshpande2024grading
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14140"}
tags: ['GPT', 'Applications', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Interpretability']
---
The LLM-as-judge paradigm is increasingly being adopted for automated
evaluation of model outputs. While LLM judges have shown promise on constrained
evaluation tasks, closed source LLMs display critical shortcomings when
deployed in real world applications due to challenges of fine grained metrics
and explainability, while task specific evaluation models lack cross-domain
generalization. We introduce GLIDER, a powerful 3B evaluator LLM that can score
any text input and associated context on arbitrary user defined criteria.
GLIDER shows higher Pearson's correlation than GPT-4o on FLASK and greatly
outperforms prior evaluation models, achieving comparable performance to LLMs
17x its size. GLIDER supports fine-grained scoring, multilingual reasoning,
span highlighting and was trained on 685 domains and 183 criteria. Extensive
qualitative analysis shows that GLIDER scores are highly correlated with human
judgments, with 91.3% human agreement. We have open-sourced GLIDER to
facilitate future research.
