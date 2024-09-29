---
layout: publication
title: 'RLPF: Reinforcement Learning From Prediction Feedback For User Summarization With Llms'
authors: Wu Jiaxing, Ning Lin, Liu Luyang, Lee Harrison, Wu Neo, Wang Chao, Prakash Sushant, O'banion Shawn, Green Bradley, Xie Jun
conference: "Arxiv"
year: 2024
bibkey: wu2024reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.04421"}
tags: ['Agentic', 'Applications', 'RAG', 'Reinforcement Learning']
---
LLM-powered personalization agent systems employ Large Language Models (LLMs) to predict users behavior from their past activities. However their effectiveness often hinges on the ability to effectively leverage extensive long user historical data due to its inherent noise and length of such data. Existing pretrained LLMs may generate summaries that are concise but lack the necessary context for downstream tasks hindering their utility in personalization systems. To address these challenges we introduce Reinforcement Learning from Prediction Feedback (RLPF). RLPF fine-tunes LLMs to generate concise human-readable user summaries that are optimized for downstream task performance. By maximizing the usefulness of the generated summaries RLPF effectively distills extensive user history data while preserving essential information for downstream tasks. Our empirical evaluation demonstrates significant improvements in both extrinsic downstream task utility and intrinsic summary quality surpassing baseline methods by up to 2237; on downstream task performance and achieving an up to 84.5937; win rate on Factuality Abstractiveness and Readability. RLPF also achieves a remarkable 7437; reduction in context length while improving performance on 16 out of 19 unseen tasks and/or datasets showcasing its generalizability. This approach offers a promising solution for enhancing LLM personalization by effectively transforming long noisy user histories into informative and human-readable representations.
