---
layout: publication
title: 'Self-controller: Controlling Llms With Multi-round Step-by-step Self-awareness'
authors: Xiao Peng, Xufan Geng
conference: "Arxiv"
year: 2024
bibkey: peng2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.00359"}
tags: ['Agentic', 'Applications', 'Tools']
---
The applications of large language models (LLMs) have been widely spread
across all domains. However, the basic abilities such as the controllability of
LLMs are still limited. To address this, we propose "Self-controller", a novel
agentic framework bringing self-awareness into LLMs' reasoning logic. The core
idea of this work is to maintain states based on the LLM's response, letting
the LLM become self-aware of current status and think step by step in a
multi-round chain-of-thought paradigm. Our experiment on the state of textual
length has shown the controllability and effectiveness of the Self-controller.
We further implement a binary search algorithm to accelerate the generation
process based on the linearity and monotonicity of the textual length state.
Another advantage of the Self-controller comes with DeepSeek's Context Caching
technology, which significantly saves computational token consumption when a
cluster of conversations shares the same prefix of context. Theoretically, we
prove that in this scenario the extra time complexity is \\(O(c log n)\\). Results
of the back-of-the-envelope estimation suggest that the token consumption of
our method is no more than twice as much as that of the trivial single-round
generation. Furthermore, our ablation study on word constraints demonstrates
the Self-controller's consistent controllability across all foundation models.
