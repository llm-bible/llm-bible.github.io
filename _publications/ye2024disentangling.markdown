---
layout: publication
title: 'Disentangling Reasoning Tokens And Boilerplate Tokens For Language Model Fine-tuning'
authors: Ziang Ye, Zhenru Zhang, Yang Zhang, Jianxin Ma, Junyang Lin, Fuli Feng
conference: "Arxiv"
year: 2024
bibkey: ye2024disentangling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14780"}
tags: ['Agentic', 'Pretraining Methods', 'Training Techniques', 'Fine-Tuning']
---
When using agent-task datasets to enhance agent capabilities for Large
Language Models (LLMs), current methodologies often treat all tokens within a
sample equally. However, we argue that tokens serving different roles -
specifically, reasoning tokens versus boilerplate tokens (e.g., those governing
output format) - differ significantly in importance and learning complexity,
necessitating their disentanglement and distinct treatment. To address this, we
propose a novel Shuffle-Aware Discriminator (SHAD) for adaptive token
discrimination. SHAD classifies tokens by exploiting predictability differences
observed after shuffling input-output combinations across samples: boilerplate
tokens, due to their repetitive nature among samples, maintain predictability,
whereas reasoning tokens do not. Using SHAD, we propose the
Reasoning-highlighted Fine-Tuning (RFT) method, which adaptively emphasizes
reasoning tokens during fine-tuning, yielding notable performance gains over
common Supervised Fine-Tuning (SFT).
