---
layout: publication
title: 'Cosyvoice 2: Scalable Streaming Speech Synthesis With Large Language Models'
authors: Zhihao Du, Yuxuan Wang, Qian Chen, Xian Shi, Xiang Lv, Tianyu Zhao, Zhifu Gao, Yexin Yang, Changfeng Gao, Hui Wang, Fan Yu, Huadai Liu, Zhengyan Sheng, Yue Gu, Chong Deng, Wen Wang, Shiliang Zhang, Zhijie Yan, Jingren Zhou
conference: "Arxiv"
year: 2024
bibkey: du2024cosyvoice
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.10117'}
  - {name: "Code", url: 'https://funaudiollm.github.io/cosyvoice2'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Quantization', 'Reinforcement Learning']
---
In our previous work, we introduced CosyVoice, a multilingual speech
synthesis model based on supervised discrete speech tokens. By employing
progressive semantic decoding with two popular generative models, language
models (LMs) and Flow Matching, CosyVoice demonstrated high prosody
naturalness, content consistency, and speaker similarity in speech in-context
learning. Recently, significant progress has been made in multi-modal large
language models (LLMs), where the response latency and real-time factor of
speech synthesis play a crucial role in the interactive experience. Therefore,
in this report, we present an improved streaming speech synthesis model,
CosyVoice 2, which incorporates comprehensive and systematic optimizations.
Specifically, we introduce finite-scalar quantization to improve the codebook
utilization of speech tokens. For the text-speech LM, we streamline the model
architecture to allow direct use of a pre-trained LLM as the backbone. In
addition, we develop a chunk-aware causal flow matching model to support
various synthesis scenarios, enabling both streaming and non-streaming
synthesis within a single model. By training on a large-scale multilingual
dataset, CosyVoice 2 achieves human-parity naturalness, minimal response
latency, and virtually lossless synthesis quality in the streaming mode. We
invite readers to listen to the demos at
https://funaudiollm.github.io/cosyvoice2.
