---
layout: publication
title: 'Unmasking The Canvas: A Dynamic Benchmark For Image Generation Jailbreaking And LLM Content Safety'
authors: Variath Madhupal Gautham Nair, Vishal Varma Dantuluri
conference: "Arxiv"
year: 2025
bibkey: nair2025unmasking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.04146"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Prompting']
---
Existing large language models (LLMs) are advancing rapidly and produce
outstanding results in image generation tasks, yet their content safety checks
remain vulnerable to prompt-based jailbreaks. Through preliminary testing on
platforms such as ChatGPT, MetaAI, and Grok, we observed that even short,
natural prompts could lead to the generation of compromising images ranging
from realistic depictions of forged documents to manipulated images of public
figures.
  We introduce Unmasking the Canvas (UTC Benchmark; UTCB), a dynamic and
scalable benchmark dataset to evaluate LLM vulnerability in image generation.
Our methodology combines structured prompt engineering, multilingual
obfuscation (e.g., Zulu, Gaelic, Base64), and evaluation using Groq-hosted
LLaMA-3. The pipeline supports both zero-shot and fallback prompting
strategies, risk scoring, and automated tagging. All generations are stored
with rich metadata and curated into Bronze (non-verified), Silver (LLM-aided
verification), and Gold (manually verified) tiers. UTCB is designed to evolve
over time with new data sources, prompt templates, and model behaviors.
  Warning: This paper includes visual examples of adversarial inputs designed
to test model safety. All outputs have been redacted to ensure responsible
disclosure.
