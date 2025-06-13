---
layout: publication
title: 'A Closer Look At System Prompt Robustness'
authors: Norman Mu, Jonathan Lu, Michael Lavery, David Wagner
conference: "Arxiv"
year: 2025
bibkey: mu2025closer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12197"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
System prompts have emerged as a critical control surface for specifying the
behavior of LLMs in chat and agent settings. Developers depend on system
prompts to specify important context, output format, personalities, guardrails,
content policies, and safety countermeasures, all of which require models to
robustly adhere to the system prompt, especially when facing conflicting or
adversarial user inputs. In practice, models often forget to consider relevant
guardrails or fail to resolve conflicting demands between the system and the
user. In this work, we study various methods for improving system prompt
robustness by creating realistic new evaluation and fine-tuning datasets based
on prompts collected from from OpenAI's GPT Store and HuggingFace's
HuggingChat. Our experiments assessing models with a panel of new and existing
benchmarks show that performance can be considerably improved with realistic
fine-tuning data, as well as inference-time interventions such as
classifier-free guidance. Finally, we analyze the results of recently released
reasoning models from OpenAI and DeepSeek, which show exciting but uneven
improvements on the benchmarks we study. Overall, current techniques fall short
of ensuring system prompt robustness and further study is warranted.
