---
layout: publication
title: 'Structlm: Towards Building Generalist Models For Structured Knowledge Grounding'
authors: Alex Zhuang, Ge Zhang, Tianyu Zheng, Xinrun Du, Junjie Wang, Weiming Ren, Stephen W. Huang, Jie Fu, Xiang Yue, Wenhu Chen
conference: "Arxiv"
year: 2024
bibkey: zhuang2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16671"}
tags: ['RAG', 'GPT', 'Model Architecture']
---
Structured data sources, such as tables, graphs, and databases, are
ubiquitous knowledge sources. Despite the demonstrated capabilities of large
language models (LLMs) on plain text, their proficiency in interpreting and
utilizing structured data remains limited. Our investigation reveals a notable
deficiency in LLMs' ability to process structured data, e.g., ChatGPT lags
behind state-of-the-art (SoTA) model by an average of 35%. To augment the
Structured Knowledge Grounding (SKG) capabilities in LLMs, we have developed a
comprehensive instruction tuning dataset comprising 1.1 million examples.
Utilizing this dataset, we train a series of models, referred to as StructLM,
based on the Mistral and the CodeLlama model family, ranging from 7B to 34B
parameters. Our StructLM series surpasses task-specific models on 16 out of 18
evaluated datasets and establishes new SoTA performance on 8 SKG tasks.
Furthermore, StructLM demonstrates strong generalization across 6 novel
held-out SKG tasks, outperforming TableLlama by an average of 35% and Flan-UL2
20B by an average of 10%. Contrary to expectations, we observe that scaling
model size offers marginal benefits, with StructLM-34B showing only slight
improvements over StructLM-7B. This suggests that structured knowledge
grounding is still a challenging task and requires more innovative design to
push to a new level.
