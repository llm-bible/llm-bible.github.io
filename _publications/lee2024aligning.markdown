---
layout: publication
title: Aligning To Thousands Of Preferences Via System Message Generalization
authors: Lee Seongyun, Park Sue Hyun, Kim Seungone, Seo Minjoon
conference: "Arxiv"
year: 2024
bibkey: lee2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17977"}
  - {name: "Code", url: "https://github.com/kaistAI/Janus"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Although humans inherently have diverse values current large language model (LLM) alignment methods often assume that aligning LLMs with the general publics preferences is optimal. A major challenge in adopting a more individualized approach to LLM alignment is its lack of scalability as it involves repeatedly acquiring preference data and training new reward models and LLMs for each individuals preferences. To address these challenges we propose a new paradigm where users specify what they value most within the system message steering the LLMs generation behavior to better align with the users intentions. However a naive application of such an approach is non-trivial since LLMs are typically trained on a uniform system message (e.g. You are a helpful assistant) which limits their ability to generalize to diverse unseen system messages. To improve this generalization we create the Multifaceted Collection a preference dataset with 192k combinations of values beyond generic helpfulness and harmlessness spanning 65k user instructions. Using this dataset we train a 7B LLM called Janus and test it on 921 prompts from 5 benchmarks (AlpacaEval 2.0 FLASK Koala MT-Bench and Self-Instruct) by adding various unseen system messages that reflect user preferences. Janus achieves tie+win rate of 75.237; 72.437; and 66.437; against Mistral 7B Instruct v0.2 GPT-3.5 Turbo and GPT-4 respectively. Unexpectedly on three benchmarks focused on response helpfulness (AlpacaEval 2.0 MT-Bench Arena Hard Auto v0.1) Janus also outperforms LLaMA 3 8B Instruct by a +4.037; +0.137; +3.037; margin underscoring that training with a vast array of system messages could also enhance alignment to the general publics preference as well. Our code dataset benchmark and models are available at https://github.com/kaistAI/Janus.
