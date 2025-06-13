---
layout: publication
title: 'M\(^3\)GPT: An Advanced Multimodal, Multitask Framework For Motion Comprehension And Generation'
authors: Mingshuang Luo, Ruibing Hou, Zhuo Li, Hong Chang, Zimo Liu, Yaowei Wang, Shiguang Shan
conference: "Arxiv"
year: 2024
bibkey: luo2024advanced
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.16273'}
  - {name: "Code", url: 'https://github.com/luomingshuang/M3GPT'}
tags: ['Has Code', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'GPT', 'Quantization', 'Multimodal Models', 'Reinforcement Learning']
---
This paper presents M\\(^3\\)GPT, an advanced \\(\textbf\{M\}\\)ultimodal,
\\(\textbf\{M\}\\)ultitask framework for \\(\textbf\{M\}\\)otion comprehension and
generation. M\\(^3\\)GPT operates on three fundamental principles. The first
focuses on creating a unified representation space for various motion-relevant
modalities. We employ discrete vector quantization for multimodal conditional
signals, such as text, music and motion/dance, enabling seamless integration
into a large language model (LLM) with a single vocabulary. The second involves
modeling motion generation directly in the raw motion space. This strategy
circumvents the information loss associated with a discrete tokenizer,
resulting in more detailed and comprehensive motion generation. Third, M\\(^3\\)GPT
learns to model the connections and synergies among various motion-relevant
tasks. Text, the most familiar and well-understood modality for LLMs, is
utilized as a bridge to establish connections between different motion tasks,
facilitating mutual reinforcement. To our knowledge, M\\(^3\\)GPT is the first
model capable of comprehending and generating motions based on multiple
signals. Extensive experiments highlight M\\(^3\\)GPT's superior performance across
various motion-relevant tasks and its powerful zero-shot generalization
capabilities for extremely challenging tasks. Project page:
\url\{https://github.com/luomingshuang/M3GPT\}.
