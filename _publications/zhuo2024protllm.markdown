---
layout: publication
title: ProtLLM An Interleaved Protein-Language LLM with Protein-as-Word Pre-Training
authors: Zhuo Le, Chi Zewen, Xu Minghao, Huang Heyan, Zheng Heqi, He Conghui, Mao Xian-ling, Zhang Wentao
conference: "Arxiv"
year: 2024
bibkey: zhuo2024protllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.07920"}
tags: ['ARXIV', 'Applications', 'Cross Modal', 'LLM', 'Language Modeling', 'Supervised']
---
We propose ProtLLM a versatile cross-modal large language model (LLM) for both protein-centric and protein-language tasks. ProtLLM features a unique dynamic protein mounting mechanism enabling it to handle complex inputs where the natural language text is interspersed with an arbitrary number of proteins. Besides we propose the protein-as-word language modeling approach to train ProtLLM. By developing a specialized protein vocabulary we equip the model with the capability to predict not just natural language but also proteins from a vast pool of candidates. Additionally we construct a large-scale interleaved protein-text dataset named InterPT for pre-training. This dataset comprehensively encompasses both (1) structured data sources like protein annotations and (2) unstructured data sources like biological research papers thereby endowing ProtLLM with crucial knowledge for understanding proteins. We evaluate ProtLLM on classic supervised protein-centric tasks and explore its novel protein-language applications. Experimental results demonstrate that ProtLLM not only achieves superior performance against protein-specialized baselines on protein-centric tasks but also induces zero-shot and in-context learning capabilities on protein-language tasks.
