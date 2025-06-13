---
layout: publication
title: 'Prefrag: Preference-driven Multi-source Retrieval Augmented Generation'
authors: Qingfei Zhao, Ruobing Wang, Yukuo Cen, Daren Zha, Shicheng Tan, Jie Tang
conference: "Arxiv"
year: 2024
bibkey: zhao2024preference
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.00689'}
  - {name: "Code", url: 'https://github.com/QingFei1/PrefRAG.git'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Fine-Tuning', 'Reinforcement Learning']
---
Retrieval-Augmented Generation (RAG) has emerged as a reliable external
knowledge augmentation technique to mitigate hallucination issues and
parameterized knowledge limitations in Large Language Models (LLMs). Existing
adaptive RAG (ARAG) systems excel at in-depth exploration within a single
source but struggle to effectively and controllably explore different retrieval
sources, as they fail to foresee their internal knowledge features. We develop
a novel multi-source ARAG system, PrefRAG, which enhances RAG by enabling
in-depth and controllable exploration of diverse retrieval sources through
preference-driven adaptive retrieval and self-reflection. PrefRAG first fully
explores controllable local sources in adaptive retrieval and supplements with
the web when appropriate, ultimately selecting the optimal source for knowledge
observation. Subsequently, PrefRAG feeds answer quality feedback into the
retrieval process, optimizing it from the generation perspective to produce
higher-quality responses. Extensive experiments confirm its superiority, high
retrieval efficiency, and knowledge controllability. PrefRAG outperforms
Vanilla RAG and the leading MS-ARAG by up to 25.6% and 13.9% respectively.
Additionally, PrefRAG trained with DPO achieves higher performance. The code
and data are available at https://github.com/QingFei1/PrefRAG.git.
