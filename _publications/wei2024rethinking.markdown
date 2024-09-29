---
layout: publication
title: Rethinking Generative Large Language Model Evaluation for Semantic Comprehension
authors: Wei Fangyun, Chen Xi, Luo Lin
conference: "Arxiv"
year: 2024
bibkey: wei2024rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.07872"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Despite their sophisticated capabilities large language models (LLMs) encounter a major hurdle in effective assessment. This paper first revisits the prevalent evaluation method-multiple choice question answering (MCQA) which allows for straightforward accuracy measurement. Through a comprehensive evaluation of 24 models across 11 benchmarks we highlight several potential drawbacks of MCQA for instance the inconsistency between the MCQA evaluation and the generation of open-ended responses in practical scenarios. In response we introduce an RWQ-Elo rating system engaging 24 LLMs such as GPT-4 GPT-3.5 Google-Gemini-Pro and LLaMA-1/-2 in a two-player competitive format with GPT-4 serving as the judge. Each LLM receives an Elo rating thereafter. This system is designed to mirror real-world usage and for this purpose we have compiled a new benchmark called Real-world questions (RWQ) comprising 20772 authentic user inquiries. Additionally we thoroughly analyze the characteristics of our system and compare it with prior leaderboards like AlpacaEval and MT-Bench. Our analysis reveals the stability of our RWQ-Elo system the feasibility of registering new models and its potential to reshape LLM leaderboards.
