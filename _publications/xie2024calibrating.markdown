---
layout: publication
title: 'Calibrating Reasoning In Language Models With Internal Consistency'
authors: Xie Zhihui, Guo Jizhou, Yu Tong, Li Shuai
conference: "Arxiv"
year: 2024
bibkey: xie2024calibrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18711"}
tags: ['Attention Mechanism', 'Model Architecture', 'Prompting', 'Uncategorized']
---
Large language models (LLMs) have demonstrated impressive capabilities in
various reasoning tasks, aided by techniques like chain-of-thought (CoT)
prompting that elicits verbalized reasoning. However, LLMs often generate text
with obvious mistakes and contradictions, raising doubts about their ability to
robustly process and utilize generated rationales. In this work, we investigate
CoT reasoning in LLMs through the lens of internal representations, focusing on
how these representations are influenced by generated rationales. Our
preliminary analysis reveals that while generated rationales improve answer
accuracy, inconsistencies emerge between the model's internal representations
in middle layers and those in final layers, potentially undermining the
reliability of their reasoning processes. To address this, we propose internal
consistency as a measure of the model's confidence by examining the agreement
of latent predictions decoded from intermediate layers. Extensive empirical
studies across different models and datasets demonstrate that internal
consistency effectively distinguishes between correct and incorrect reasoning
paths. Motivated by this, we propose a new approach to calibrate CoT reasoning
by up-weighting reasoning paths with high internal consistency, resulting in a
significant boost in reasoning performance. Further analysis uncovers distinct
patterns in attention and feed-forward modules across layers, providing
insights into the emergence of internal inconsistency. In summary, our results
demonstrate the potential of using internal representations for self-evaluation
of LLMs.
