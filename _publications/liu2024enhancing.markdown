---
layout: publication
title: Enhancing LLMs Cognition via Structurization
authors: Liu Kai, Fu Zhihang, Chen Chao, Zhang Wei, Jiang Rongxin, Zhou Fan, Chen Yaowu, Wu Yue, Ye Jieping
conference: "Arxiv"
year: 2024
bibkey: liu2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16434"}
tags: ['ARXIV', 'Applications', 'Attention Mechanism', 'BERT', 'GPT', 'LLM', 'Model Architecture', 'NLP']
---
When reading long-form text human cognition is complex and structurized. While large language models (LLMs) process input contexts through a causal and sequential perspective this approach can potentially limit their ability to handle intricate and complex inputs effectively. To enhance LLMs cognition capability this paper presents a novel concept of context structurization. Specifically we transform the plain unordered contextual sentences into well-ordered and hierarchically structurized elements. By doing so LLMs can better grasp intricate and extended contexts through precise attention and information-seeking along the organized structures. Extensive evaluations are conducted across various model architectures and sizes (including several 7B- to 72B-size auto-regressive LLMs as well as BERT-like masking models) on a diverse set of NLP tasks (e.g. context-based question-answering exhaustive hallucination evaluation and passage-level dense retrieval). Empirical results show consistent and significant performance gains afforded by a single-round structurization. In particular we boost a 72B-parameter open-source model to achieve comparable performance against GPT-3.5-Turbo as the hallucination evaluator. Besides we show the feasibility of distilling advanced LLMs language processing abilities to a smaller yet effective StruXGPT-7B to execute structurization addressing the practicality of our approach. Code will be made public soon.
