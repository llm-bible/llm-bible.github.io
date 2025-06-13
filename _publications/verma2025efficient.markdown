---
layout: publication
title: 'OMNIGUARD: An Efficient Approach For AI Safety Moderation Across Modalities'
authors: Sahil Verma, Keegan Hines, Jeff Bilmes, Charlotte Siska, Luke Zettlemoyer, Hila Gonen, Chandan Singh
conference: "Arxiv"
year: 2025
bibkey: verma2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23856'}
  - {name: "Code", url: 'https://github.com/vsahil/OmniGuard'}
tags: ['Has Code', 'Security', 'Merging', 'Prompting', 'Reinforcement Learning', 'Responsible AI']
---
The emerging capabilities of large language models (LLMs) have sparked concerns about their immediate potential for harmful misuse. The core approach to mitigate these concerns is the detection of harmful queries to the model. Current detection approaches are fallible, and are particularly susceptible to attacks that exploit mismatched generalization of model capabilities (e.g., prompts in low-resource languages or prompts provided in non-text modalities such as image and audio). To tackle this challenge, we propose OMNIGUARD, an approach for detecting harmful prompts across languages and modalities. Our approach (i) identifies internal representations of an LLM/MLLM that are aligned across languages or modalities and then (ii) uses them to build a language-agnostic or modality-agnostic classifier for detecting harmful prompts. OMNIGUARD improves harmful prompt classification accuracy by 11.57% over the strongest baseline in a multilingual setting, by 20.44% for image-based prompts, and sets a new SOTA for audio-based prompts. By repurposing embeddings computed during generation, OMNIGUARD is also very efficient (\\(\approx 120 \times\\) faster than the next fastest baseline). Code and data are available at: https://github.com/vsahil/OmniGuard.
