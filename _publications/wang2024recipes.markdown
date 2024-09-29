---
layout: publication
title: Tarsier Recipes For Training And Evaluating Large Video Description Models
authors: Wang Jiawei, Yuan Liping, Zhang Yuchen
conference: "Arxiv"
year: 2024
bibkey: wang2024recipes
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00634"}
  - {name: "Code", url: "https://github.com/bytedance/tarsier&#125;"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Generating fine45;grained video descriptions is a fundamental challenge in video understanding. In this work we introduce Tarsier a family of large45;scale video45;language models designed to generate high45;quality video descriptions. Tarsier employs CLIP45;ViT to encode frames separately and then uses an LLM to model temporal relationships. Despite its simple architecture we demonstrate that with a meticulously designed two45;stage training procedure the Tarsier models exhibit substantially stronger video description capabilities than any existing open45;source model showing a +51.437; advantage in human side45;by45;side evaluation over the strongest model. Additionally they are comparable to state45;of45;the45;art proprietary models with a +12.337; advantage against GPT45;4V and a 45;6.737; disadvantage against Gemini 1.5 Pro. Besides video description Tarsier proves to be a versatile generalist model achieving new state45;of45;the45;art results across nine public benchmarks including multi45;choice VQA open45;ended VQA and zero45;shot video captioning. Our second contribution is the introduction of a new benchmark for evaluating video description models consisting of a new challenging dataset featuring videos from diverse sources and varying complexity along with an automatic method specifically designed to assess the quality of fine45;grained video descriptions. We make our models and evaluation benchmark publicly available at url123;https://github.com/bytedance/tarsier&#125;.
