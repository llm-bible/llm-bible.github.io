---
layout: publication
title: 'Pico: Jailbreaking Multimodal Large Language Models Via \(\textbf{pi}\)ctorial \(\textbf{co}\)de Contextualization'
authors: Aofan Liu, Lulu Tang, Ting Pan, Yuguo Yin, Bin Wang, Ao Yang
conference: "Arxiv"
year: 2025
bibkey: liu2025jailbreaking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.01444'}
tags: ['RAG', 'Security', 'Model Architecture', 'Training Techniques', 'Tools', 'GPT', 'Multimodal Models']
---
Multimodal Large Language Models (MLLMs), which integrate vision and other
modalities into Large Language Models (LLMs), significantly enhance AI
capabilities but also introduce new security vulnerabilities. By exploiting the
vulnerabilities of the visual modality and the long-tail distribution
characteristic of code training data, we present PiCo, a novel jailbreaking
framework designed to progressively bypass multi-tiered defense mechanisms in
advanced MLLMs. PiCo employs a tier-by-tier jailbreak strategy, using
token-level typographic attacks to evade input filtering and embedding harmful
intent within programming context instructions to bypass runtime monitoring. To
comprehensively assess the impact of attacks, a new evaluation metric is
further proposed to assess both the toxicity and helpfulness of model outputs
post-attack. By embedding harmful intent within code-style visual instructions,
PiCo achieves an average Attack Success Rate (ASR) of 84.13% on Gemini-Pro
Vision and 52.66% on GPT-4, surpassing previous methods. Experimental results
highlight the critical gaps in current defenses, underscoring the need for more
robust strategies to secure advanced MLLMs.
