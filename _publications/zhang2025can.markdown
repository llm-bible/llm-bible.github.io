---
layout: publication
title: 'Can Large Language Models Help Multimodal Language Analysis? MMLA: A Comprehensive Benchmark'
authors: Hanlei Zhang, Zhuohang Li, Yeshuang Zhu, Hua Xu, Peiwu Wang, Haige Zhu, Jie Zhou, Jinchao Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.16427'}
  - {name: "Code", url: 'https://github.com/thuiar/MMLA'}
tags: ['Has Code', 'RAG', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Multimodal language analysis is a rapidly evolving field that leverages
multiple modalities to enhance the understanding of high-level semantics
underlying human conversational utterances. Despite its significance, little
research has investigated the capability of multimodal large language models
(MLLMs) to comprehend cognitive-level semantics. In this paper, we introduce
MMLA, a comprehensive benchmark specifically designed to address this gap. MMLA
comprises over 61K multimodal utterances drawn from both staged and real-world
scenarios, covering six core dimensions of multimodal semantics: intent,
emotion, dialogue act, sentiment, speaking style, and communication behavior.
We evaluate eight mainstream branches of LLMs and MLLMs using three methods:
zero-shot inference, supervised fine-tuning, and instruction tuning. Extensive
experiments reveal that even fine-tuned models achieve only about 60%~70%
accuracy, underscoring the limitations of current MLLMs in understanding
complex human language. We believe that MMLA will serve as a solid foundation
for exploring the potential of large language models in multimodal language
analysis and provide valuable resources to advance this field. The datasets and
code are open-sourced at https://github.com/thuiar/MMLA.
