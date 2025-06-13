---
layout: publication
title: 'Llmstinger: Jailbreaking Llms Using RL Fine-tuned Llms'
authors: Piyush Jha, Arnav Arora, Vijay Ganesh
conference: "Arxiv"
year: 2024
bibkey: jha2024jailbreaking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.08862'}
tags: ['Agentic', 'RAG', 'Security', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Responsible AI']
---
We introduce LLMStinger, a novel approach that leverages Large Language
Models (LLMs) to automatically generate adversarial suffixes for jailbreak
attacks. Unlike traditional methods, which require complex prompt engineering
or white-box access, LLMStinger uses a reinforcement learning (RL) loop to
fine-tune an attacker LLM, generating new suffixes based on existing attacks
for harmful questions from the HarmBench benchmark. Our method significantly
outperforms existing red-teaming approaches (we compared against 15 of the
latest methods), achieving a +57.2% improvement in Attack Success Rate (ASR) on
LLaMA2-7B-chat and a +50.3% ASR increase on Claude 2, both models known for
their extensive safety measures. Additionally, we achieved a 94.97% ASR on
GPT-3.5 and 99.4% on Gemma-2B-it, demonstrating the robustness and adaptability
of LLMStinger across open and closed-source models.
