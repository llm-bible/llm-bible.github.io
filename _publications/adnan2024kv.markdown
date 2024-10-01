---
layout: publication
title: 'Keyformer: KV Cache Reduction Through Key Tokens Selection For Efficient Generative Inference'
authors: Adnan Muhammad, Arunkumar Akhil, Jain Gaurav, Nair Prashant J., Soloveychik Ilya, Kamath Purushotham
conference: "Proceedings of the"
year: 2024
bibkey: adnan2024kv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09054"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Transformers have emerged as the underpinning architecture for Large Language Models (LLMs). In generative language models, the inference process involves two primary phases: prompt processing and token generation. Token generation, which constitutes the majority of the computational workload, primarily entails vector-matrix multiplications and interactions with the Key-Value (KV) Cache. This phase is constrained by memory bandwidth due to the overhead of transferring weights and KV cache values from the memory system to the computing units. This memory bottleneck becomes particularly pronounced in applications that require long-context and extensive text generation, both of which are increasingly crucial for LLMs. This paper introduces Keyformer, an innovative inference-time approach, to mitigate the challenges associated with KV cache size and memory bandwidth utilization. Keyformer leverages the observation that approximately 90&#37; of the attention weight in generative inference focuses on a specific subset of tokens, referred to as key tokens. Keyformer retains only the key tokens in the KV cache by identifying these crucial tokens using a novel score function. This approach effectively reduces both the KV cache size and memory bandwidth usage without compromising model accuracy. We evaluate Keyformer's performance across three foundational models: GPT-J, Cerebras-GPT, and MPT, which employ various positional embedding algorithms. Our assessment encompasses a variety of tasks, with a particular emphasis on summarization and conversation tasks involving extended contexts. Keyformer's reduction of KV cache reduces inference latency by 2.1x and improves token generation throughput by 2.4x, while preserving the model's accuracy.
