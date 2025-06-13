---
layout: publication
title: 'Language Models Are Hidden Reasoners: Unlocking Latent Reasoning Capabilities Via Self-rewarding'
authors: Haolin Chen, Yihao Feng, Zuxin Liu, Weiran Yao, Akshara Prabhakar, Shelby Heinecke, Ricky Ho, Phil Mui, Silvio Savarese, Caiming Xiong, Huan Wang
conference: "Arxiv"
year: 2024
bibkey: chen2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.04282"}
  - {name: "Code", url: "https://github.com/SalesforceAIResearch/LaTRO"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) have shown impressive capabilities, but still
struggle with complex reasoning tasks requiring multiple steps. While
prompt-based methods like Chain-of-Thought (CoT) can improve LLM reasoning at
inference time, optimizing reasoning capabilities during training remains
challenging. We introduce LaTent Reasoning Optimization (LaTRO), a principled
framework that formulates reasoning as sampling from a latent distribution and
optimizes it via variational approaches. LaTRO enables LLMs to concurrently
improve both their reasoning process and ability to evaluate reasoning quality,
without requiring external feedback or reward models. We validate LaTRO through
experiments on GSM8K and ARC-Challenge datasets using multiple model
architectures. On GSM8K, LaTRO improves zero-shot accuracy by an average of
12.5% over base models and 9.6% over supervised fine-tuning across
Phi-3.5-mini, Mistral-7B, and Llama-3.1-8B. Our findings suggest that
pre-trained LLMs possess latent reasoning capabilities that can be unlocked and
enhanced through our proposed optimization approach in a self-improvement
manner. The code of LaTRO is available at
\url\{https://github.com/SalesforceAIResearch/LaTRO\}.
