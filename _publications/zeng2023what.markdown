---
layout: publication
title: 'What Matters In Training A Gpt4-style Language Model With Multimodal Inputs?'
authors: Zeng Yan, Zhang Hanbo, Zheng Jiani, Xia Jiangnan, Wei Guoqiang, Wei Yang, Zhang Yuchen, Kong Tao
conference: "Arxiv"
year: 2023
bibkey: zeng2023what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.02469"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Survey Paper', 'Training Techniques']
---
Recent advancements in Large Language Models (LLMs) such as GPT4 have
displayed exceptional multi-modal capabilities in following open-ended
instructions given images. However, the performance of these models heavily
relies on design choices such as network structures, training data, and
training strategies, and these choices have not been extensively discussed in
the literature, making it difficult to quantify progress in this field. To
address this issue, this paper presents a systematic and comprehensive study,
quantitatively and qualitatively, on training such models. We implement over 20
variants with controlled settings. Concretely, for network structures, we
compare different LLM backbones and model designs. For training data, we
investigate the impact of data and sampling strategies. For instructions, we
explore the influence of diversified prompts on the instruction-following
ability of the trained models. For benchmarks, we contribute the first, to our
best knowledge, comprehensive evaluation set including both image and video
tasks through crowd-sourcing. Based on our findings, we present Lynx, which
performs the most accurate multi-modal understanding while keeping the best
multi-modal generation ability compared to existing open-sourced GPT4-style
models.
