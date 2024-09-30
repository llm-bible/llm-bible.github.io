---
layout: publication
title: 'Tarsier: Recipes For Training And Evaluating Large Video Description Models'
authors: Wang Jiawei, Yuan Liping, Zhang Yuchen
conference: "Arxiv"
year: 2024
bibkey: wang2024recipes
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00634"}
  - {name: "Code", url: "https://github.com/bytedance/tarsier"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Generating fine-grained video descriptions is a fundamental challenge in video understanding. In this work we introduce Tarsier a family of large-scale video-language models designed to generate high-quality video descriptions. Tarsier employs CLIP-ViT to encode frames separately and then uses an LLM to model temporal relationships. Despite its simple architecture we demonstrate that with a meticulously designed two-stage training procedure the Tarsier models exhibit substantially stronger video description capabilities than any existing open-source model showing a (+51.4) advantage in human side-by-side evaluation over the strongest model. Additionally they are comparable to state-of-the-art proprietary models with a (+12.3) advantage against GPT-4V and a (-6.7) disadvantage against Gemini 1.5 Pro. Besides video description Tarsier proves to be a versatile generalist model achieving new state-of-the-art results across nine public benchmarks including multi-choice VQA open-ended VQA and zero-shot video captioning. Our second contribution is the introduction of a new benchmark for evaluating video description models consisting of a new challenging dataset featuring videos from diverse sources and varying complexity along with an automatic method specifically designed to assess the quality of fine-grained video descriptions. We make our models and evaluation benchmark publicly available at urlhttps://github.com/bytedance/tarsier\}."
