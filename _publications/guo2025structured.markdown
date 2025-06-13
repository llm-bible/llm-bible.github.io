---
layout: publication
title: 'Structured Outputs Enable General-purpose Llms To Be Medical Experts'
authors: Guangfu Guo, Kai Zhang, Bryan Hoo, Yujun Cai, Xiaoqian Lu, Nanyun Peng, Yiwei Wang
conference: "Arxiv"
year: 2025
bibkey: guo2025structured
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.03194'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Pretraining Methods']
---
Medical question-answering (QA) is a critical task for evaluating how
effectively large language models (LLMs) encode clinical knowledge and
assessing their potential applications in medicine. Despite showing promise on
multiple-choice tests, LLMs frequently struggle with open-ended medical
questions, producing responses with dangerous hallucinations or lacking
comprehensive coverage of critical aspects. Existing approaches attempt to
address these challenges through domain-specific fine-tuning, but this proves
resource-intensive and difficult to scale across models. To improve the
comprehensiveness and factuality of medical responses, we propose a novel
approach utilizing structured medical reasoning. Our method guides LLMs through
an seven-step cognitive process inspired by clinical diagnosis, enabling more
accurate and complete answers without additional training. Experiments on the
MedLFQA benchmark demonstrate that our approach achieves the highest Factuality
Score of 85.8, surpassing fine-tuned models. Notably, this improvement
transfers to smaller models, highlighting the method's efficiency and
scalability. Our code and datasets are available.
