---
layout: publication
title: 'Large Language Models Are Qualified Benchmark Builders: Rebuilding Pre-training Datasets For Advancing Code Intelligence Tasks'
authors: Kang Yang, Xinjun Mao, Shangwen Wang, Yanlin Wang, Tanghaoran Zhang, Bo Lin, Yihao Qin, Zhang Zhang, Yao Lu, Kamal Al-sabahi
conference: "Arxiv"
year: 2025
bibkey: yang2025large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.19444'}
tags: ['RAG', 'Applications', 'Training Techniques', 'Reinforcement Learning', 'Pre-Training']
---
Pre-trained code models rely heavily on high-quality pre-training data,
particularly human-written reference comments that bridge code and natural
language. However, these comments often become outdated as software evolves,
degrading model performance. Large language models (LLMs) excel at generating
high-quality code comments. We investigate whether replacing human-written
comments with LLM-generated ones improves pre-training datasets. Since standard
metrics cannot assess reference comment quality, we propose two novel
reference-free evaluation tasks: code-comment inconsistency detection and
semantic code search. Results show that LLM-generated comments are more
semantically consistent with code than human-written ones, as confirmed by
manual evaluation. Leveraging this finding, we rebuild the CodeSearchNet
dataset with LLM-generated comments and re-pre-train CodeT5. Evaluations
demonstrate that models trained on LLM-enhanced data outperform those using
original human comments in code summarization, generation, and translation
tasks. This work validates rebuilding pre-training datasets with LLMs to
advance code intelligence, challenging the traditional reliance on human
reference comments.
