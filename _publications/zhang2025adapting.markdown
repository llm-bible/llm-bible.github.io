---
layout: publication
title: 'Adapting Large Language Models For Time Series Modeling Via A Novel Parameter-efficient Adaptation Method'
authors: Juyuan Zhang, Wei Zhu, Jiechao Gao
conference: "Arxiv"
year: 2025
bibkey: zhang2025adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13725"}
tags: ['Fine-Tuning', 'Transformer', 'Tools', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Tokenization', 'Pretraining Methods', 'Prompting']
---
Time series modeling holds significant importance in many real-world
applications and has been extensively studied. While pre-trained foundation
models have made impressive strides in the fields of natural language
processing (NLP) and computer vision (CV), their development in time series
domains has been constrained by data sparsity. A series of recent studies have
demonstrated that large language models (LLMs) possess robust pattern
recognition and reasoning abilities over complex sequences of tokens. However,
the current literature have yet striked a high-quality balance between (a)
effectively aligning the time series and natural language modalities, and (b)
keeping the inference efficiency. To address the above issues, we now propose
the Time-LlaMA framework. Time-LlaMA first converts the time series input into
token embeddings through a linear tokenization mechanism. Second, the time
series token embeddings are aligned with the text prompts. Third, to further
adapt the LLM backbone for time series modeling, we have developed a dynamic
low-rank adaptation technique (D-LoRA). D-LoRA dynamically chooses the most
suitable LoRA modules at each layer of the Transformer backbone for each time
series input, enhancing the model's predictive capabilities. Our experimental
results on an extensive collection of challenging real-world time series tasks
confirm that our proposed method achieves the state-of-the-art (SOTA)
performance.
