---
layout: publication
title: 'Visionary-r1: Mitigating Shortcuts In Visual Reasoning With Reinforcement Learning'
authors: Jiaer Xia, Yuhang Zang, Peng Gao, Yixuan Li, Kaiyang Zhou
conference: "Arxiv"
year: 2025
bibkey: xia2025visionary
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14677"}
tags: ['Agentic', 'Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Prompting']
---
Learning general-purpose reasoning capabilities has long been a challenging problem in AI. Recent research in large language models (LLMs), such as DeepSeek-R1, has shown that reinforcement learning techniques like GRPO can enable pre-trained LLMs to develop reasoning capabilities using simple question-answer pairs. In this paper, we aim to train visual language models (VLMs) to perform reasoning on image data through reinforcement learning and visual question-answer pairs, without any explicit chain-of-thought (CoT) supervision. Our findings indicate that simply applying reinforcement learning to a VLM -- by prompting the model to produce a reasoning chain before providing an answer -- can lead the model to develop shortcuts from easy questions, thereby reducing its ability to generalize across unseen data distributions. We argue that the key to mitigating shortcut learning is to encourage the model to interpret images prior to reasoning. Therefore, we train the model to adhere to a caption-reason-answer output format: initially generating a detailed caption for an image, followed by constructing an extensive reasoning chain. When trained on 273K CoT-free visual question-answer pairs and using only reinforcement learning, our model, named Visionary-R1, outperforms strong multimodal models, such as GPT-4o, Claude3.5-Sonnet, and Gemini-1.5-Pro, on multiple visual reasoning benchmarks.
