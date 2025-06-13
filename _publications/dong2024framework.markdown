---
layout: publication
title: 'A Framework For Real-time Safeguarding The Text Generation Of Large Language Model'
authors: Ximing Dong, Dayi Lin, Shaowei Wang, Ahmed E. Hassan
conference: "Arxiv"
year: 2024
bibkey: dong2024framework
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.19048"}
tags: ['Applications', 'Training Techniques', 'Language Modeling', 'Tools']
---
Large Language Models (LLMs) have significantly advanced natural language processing (NLP) tasks but also pose ethical and societal risks due to their propensity to generate harmful content. Existing methods have limitations, including the need for training specific control models and proactive intervention during text generation, that lead to quality degradation and increased computational overhead. To mitigate those limitations, we propose LLMSafeGuard, a lightweight real-time framework that integrates an external validator into decoding, rejecting unsafe outputs while allowing valid ones. We introduce a similarity-based validation approach, simplifying constraint introduction and eliminating the need for control model training. Additionally, LLMSafeGuard employs a context-wise timing selection strategy, intervening LLMs only when necessary. We evaluate LLMSafeGuard on detoxification and copyright safeguarding, demonstrating its superiority over SOTA baselines. In detoxification, LLMSafeGuard reduces toxic output by at least 38.6% while preserving linguistic quality. Additionally, its context-wise timing selection cuts inference time by at least 24.2% without compromising effectiveness.
