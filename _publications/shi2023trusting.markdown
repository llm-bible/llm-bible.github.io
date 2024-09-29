---
layout: publication
title: "Trusting Your Evidence: Hallucinate Less With Context-aware Decoding"
authors: Shi Weijia, Han Xiaochuang, Lewis Mike, Tsvetkov Yulia, Zettlemoyer Luke, Yih Scott Wen-tau
conference: "Arxiv"
year: 2023
bibkey: shi2023trusting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14739"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Language models (LMs) often struggle to pay enough attention to the input context and generate texts that are unfaithful or contain hallucinations. To mitigate this issue we present context-aware decoding (CAD) which follows a contrastive output distribution that amplifies the difference between the output probabilities when a model is used with and without context. Our experiments show that CAD without additional training significantly improves the faithfulness of different LM families including OPT GPT LLaMA and FLAN-T5 for summarization tasks (e.g. 14.337; gain for LLaMA in factuality metrics). Furthermore CAD is particularly effective in overriding a models prior knowledge when it contradicts the provided context leading to substantial improvements in tasks where resolving the knowledge conflict is essential.
