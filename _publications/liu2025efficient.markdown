---
layout: publication
title: 'Efficient Inference For Large Reasoning Models: A Survey'
authors: Yue Liu, Jiaying Wu, Yufei He, Hongcheng Gao, Hongyu Chen, Baolong Bi, Jiaheng Zhang, Zhiqi Huang, Bryan Hooi
conference: "Arxiv"
year: 2025
bibkey: liu2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23077"}
  - {name: "Code", url: "https://github.com/yueliu1999/Awesome-Efficient-Inference-for-LRMs"}
tags: ['Responsible AI', 'Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Survey Paper', 'Merging', 'Has Code', 'Interpretability and Explainability', 'Applications']
---
Large Reasoning Models (LRMs) significantly improve the reasoning ability of
Large Language Models (LLMs) by learning to reason, exhibiting promising
performance in complex task-solving. However, their deliberative reasoning
process leads to inefficiencies in token usage, memory consumption, and
inference time. Thus, this survey provides a review of efficient inference
methods designed specifically for LRMs, focusing on mitigating token
inefficiency while preserving the reasoning quality. First, we introduce a
taxonomy to group the recent methods into two main categories: (a) explicit
compact Chain-of-Thought (CoT), which reduces tokens while keeping the explicit
reasoning structure, and (b) implicit latent CoT, which encodes reasoning steps
within hidden representations instead of explicit tokens. Meanwhile, we discuss
their strengths and weaknesses. Then, we conduct empirical analyses on existing
methods from performance and efficiency aspects. Besides, we present open
challenges in this field, including human-centric controllable reasoning,
trade-off between interpretability and efficiency of reasoning, ensuring safety
of efficient reasoning, and broader applications of efficient reasoning. In
addition, we highlight key insights for enhancing LRMs' inference efficiency
via techniques such as model merging, new architectures, and agent routers. We
hope this work serves as a valuable guide, helping researchers overcome
challenges in this vibrant
field\footnote\{https://github.com/yueliu1999/Awesome-Efficient-Inference-for-LRMs\}.
