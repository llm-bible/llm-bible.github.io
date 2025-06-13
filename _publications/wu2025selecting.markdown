---
layout: publication
title: 'Longattn: Selecting Long-context Training Data Via Token-level Attention'
authors: Longyun Wu, Dawei Zhu, Guangxiang Zhao, Zhuocheng Yu, Junfeng Ran, Xiangyu Wong, Lin Sun, Sujian Li
conference: "Arxiv"
year: 2025
bibkey: wu2025selecting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.16860'}
tags: ['Attention Mechanism', 'Arxiv', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Training Techniques']
---
With the development of large language models (LLMs), there has been an
increasing need for significant advancements in handling long contexts. To
enhance long-context capabilities, constructing high-quality training data with
long-range dependencies is crucial. Existing methods to select long-context
data often rely on sentence-level analysis, which can be greatly optimized in
both performance and efficiency. In this paper, we propose a novel token-level
framework, LongAttn, which leverages the self-attention mechanism of LLMs to
measure the long-range dependencies for the data. By calculating token-level
dependency strength and distribution uniformity of token scores, LongAttn
effectively quantifies long-range dependencies, enabling more accurate and
efficient data selection. We filter LongABC-32K from open-source long-context
datasets (ArXiv, Book, and Code). Through our comprehensive experiments,
LongAttn has demonstrated its excellent effectiveness, scalability, and
efficiency. To facilitate future research in long-context data, we released our
code and the high-quality long-context training data LongABC-32K.
