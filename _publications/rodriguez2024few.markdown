---
layout: publication
title: 'Intentgpt: Few-shot Intent Discovery With Large Language Models'
authors: Juan A. Rodriguez, Nicholas Botzer, David Vazquez, Christopher Pal, Marco Pedersoli, Issam Laradji
conference: "Arxiv"
year: 2024
bibkey: rodriguez2024few
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.10670'}
tags: ['Attention Mechanism', 'Few-Shot', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Prompting', 'Applications', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
In today's digitally driven world, dialogue systems play a pivotal role in
enhancing user interactions, from customer service to virtual assistants. In
these dialogues, it is important to identify user's goals automatically to
resolve their needs promptly. This has necessitated the integration of models
that perform Intent Detection. However, users' intents are diverse and dynamic,
making it challenging to maintain a fixed set of predefined intents. As a
result, a more practical approach is to develop a model capable of identifying
new intents as they emerge. We address the challenge of Intent Discovery, an
area that has drawn significant attention in recent research efforts. Existing
methods need to train on a substantial amount of data for correctly identifying
new intents, demanding significant human effort. To overcome this, we introduce
IntentGPT, a novel training-free method that effectively prompts Large Language
Models (LLMs) such as GPT-4 to discover new intents with minimal labeled data.
IntentGPT comprises an \textit\{In-Context Prompt Generator\}, which generates
informative prompts for In-Context Learning, an \textit\{Intent Predictor\} for
classifying and discovering user intents from utterances, and a
\textit\{Semantic Few-Shot Sampler\} that selects relevant few-shot examples and
a set of known intents to be injected into the prompt. Our experiments show
that IntentGPT outperforms previous methods that require extensive
domain-specific data and fine-tuning, in popular benchmarks, including CLINC
and BANKING, among others.
