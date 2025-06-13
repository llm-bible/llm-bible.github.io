---
layout: publication
title: 'Understanding The Repeat Curse In Large Language Models From A Feature Perspective'
authors: Junchi Yao, Shu Yang, Jianhua Xu, Lijie Hu, Mengdi Li, Di Wang
conference: "Arxiv"
year: 2025
bibkey: yao2025understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14218"}
tags: ['Reinforcement Learning', 'Language Modeling', 'RAG', 'Interpretability and Explainability', 'Applications']
---
Large language models (LLMs) have made remarkable progress in various domains, yet they often suffer from repetitive text generation, a phenomenon we refer to as the "Repeat Curse". While previous studies have proposed decoding strategies to mitigate repetition, the underlying mechanism behind this issue remains insufficiently explored. In this work, we investigate the root causes of repetition in LLMs through the lens of mechanistic interpretability. Inspired by recent advances in Sparse Autoencoders (SAEs), which enable monosemantic feature extraction, we propose a novel approach, "Duplicatus Charm", to induce and analyze the Repeat Curse. Our method systematically identifies "Repetition Features" -the key model activations responsible for generating repetitive outputs. First, we locate the layers most involved in repetition through logit analysis. Next, we extract and stimulate relevant features using SAE-based activation manipulation. To validate our approach, we construct a repetition dataset covering token and paragraph level repetitions and introduce an evaluation pipeline to quantify the influence of identified repetition features. Furthermore, by deactivating these features, we have effectively mitigated the Repeat Curse.
