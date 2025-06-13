---
layout: publication
title: '2 Olmo 2 Furious'
authors: Team Olmo, Pete Walsh, Luca Soldaini, Dirk Groeneveld, Kyle Lo, Shane Arora, Akshita Bhagia, Yuling Gu, Shengyi Huang, Matt Jordan, Nathan Lambert, Dustin Schwenk, Oyvind Tafjord, Taira Anderson, David Atkinson, Faeze Brahman, Christopher Clark, Pradeep Dasigi, Nouha Dziri, Michal Guerquin, Hamish Ivison, Pang Wei Koh, Jiacheng Liu, Saumya Malik, William Merrill, Lester James V. Miranda, Jacob Morrison, Tyler Murray, Crystal Nam, Valentina Pyatkin, Aman Rangapur, Michael Schmitz, Sam Skjonsberg, David Wadden, Christopher Wilhelm, Michael Wilson, Luke Zettlemoyer, Ali Farhadi, Noah A. Smith, Hannaneh Hajishirzi
conference: "Arxiv"
year: 2024
bibkey: olmo2024olmo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.00656"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'GPT', 'Pretraining Methods']
---
We present OLMo 2, the next generation of our fully open language models.
OLMo 2 includes dense autoregressive models with improved architecture and
training recipe, pretraining data mixtures, and instruction tuning recipes. Our
modified model architecture and training recipe achieve both better training
stability and improved per-token efficiency. Our updated pretraining data
mixture introduces a new, specialized data mix called Dolmino Mix 1124, which
significantly improves model capabilities across many downstream task
benchmarks when introduced via late-stage curriculum training (i.e. specialized
data during the annealing phase of pretraining). Finally, we incorporate best
practices from T\"ulu 3 to develop OLMo 2-Instruct, focusing on permissive data
and extending our final-stage reinforcement learning with verifiable rewards
(RLVR). Our OLMo 2 base models sit at the Pareto frontier of performance to
compute, often matching or outperforming open-weight only models like Llama 3.1
and Qwen 2.5 while using fewer FLOPs and with fully transparent training data,
code, and recipe. Our fully open OLMo 2-Instruct models are competitive with or
surpassing open-weight only models of comparable size, including Qwen 2.5,
Llama 3.1 and Gemma 2. We release all OLMo 2 artifacts openly -- models at 7B
and 13B scales, both pretrained and post-trained, including their full training
data, training code and recipes, training logs and thousands of intermediate
checkpoints. The final instruction model is available on the Ai2 Playground as
a free research demo.
