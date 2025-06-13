---
layout: publication
title: 'Flexvln: Flexible Adaptation For Diverse Vision-and-language Navigation Tasks'
authors: Siqi Zhang, Yanyuan Qiao, Qunbo Wang, Longteng Guo, Zhihua Wei, Jing Liu
conference: "Arxiv"
year: 2025
bibkey: zhang2025flexible
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.13966'}
tags: ['Agentic', 'Training Techniques']
---
The aspiration of the Vision-and-Language Navigation (VLN) task has long been
to develop an embodied agent with robust adaptability, capable of seamlessly
transferring its navigation capabilities across various tasks. Despite
remarkable advancements in recent years, most methods necessitate
dataset-specific training, thereby lacking the capability to generalize across
diverse datasets encompassing distinct types of instructions. Large language
models (LLMs) have demonstrated exceptional reasoning and generalization
abilities, exhibiting immense potential in robot action planning. In this
paper, we propose FlexVLN, an innovative hierarchical approach to VLN that
integrates the fundamental navigation ability of a supervised-learning-based
Instruction Follower with the robust generalization ability of the LLM Planner,
enabling effective generalization across diverse VLN datasets. Moreover, a
verification mechanism and a multi-model integration mechanism are proposed to
mitigate potential hallucinations by the LLM Planner and enhance execution
accuracy of the Instruction Follower. We take REVERIE, SOON, and CVDN-target as
out-of-domain datasets for assessing generalization ability. The generalization
performance of FlexVLN surpasses that of all the previous methods to a large
extent.
