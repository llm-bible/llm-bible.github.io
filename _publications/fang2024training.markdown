---
layout: publication
title: 'KARPA: A Training-free Method Of Adapting Knowledge Graph As References For Large Language Model''s Reasoning Path Aggregation'
authors: Siyuan Fang, Kaijing Ma, Tianyu Zheng, Xinrun Du, Ningxuan Lu, Ge Zhang, Qingkun Tang
conference: "Arxiv"
year: 2024
bibkey: fang2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20995"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training', 'Applications']
---
Large language models (LLMs) demonstrate exceptional performance across a
variety of tasks, yet they are often affected by hallucinations and the
timeliness of knowledge. Leveraging knowledge graphs (KGs) as external
knowledge sources has emerged as a viable solution, but existing methods for
LLM-based knowledge graph question answering (KGQA) are often limited by
step-by-step decision-making on KGs, restricting the global planning and
reasoning capabilities of LLMs, or they require fine-tuning or pre-training on
specific KGs. To address these challenges, we propose Knowledge graph Assisted
Reasoning Path Aggregation (KARPA), a novel framework that harnesses the global
planning abilities of LLMs for efficient and accurate KG reasoning. KARPA
operates in three steps: pre-planning relation paths using the LLM's global
planning capabilities, matching semantically relevant paths via an embedding
model, and reasoning over these paths to generate answers. Unlike existing KGQA
methods, KARPA avoids stepwise traversal, requires no additional training, and
is adaptable to various LLM architectures. Extensive experimental results show
that KARPA achieves state-of-the-art performance in KGQA tasks, delivering both
high efficiency and accuracy. Our code will be available on Github.
