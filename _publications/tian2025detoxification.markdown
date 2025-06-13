---
layout: publication
title: 'Detoxification Of Large Language Models Through Output-layer Fusion With A Calibration Model'
authors: Yuanhe Tian, Mingjie Deng, Guoqing Jin, Yan Song
conference: "Arxiv"
year: 2025
bibkey: tian2025detoxification
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01266"}
tags: ['RAG', 'Merging', 'Security', 'Training Techniques', 'Prompting']
---
Existing approaches for Large language model (LLM) detoxification generally rely on training on large-scale non-toxic or human-annotated preference data, designing prompts to instruct the LLM to generate safe content, or modifying the model parameters to remove toxic information, which are computationally expensive, lack robustness, and often compromise LLMs' fluency and contextual understanding. In this paper, we propose a simple yet effective approach for LLM detoxification, which leverages a compact, pre-trained calibration model that guides the detoxification process of a target LLM via a lightweight intervention in its generation pipeline. By learning a detoxified embedding space from non-toxic data, the calibration model effectively steers the LLM away from generating harmful content. This approach only requires a one-time training of the calibration model that is able to be seamlessly applied to multiple LLMs without compromising fluency or contextual understanding. Experiment results on the benchmark dataset demonstrate that our approach reduces toxicity while maintaining reasonable content expression.
