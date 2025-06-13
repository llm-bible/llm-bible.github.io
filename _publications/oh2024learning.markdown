---
layout: publication
title: 'Learning To Verify Summary Facts With Fine-grained LLM Feedback'
authors: Jihwan Oh, Jeonghwan Choi, Nicole Hee-yeon Kim, Taewon Yun, Hwanjun Song
conference: "Arxiv"
year: 2024
bibkey: oh2024learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.10689'}
  - {name: "Code", url: 'https://github.com/DISL-Lab/FineSumFact'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Pretraining Methods']
---
Training automatic summary fact verifiers often faces the challenge of a lack
of human-labeled data. In this paper, we explore alternative way of leveraging
Large Language Model (LLM) generated feedback to address the inherent
limitation of using human-labeled data. We introduce FineSumFact, a large-scale
dataset containing fine-grained factual feedback on summaries. We employ 10
distinct LLMs for diverse summary generation and Llama-3-70B-Instruct for
feedback. We utilize this dataset to fine-tune the lightweight open-source
model Llama-3-8B-Instruct, optimizing resource efficiency while maintaining
high performance. Our experimental results reveal that the model trained on
extensive LLM-generated datasets surpasses that trained on smaller
human-annotated datasets when evaluated using human-generated test sets.
Fine-tuning fact verification models with LLM feedback can be more effective
and cost-efficient than using human feedback. The dataset is available at
https://github.com/DISL-Lab/FineSumFact.
