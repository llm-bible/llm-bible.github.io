---
layout: publication
title: 'Data-juicer: A One-stop Data Processing System For Large Language Models'
authors: Daoyuan Chen, Yilun Huang, Zhijian Ma, Hesen Chen, Xuchen Pan, Ce Ge, Dawei Gao, Yuexiang Xie, Zhaoyang Liu, Jinyang Gao, Yaliang Li, Bolin Ding, Jingren Zhou
conference: "Arxiv"
year: 2023
bibkey: chen2023data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.02033"}
tags: ['Fine-Tuning', 'Pre-Training', 'GPT', 'Tools', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
The immense evolution in Large Language Models (LLMs) has underscored the
importance of massive, heterogeneous, and high-quality data. A data recipe is a
mixture of data from different sources for training LLMs, which plays a vital
role in LLMs' performance. Existing open-source tools for LLM data processing
are mostly tailored for specific data recipes. To continuously uncover the
potential of LLMs, incorporate data from new sources, and improve LLMs'
performance, we build a new system named Data-Juicer, with which we can
efficiently generate diverse data recipes, explore different possibilities in
forming data mixtures, and evaluate their effects on model performance.
Different from traditional data-analytics pipelines, Data-Juicer faces some
unique challenges. Firstly, the possible data sources for forming data recipes
are truly heterogeneous and massive with various qualities. Secondly, it is
extremely expensive to precisely evaluate data recipes' impact on LLMs'
performance. Thirdly, the end users of Data-Juicer, model developers, need
sufficient flexibility to configure and evaluate different data recipes.
  Data-Juicer features a fine-grained abstraction of pipelines for constructing
data recipes, with over 50 built-in operators for easy composition and
extension. By incorporating visualization and auto-evaluation capabilities,
Data-Juicer enables a timely feedback loop for both LLM pre-training and
fine-tuning. Further, Data-Juicer is optimized and integrated with ecosystems
for LLM training, evaluation, and distributed computing. The data recipes
derived with Data-Juicer gain notable improvements on state-of-the-art LLMs, by
up to 7.45% increase in averaged score across 16 LLM benchmarks and 17.5%
higher win rate in pair-wise GPT-4 evaluations. Our system, data recipes, and
tutorials are released, calling for broader data-centric research on training
and understanding LLMs.
