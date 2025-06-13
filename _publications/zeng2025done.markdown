---
layout: publication
title: 'Done Is Better Than Perfect: Unlocking Efficient Reasoning By Structured Multi-turn Decomposition'
authors: Zihao Zeng, Xuyao Huang, Boxiu Li, Hao Zhang, Zhijie Deng
conference: "Arxiv"
year: 2025
bibkey: zeng2025done
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19788'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Reasoning Models (LRMs) are criticized for the excessively lengthy Chain-of-Thought (CoT) to derive the final answer, suffering from high first-token and overall latency. Typically, the CoT of LRMs mixes multiple thinking units; each unit attempts to produce a candidate answer to the original query. Hence, a natural idea to improve efficiency is to reduce the unit number. Yet, the fact that the thinking units in vanilla CoT cannot be explicitly managed renders doing so challenging. This paper introduces Multi-Turn Decomposition (MinD) to decode conventional CoT into a sequence of explicit, structured, and turn-wise interactions to bridge the gap. In MinD, the model provides a multi-turn response to the query, where each turn embraces a thinking unit and yields a corresponding answer. The subsequent turns can reflect, verify, revise, or explore alternative approaches to both the thinking and answer parts of earlier ones. This not only makes the answer delivered more swiftly, but also enables explicit controls over the iterative reasoning process (i.e., users may halt or continue at any turn). We follow a supervised fine-tuning (SFT) then reinforcement learning (RL) paradigm to realize MinD. We first rephrase the outputs of an LRM into multi-turn formats by prompting another LLM, and then tune the LRM with such data. Observing that the tuned model tends to consume even more tokens than the original one (probably due to that the multi-turn formats introduce additional answer tokens), we advocate leveraging RL algorithms like GRPO to prioritize correct outputs with fewer turns. Trained on the MATH dataset using R1-Distill models, MinD can achieve up to ~70% reduction in both output token usage and time to first token (TTFT), while maintaining competitive performance on reasoning benchmarks such as MATH-500, AIME24, AMC23, and GPQA-Diamond.
