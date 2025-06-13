---
layout: publication
title: 'Measuring And Controlling Instruction (in)stability In Language Model Dialogs'
authors: Kenneth Li, Tianle Liu, Naomi Bashkansky, David Bau, Fernanda Viégas, Hanspeter Pfister, Martin Wattenberg
conference: "Arxiv"
year: 2024
bibkey: li2024measuring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.10962'}
tags: ['Attention Mechanism', 'Transformer', 'GPT', 'Model Architecture', 'Prompting', 'Pretraining Methods']
---
System-prompting is a standard tool for customizing language-model chatbots,
enabling them to follow a specific instruction. An implicit assumption in the
use of system prompts is that they will be stable, so the chatbot will continue
to generate text according to the stipulated instructions for the duration of a
conversation. We propose a quantitative benchmark to test this assumption,
evaluating instruction stability via self-chats between two instructed
chatbots. Testing popular models like LLaMA2-chat-70B and GPT-3.5, we reveal a
significant instruction drift within eight rounds of conversations. An
empirical and theoretical analysis of this phenomenon suggests the transformer
attention mechanism plays a role, due to attention decay over long exchanges.
To combat attention decay and instruction drift, we propose a lightweight
method called split-softmax, which compares favorably against two strong
baselines.
