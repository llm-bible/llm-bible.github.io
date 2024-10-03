---
layout: publication
title: 'A Framework For Real-time Safeguarding The Text Generation Of Large Language Model'
authors: Dong Ximing, Lin Dayi, Wang Shaowei, Hassan Ahmed E.
conference: "Arxiv"
year: 2024
bibkey: dong2024framework
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.19048"}
tags: ['Applications', 'Efficiency And Optimization', 'Language Modeling', 'RAG', 'Reinforcement Learning', 'Responsible AI', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have significantly advanced natural language processing (NLP) tasks but also pose ethical and societal risks due to their propensity to generate harmful content. To address this, various approaches have been developed to safeguard LLMs from producing unsafe content. However, existing methods have limitations, including the need for training specific control models and proactive intervention during text generation, that lead to quality degradation and increased computational overhead. To mitigate those limitations, we propose LLMSafeGuard, a lightweight framework to safeguard LLM text generation in real-time. LLMSafeGuard integrates an external validator into the beam search algorithm during decoding, rejecting candidates that violate safety constraints while allowing valid ones to proceed. We introduce a similarity based validation approach, simplifying constraint introduction and eliminating the need for control model training. Additionally, LLMSafeGuard employs a context-wise timing selection strategy, intervening LLMs only when necessary. We evaluate LLMSafeGuard on two tasks, detoxification and copyright safeguarding, and demonstrate its superior performance over SOTA baselines. For instance, LLMSafeGuard reduces the average toxic score of. LLM output by 29.7&#37; compared to the best baseline meanwhile preserving similar linguistic quality as natural output in detoxification task. Similarly, in the copyright task, LLMSafeGuard decreases the Longest Common Subsequence (LCS) by 56.2&#37; compared to baselines. Moreover, our context-wise timing selection strategy reduces inference time by at least 24&#37; meanwhile maintaining comparable effectiveness as validating each time step. LLMSafeGuard also offers tunable parameters to balance its effectiveness and efficiency.
