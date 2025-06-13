---
layout: publication
title: 'Exploring User Retrieval Integration Towards Large Language Models For Cross-domain Sequential Recommendation'
authors: Tingjia Shen, Hao Wang, Jiaqing Zhang, Sirui Zhao, Liangyue Li, Zulong Chen, Defu Lian, Enhong Chen
conference: "Arxiv"
year: 2024
bibkey: shen2024exploring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.03085'}
  - {name: "Code", url: 'https://github.com/TingJShen/URLLM'}
tags: ['Reinforcement Learning', 'Has Code', 'Tools', 'Pretraining Methods']
---
Cross-Domain Sequential Recommendation (CDSR) aims to mine and transfer
users' sequential preferences across different domains to alleviate the
long-standing cold-start issue. Traditional CDSR models capture collaborative
information through user and item modeling while overlooking valuable semantic
information. Recently, Large Language Model (LLM) has demonstrated powerful
semantic reasoning capabilities, motivating us to introduce them to better
capture semantic information. However, introducing LLMs to CDSR is non-trivial
due to two crucial issues: seamless information integration and domain-specific
generation. To this end, we propose a novel framework named URLLM, which aims
to improve the CDSR performance by exploring the User Retrieval approach and
domain grounding on LLM simultaneously. Specifically, we first present a novel
dual-graph sequential model to capture the diverse information, along with an
alignment and contrastive learning method to facilitate domain knowledge
transfer. Subsequently, a user retrieve-generation model is adopted to
seamlessly integrate the structural information into LLM, fully harnessing its
emergent inferencing ability. Furthermore, we propose a domain-specific
strategy and a refinement module to prevent out-of-domain generation. Extensive
experiments on Amazon demonstrated the information integration and
domain-specific generation ability of URLLM in comparison to state-of-the-art
baselines. Our code is available at https://github.com/TingJShen/URLLM
