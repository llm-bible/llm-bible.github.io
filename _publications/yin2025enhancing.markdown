---
layout: publication
title: 'Enhancing Generalization In Chain Of Thought Reasoning For Smaller Models'
authors: Maxwell J. Yin, Dingyi Jiang, Yongbing Chen, Boyu Wang, Charles Ling
conference: "Arxiv"
year: 2025
bibkey: yin2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.09804"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Distillation', 'Pretraining Methods', 'Interpretability', 'Fine-Tuning', 'Interpretability and Explainability', 'Prompting', 'Applications']
---
Chain-of-Thought (CoT) reasoning in smaller language models is a challenging
natural language process problem yet highly desirable in many real-life
applications. Existing CoT knowledge distillation methods often suffer from
overly conservative memorization in smaller LLMs, leading to low generalization
confidence. As fully preserving the CoT ability of teacher model is impossible,
we hypothesize that adversarial CoT fine-tuning is crucial for developing
smaller LLM with robust CoT generalization. To this end, we propose
\textit\{PRompt-Assisted Domain-Adversarial fine-tuning\} (PRADA), a principled
fine-tuning framework that integrates diverse CoT domains. Specifically, PRADA
pioneers two CoT improvements in smaller LLM: (1) Recovering the
domain-invariant feature insight which typically lost during distillation with
domain adversarial fine-tuning; (2) Enhancing the domain adaptability of CoT
prompt engineering by employing domain-adversarial approaches. We theoretically
demonstrate the effectiveness of our approach and empirically show that it
significantly outperforms the state of the arts in a wide range of tasks.
Moreover, our empirical findings reveal that the smaller LLM, when leveraging
PRADA, aligns closely with domain knowledge, thereby improving the
explainability of our approach.
