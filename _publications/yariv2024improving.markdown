---
layout: publication
title: "Improving Visual Commonsense In Language Models Via Multiple Image Generation"
authors: Yariv Guy, Schwartz Idan, Adi Yossi, Benaim Sagie
conference: "Arxiv"
year: 2024
bibkey: yariv2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13621"}
  - {name: "Code", url: "https://github.com/guyyariv/vLMIG"}
tags: ['Has Code', 'Language Modeling', 'Merging', 'Multimodal Models', 'Prompting']
---
Commonsense reasoning is fundamentally based on multimodal knowledge. However existing large language models (LLMs) are primarily trained using textual data only limiting their ability to incorporate essential visual information. In contrast Visual Language Models which excel at visually-oriented tasks often fail at non-visual tasks such as basic commonsense reasoning. This divergence highlights a critical challenge - the integration of robust visual understanding with foundational text-based language reasoning. To this end we introduce a method aimed at enhancing LLMs visual commonsense. Specifically our method generates multiple images based on the input text prompt and integrates these into the models decision-making process by mixing their prediction probabilities. To facilitate multimodal grounded language modeling we employ a late-fusion layer that combines the projected visual features with the output of a pre-trained LLM conditioned on text only. This late-fusion layer enables predictions based on comprehensive image-text knowledge as well as text only when this is required. We evaluate our approach using several visual commonsense reasoning tasks together with traditional NLP tasks including common sense reasoning and reading comprehension. Our experimental results demonstrate significant superiority over existing baselines. When applied to recent state-of-the-art LLMs (e.g. Llama3) we observe improvements not only in visual common sense but also in traditional NLP benchmarks. Code and models are available under https://github.com/guyyariv/vLMIG."
