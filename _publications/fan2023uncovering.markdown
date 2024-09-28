---
layout: publication
title: Uncovering the Potential of ChatGPT for Discourse Analysis in Dialogue An Empirical Study
authors: Fan Yaxin, Jiang Feng, Li Peifeng, Li Haizhou
conference: "Arxiv"
year: 2023
bibkey: fan2023uncovering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.08391"}
  - {name: "Code", url: "https://github.com/yxfanSuda/GPTforDDA}"}
tags: ['ARXIV', 'Has Code', 'Pretraining Methods']
---
Large language models like ChatGPT have shown remarkable capability in many downstream tasks yet their ability to understand discourse structures of dialogues remains less explored where it requires higher level capabilities of understanding and reasoning. In this paper we aim to systematically inspect ChatGPTs performance in two discourse analysis tasks topic segmentation and discourse parsing focusing on its deep semantic understanding of linear and hierarchical discourse structures underlying dialogue. To instruct ChatGPT to complete these tasks we initially craft a prompt template consisting of the task description output format and structured input. Then we conduct experiments on four popular topic segmentation datasets and two discourse parsing datasets. The experimental results showcase that ChatGPT demonstrates proficiency in identifying topic structures in general-domain conversations yet struggles considerably in specific-domain conversations. We also found that ChatGPT hardly understands rhetorical structures that are more complex than topic structures. Our deeper investigation indicates that ChatGPT can give more reasonable topic structures than human annotations but only linearly parses the hierarchical rhetorical structures. In addition we delve into the impact of in-context learning (e.g. chain-of-thought) on ChatGPT and conduct the ablation study on various prompt components which can provide a research foundation for future work. The code is available at urlhttps://github.com/yxfanSuda/GPTforDDA}.
