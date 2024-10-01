---
layout: publication
title: 'Intent-conditioned And Non-toxic Counterspeech Generation Using Multi-task Instruction Tuning With RLAIF'
authors: Hengle Amey, Kumar Aswini, Singh Sahajpreet, Bandhakavi Anil, Akhtar Md Shad, Chakroborty Tanmoy
conference: "Arxiv"
year: 2024
bibkey: hengle2024intent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.10088"}
tags: ['Agentic', 'Ethics And Bias', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools']
---
Counterspeech, defined as a response to mitigate online hate speech, is increasingly used as a non-censorial solution. Addressing hate speech effectively involves dispelling the stereotypes, prejudices, and biases often subtly implied in brief, single-sentence statements or abuses. These implicit expressions challenge language models, especially in seq2seq tasks, as model performance typically excels with longer contexts. Our study introduces CoARL, a novel framework enhancing counterspeech generation by modeling the pragmatic implications underlying social biases in hateful statements. CoARL's first two phases involve sequential multi-instruction tuning, teaching the model to understand intents, reactions, and harms of offensive statements, and then learning task-specific low-rank adapter weights for generating intent-conditioned counterspeech. The final phase uses reinforcement learning to fine-tune outputs for effectiveness and non-toxicity. CoARL outperforms existing benchmarks in intent-conditioned counterspeech generation, showing an average improvement of 3 points in intent-conformity and 4 points in argument-quality metrics. Extensive human evaluation supports CoARL's efficacy in generating superior and more context-appropriate responses compared to existing systems, including prominent LLMs like ChatGPT.
