---
layout: publication
title: 'Generating Negative Samples For Multi-modal Recommendation'
authors: Yanbiao Ji, Yue Ding, Dan Luo, Chang Liu, Jing Tong, Shaokai Wu, Hongtao Lu
conference: "Arxiv"
year: 2025
bibkey: ji2025generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15183"}
tags: ['Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'RecSys', 'Attention Mechanism', 'Prompting']
---
Multi-modal recommender systems (MMRS) have gained significant attention due
to their ability to leverage information from various modalities to enhance
recommendation quality. However, existing negative sampling techniques often
struggle to effectively utilize the multi-modal data, leading to suboptimal
performance. In this paper, we identify two key challenges in negative sampling
for MMRS: (1) producing cohesive negative samples contrasting with positive
samples and (2) maintaining a balanced influence across different modalities.
To address these challenges, we propose NegGen, a novel framework that utilizes
multi-modal large language models (MLLMs) to generate balanced and contrastive
negative samples. We design three different prompt templates to enable NegGen
to analyze and manipulate item attributes across multiple modalities, and then
generate negative samples that introduce better supervision signals and ensure
modality balance. Furthermore, NegGen employs a causal learning module to
disentangle the effect of intervened key features and irrelevant item
attributes, enabling fine-grained learning of user preferences. Extensive
experiments on real-world datasets demonstrate the superior performance of
NegGen compared to state-of-the-art methods in both negative sampling and
multi-modal recommendation.
