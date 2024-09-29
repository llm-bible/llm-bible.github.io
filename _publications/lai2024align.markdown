---
layout: publication
title: Alarm Align Language Models Via Hierarchical Rewards Modeling
authors: Lai Yuhang, Wang Siyuan, Liu Shujun, Huang Xuanjing, Wei Zhongyu
conference: "Arxiv"
year: 2024
bibkey: lai2024align
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.06754"}
  - {name: "Code", url: "https://ALaRM&#45;fdu.github.io"}
tags: ['Agentic', 'Applications', 'GPT', 'Has Code', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
We introduce ALaRM the first framework modeling hierarchical rewards in reinforcement learning from human feedback (RLHF) which is designed to enhance the alignment of large language models (LLMs) with human preferences. The framework addresses the limitations of current alignment approaches which often struggle with the inconsistency and sparsity of human supervision signals by integrating holistic rewards with aspect45;specific rewards. This integration enables more precise and consistent guidance of language models towards desired outcomes particularly in complex and open text generation tasks. By employing a methodology that filters and combines multiple rewards based on their consistency the framework provides a reliable mechanism for improving model alignment. We validate our approach through applications in long45;form question answering and machine translation tasks employing gpt45;3.545;turbo for pairwise comparisons and demonstrate improvements over existing baselines. Our work underscores the effectiveness of hierarchical rewards modeling in refining LLM training processes for better human preference alignment. We release our code at https://ALaRM&#45;fdu.github.io.
