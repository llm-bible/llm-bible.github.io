---
layout: publication
title: 'Genarm: Reward Guided Generation With Autoregressive Reward Model For Test-time Alignment'
authors: Yuancheng Xu, Udari Madhushani Sehwag, Alec Koppel, Sicheng Zhu, Bang An, Furong Huang, Sumitra Ganesh
conference: "Arxiv"
year: 2024
bibkey: xu2024reward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.08193"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Language Modeling', 'GPT', 'Pretraining Methods', 'Applications']
---
Large Language Models (LLMs) exhibit impressive capabilities but require
careful alignment with human preferences. Traditional training-time methods
finetune LLMs using human preference datasets but incur significant training
costs and require repeated training to handle diverse user preferences.
Test-time alignment methods address this by using reward models (RMs) to guide
frozen LLMs without retraining. However, existing test-time approaches rely on
trajectory-level RMs which are designed to evaluate complete responses, making
them unsuitable for autoregressive text generation that requires computing
next-token rewards from partial responses. To address this, we introduce
GenARM, a test-time alignment approach that leverages the Autoregressive Reward
Model--a novel reward parametrization designed to predict next-token rewards
for efficient and effective autoregressive generation. Theoretically, we
demonstrate that this parametrization can provably guide frozen LLMs toward any
distribution achievable by traditional RMs within the KL-regularized
reinforcement learning framework. Experimental results show that GenARM
significantly outperforms prior test-time alignment baselines and matches the
performance of training-time methods. Additionally, GenARM enables efficient
weak-to-strong guidance, aligning larger LLMs with smaller RMs without the high
costs of training larger models. Furthermore, GenARM supports multi-objective
alignment, allowing real-time trade-offs between preference dimensions and
catering to diverse user preferences without retraining. Our project page is
available at: https://genarm.github.io.
