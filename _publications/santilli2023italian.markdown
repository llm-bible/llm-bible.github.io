---
layout: publication
title: 'Camoscio: An Italian Instruction-tuned Llama'
authors: Santilli Andrea, Rodolà Emanuele
conference: "Arxiv"
year: 2023
bibkey: santilli2023italian
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.16456"}
  - {name: "Code", url: "https://github.com/teelinsan/camoscio"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
In recent years Large Language Models (LLMs) have increased the state of the
art on several natural language processing tasks. However, their accessibility
is often limited to paid API services, posing challenges for researchers in
conducting extensive investigations. On the other hand, while some open-source
models have been proposed by the community, they are typically English-centric
or multilingual without a specific adaptation for the Italian language. In an
effort to democratize the available and open resources for the Italian
language, in this paper we introduce Camoscio: a language model specifically
tuned to follow users' prompts in Italian. Specifically, we finetuned the
smallest variant of LLaMA (7b) with LoRA on a corpus of instruction prompts
translated to Italian via ChatGPT. Results indicate that the model's zero-shot
performance on various downstream tasks in Italian competes favorably with
existing models specifically finetuned for those tasks. All the artifacts
(code, dataset, model) are released to the community at the following url:
https://github.com/teelinsan/camoscio
