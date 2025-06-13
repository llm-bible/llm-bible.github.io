---
layout: publication
title: 'Tabula: Harnessing Language Models For Tabular Data Synthesis'
authors: Zilong Zhao, Robert Birke, Lydia Chen
conference: "Arxiv"
year: 2023
bibkey: zhao2023harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.12746"}
  - {name: "Code", url: "https://github.com/zhao-zilong/Tabula"}
tags: ['Security', 'Training Techniques', 'RAG', 'Has Code', 'Applications']
---
Tabular data synthesis is crucial for addressing privacy and security
concerns in industries reliant on tabular data. While recent advancements adopt
large language models (LLMs) for realistic tabular data generation, their long
training times and limited reusability hinder practical applications. In this
paper, we propose Tabula, a tabular data synthesizer that leverages the
structure of LLM. Unlike state-of-the-art (SOTA) LLM-based tabular data
synthesizers that rely on pre-trained LLMs, Tabula discards the pre-trained
weights originally designed for natural language tasks, focusing instead on a
tailored approach for tabular data. In addition, Tabula introduces a token
sequence compression strategy that significantly reduces training time while
maintaining data quality, alongside a novel token padding method that improves
sequence alignment across training batches. Experiments on six datasets show
that Tabula achieves superior synthetic data utility compared to current SOTA
methods. Additionally, the results demonstrate that Tabula model trained on
tabular datasets serves effectively as a foundational model for synthesizing
new tabular datasets. Furthermore, the proposed padding method outperforms the
conventional left and right padding strategies. Finally, the results highlight
that Tabula averagely reduces training time per epoch by 46.2% compared to
state-of-the-art LLM approaches while achieving higher data utility. Our code
is available at https://github.com/zhao-zilong/Tabula
