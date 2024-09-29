---
layout: publication
title: Intent45;conditioned And Non45;toxic Counterspeech Generation Using Multi45;task Instruction Tuning With RLAIF
authors: Hengle Amey, Kumar Aswini, Singh Sahajpreet, Bandhakavi Anil, Akhtar Md Shad, Chakroborty Tanmoy
conference: "Arxiv"
year: 2024
bibkey: hengle2024intent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.10088"}
tags: ['Agentic', 'Ethics And Bias', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools']
---
Counterspeech defined as a response to mitigate online hate speech is increasingly used as a non45;censorial solution. Addressing hate speech effectively involves dispelling the stereotypes prejudices and biases often subtly implied in brief single45;sentence statements or abuses. These implicit expressions challenge language models especially in seq2seq tasks as model performance typically excels with longer contexts. Our study introduces CoARL a novel framework enhancing counterspeech generation by modeling the pragmatic implications underlying social biases in hateful statements. CoARLs first two phases involve sequential multi45;instruction tuning teaching the model to understand intents reactions and harms of offensive statements and then learning task45;specific low45;rank adapter weights for generating intent45;conditioned counterspeech. The final phase uses reinforcement learning to fine45;tune outputs for effectiveness and non45;toxicity. CoARL outperforms existing benchmarks in intent45;conditioned counterspeech generation showing an average improvement of 3 points in intent45;conformity and 4 points in argument45;quality metrics. Extensive human evaluation supports CoARLs efficacy in generating superior and more context45;appropriate responses compared to existing systems including prominent LLMs like ChatGPT.
