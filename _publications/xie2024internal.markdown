---
layout: publication
title: 'Textrefiner: Internal Visual Feature As Efficient Refiner For Vision-language Models Prompt Tuning'
authors: Jingjing Xie, Yuxin Zhang, Jun Peng, Zhaohong Huang, Liujuan Cao
conference: "Arxiv"
year: 2024
bibkey: xie2024internal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.08176"}
  - {name: "Code", url: "https://github.com/xjjxmu/TextRefiner"}
tags: ['Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Has Code', 'Multimodal Models', 'Prompting']
---
Despite the efficiency of prompt learning in transferring vision-language
models (VLMs) to downstream tasks, existing methods mainly learn the prompts in
a coarse-grained manner where the learned prompt vectors are shared across all
categories. Consequently, the tailored prompts often fail to discern
class-specific visual concepts, thereby hindering the transferred performance
for classes that share similar or complex visual attributes. Recent advances
mitigate this challenge by leveraging external knowledge from Large Language
Models (LLMs) to furnish class descriptions, yet incurring notable inference
costs. In this paper, we introduce TextRefiner, a plug-and-play method to
refine the text prompts of existing methods by leveraging the internal
knowledge of VLMs. Particularly, TextRefiner builds a novel local cache module
to encapsulate fine-grained visual concepts derivedfrom local tokens within the
image branch. By aggregating and aligning the cached visual descriptions with
the original output of the text branch, TextRefiner can efficiently refine and
enrich the learned prompts from existing methods without relying on any
external expertise. For example, it improves the performance of CoOp from 71.66
% to 76.94 % on 11 benchmarks, surpassing CoCoOp which introduces instance-wise
features for text prompts. Equipped with TextRefiner, PromptKD achieves
state-of-the-art performance and is efficient in inference. Our code is relesed
at https://github.com/xjjxmu/TextRefiner
