---
layout: publication
title: 'Applying Refusal-vector Ablation To Llama 3.1 70B Agents'
authors: Simon Lermen, Mateusz Dziemian, Govind Pimpale
conference: "Arxiv"
year: 2024
bibkey: lermen2024applying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10871"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Training Techniques', 'Tools', 'Pretraining Methods', 'Fine-Tuning']
---
Recently, language models like Llama 3.1 Instruct have become increasingly
capable of agentic behavior, enabling them to perform tasks requiring
short-term planning and tool use. In this study, we apply refusal-vector
ablation to Llama 3.1 70B and implement a simple agent scaffolding to create an
unrestricted agent. Our findings imply that these refusal-vector ablated models
can successfully complete harmful tasks, such as bribing officials or crafting
phishing attacks, revealing significant vulnerabilities in current safety
mechanisms. To further explore this, we introduce a small Safe Agent Benchmark,
designed to test both harmful and benign tasks in agentic scenarios. Our
results imply that safety fine-tuning in chat models does not generalize well
to agentic behavior, as we find that Llama 3.1 Instruct models are willing to
perform most harmful tasks without modifications. At the same time, these
models will refuse to give advice on how to perform the same tasks when asked
for a chat completion. This highlights the growing risk of misuse as models
become more capable, underscoring the need for improved safety frameworks for
language model agents.
