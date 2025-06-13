---
layout: publication
title: 'Soteria: Language-specific Functional Parameter Steering For Multilingual Safety Alignment'
authors: Somnath Banerjee, Sayan Layek, Pratyush Chatterjee, Animesh Mukherjee, Rima Hazra
conference: "Arxiv"
year: 2025
bibkey: banerjee2025language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11244"}
tags: ['Responsible AI', 'Reinforcement Learning']
---
Ensuring consistent safety across multiple languages remains a significant
challenge for large language models (LLMs). We introduce Soteria, a lightweight
yet powerful strategy that locates and minimally adjusts the "functional heads"
most responsible for harmful content generation in each language. By altering
only a fraction of parameters, Soteria drastically reduces policy violations
without sacrificing overall model performance, even in low-resource settings.
To rigorously evaluate our approach, we also present XThreatBench, a
specialized multilingual dataset capturing fine-grained harmful behaviors drawn
from real policy guidelines. Experiments with leading open-source LLMs (e.g.,
Llama, Qwen, Mistral) show that Soteria consistently improves safety metrics
across high-, mid-, and low-resource languages. These findings highlight a
promising path toward scalable, linguistically attuned, and ethically aligned
LLMs worldwide.
