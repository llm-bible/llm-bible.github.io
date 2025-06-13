---
layout: publication
title: 'MEMLA: Enhancing Multilingual Knowledge Editing With Neuron-masked Low-rank Adaptation'
authors: Jiakuan Xie, Pengfei Cao, Yuheng Chen, Yubo Chen, Kang Liu, Jun Zhao
conference: "Arxiv"
year: 2024
bibkey: xie2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11566"}
tags: ['Fine-Tuning', 'Tools']
---
Knowledge editing aims to adjust the knowledge within large language models
(LLMs) to prevent their responses from becoming obsolete or inaccurate.
However, existing works on knowledge editing are primarily conducted in a
single language, which is inadequate for multilingual language models. In this
paper, we focus on multilingual knowledge editing (MKE), which requires
propagating updates across multiple languages. This necessity poses a
significant challenge for the task. Furthermore, the limited availability of a
comprehensive dataset for MKE exacerbates this challenge, hindering progress in
this area. Hence, we introduce the Multilingual Knowledge Editing Benchmark
(MKEB), a novel dataset comprising 12 languages and providing a complete
evaluation framework. Additionally, we propose a method that enhances
Multilingual knowledge Editing with neuron-Masked Low-Rank Adaptation (MEMLA).
Specifically, we identify two categories of knowledge neurons to improve
editing precision. Moreover, we perform LoRA-based editing with neuron masks to
efficiently modify parameters and facilitate the propagation of updates across
multiple languages. Experiments demonstrate that our method outperforms
existing baselines and significantly enhances the multi-hop reasoning
capability of the edited model, with minimal impact on its downstream task
performance. The dataset and code will be made publicly available.
