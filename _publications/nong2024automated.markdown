---
layout: publication
title: 'APPATCH: Automated Adaptive Prompting Large Language Models For Real-world Software Vulnerability Patching'
authors: Yu Nong, Haoran Yang, Long Cheng, Hongxin Hu, Haipeng Cai
conference: "Arxiv"
year: 2024
bibkey: nong2024automated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.13597"}
tags: ['Security', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Timely and effective vulnerability patching is essential for cybersecurity
defense, for which various approaches have been proposed yet still struggle to
generate valid and correct patches for real-world vulnerabilities. In this
paper, we leverage the power and merits of pre-trained language language models
(LLMs) to enable automated vulnerability patching using no test input/exploit
evidence and without model training/fine-tuning. To elicit LLMs to effectively
reason about vulnerable code behaviors, which is essential for quality patch
generation, we introduce vulnerability semantics reasoning and adaptive
prompting on LLMs and instantiate the methodology as APPATCH, an automated
LLM-based patching system. Our evaluation of APPATCH on 97 zero-day
vulnerabilities and 20 existing vulnerabilities demonstrates its superior
performance to both existing prompting methods and state-of-the-art
non-LLM-based techniques (by up to 28.33% in F1 and 182.26% in recall over the
best baseline). Through APPATCH, we demonstrate what helps for LLM-based
patching and how, as well as discussing what still lacks and why.
