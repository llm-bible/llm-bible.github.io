---
layout: publication
title: Revisit Input Perturbation Problems For Llms A Unified Robustness Evaluation Framework For Noisy Slot Filling Task
authors: Dong Guanting, Zhao Jinxu, Hui Tingfeng, Guo Daichi, Wan Wenlong, Feng Boqi, Qiu Yueyan, Gongque Zhuoma, He Keqing, Wang Zechen, Xu Weiran
conference: "Arxiv"
year: 2023
bibkey: dong2023revisit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06504"}
tags: ['Prompting', 'Reinforcement Learning', 'Security', 'Tools']
---
With the increasing capabilities of large language models (LLMs) these high-performance models have achieved state-of-the-art results on a wide range of natural language processing (NLP) tasks. However the models performance on commonly-used benchmark datasets often fails to accurately reflect their reliability and robustness when applied to real-world noisy data. To address these challenges we propose a unified robustness evaluation framework based on the slot-filling task to systematically evaluate the dialogue understanding capability of LLMs in diverse input perturbation scenarios. Specifically we construct a input perturbation evaluation dataset Noise-LLM which contains five types of single perturbation and four types of mixed perturbation data. Furthermore we utilize a multi-level data augmentation method (character word and sentence levels) to construct a candidate data pool and carefully design two ways of automatic task demonstration construction strategies (instance-level and entity-level) with various prompt templates. Our aim is to assess how well various robustness methods of LLMs perform in real-world noisy scenarios. The experiments have demonstrated that the current open-source LLMs generally achieve limited perturbation robustness performance. Based on these experimental observations we make some forward-looking suggestions to fuel the research in this direction.
