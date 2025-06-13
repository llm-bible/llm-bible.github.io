---
layout: publication
title: 'Glimpse: Enabling White-box Methods To Use Proprietary Models For Zero-shot Llm-generated Text Detection'
authors: Guangsheng Bao, Yanbin Zhao, Juncai He, Yue Zhang
conference: "Arxiv"
year: 2024
bibkey: bao2024enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11506"}
  - {name: "Code", url: "https://github.com/baoguangsheng/glimpse"}
tags: ['Tools', 'GPT', 'RAG', 'Model Architecture', 'Has Code']
---
Advanced large language models (LLMs) can generate text almost
indistinguishable from human-written text, highlighting the importance of
LLM-generated text detection. However, current zero-shot techniques face
challenges as white-box methods are restricted to use weaker open-source LLMs,
and black-box methods are limited by partial observation from stronger
proprietary LLMs. It seems impossible to enable white-box methods to use
proprietary models because API-level access to the models neither provides full
predictive distributions nor inner embeddings. To traverse the divide, we
propose **Glimpse**, a probability distribution estimation approach, predicting
the full distributions from partial observations. Despite the simplicity of
Glimpse, we successfully extend white-box methods like Entropy, Rank, Log-Rank,
and Fast-DetectGPT to latest proprietary models. Experiments show that Glimpse
with Fast-DetectGPT and GPT-3.5 achieves an average AUROC of about 0.95 in five
latest source models, improving the score by 51% relative to the remaining
space of the open source baseline. It demonstrates that the latest LLMs can
effectively detect their own outputs, suggesting that advanced LLMs may be the
best shield against themselves. We release our code and data at
https://github.com/baoguangsheng/glimpse.
