---
layout: publication
title: 'Causality For Large Language Models'
authors: Anpeng Wu, Kun Kuang, Minqin Zhu, Yingrong Wang, Yujia Zheng, Kairong Han, Baohong Li, Guangyi Chen, Fei Wu, Kun Zhang
conference: "Arxiv"
year: 2024
bibkey: wu2024causality
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15319"}
tags: ['Training Techniques', 'Survey Paper', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Recent breakthroughs in artificial intelligence have driven a paradigm shift,
where large language models (LLMs) with billions or trillions of parameters are
trained on vast datasets, achieving unprecedented success across a series of
language tasks. However, despite these successes, LLMs still rely on
probabilistic modeling, which often captures spurious correlations rooted in
linguistic patterns and social stereotypes, rather than the true causal
relationships between entities and events. This limitation renders LLMs
vulnerable to issues such as demographic biases, social stereotypes, and LLM
hallucinations. These challenges highlight the urgent need to integrate
causality into LLMs, moving beyond correlation-driven paradigms to build more
reliable and ethically aligned AI systems.
  While many existing surveys and studies focus on utilizing prompt engineering
to activate LLMs for causal knowledge or developing benchmarks to assess their
causal reasoning abilities, most of these efforts rely on human intervention to
activate pre-trained models. How to embed causality into the training process
of LLMs and build more general and intelligent models remains unexplored.
Recent research highlights that LLMs function as causal parrots, capable of
reciting causal knowledge without truly understanding or applying it. These
prompt-based methods are still limited to human interventional improvements.
This survey aims to address this gap by exploring how causality can enhance
LLMs at every stage of their lifecycle-from token embedding learning and
foundation model training to fine-tuning, alignment, inference, and
evaluation-paving the way for more interpretable, reliable, and
causally-informed models. Additionally, we further outline six promising future
directions to advance LLM development, enhance their causal reasoning
capabilities, and address the current limitations these models face.
